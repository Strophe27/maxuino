# maxuino
Software connection between Cycling '74's Max, Arduino compatible hardware, and Ableton Live, through Firmata

#This fork is about add TCP feature to Maxuino

##22-07-16

###Done :
- Full working with NodeMCU v2 with sadam.tcpClient as Max objectand, and StandardFirmataWifi on the Arduino

###To do :
####in maxuino.maxpat
- [ ] test with ethernet shield
- [*] make something to choose between serial or tcp connection
- [ ] make ip and port entries
- [ ] make auto init after connected
- [ ] make autoconnect after disconnect accidentaly
- [ ] add #0-from-tcp debug patcher

####in maxuino-gui.maxpat
- [*] make a chooser between serial and tcp
- [ ] make a tcp interface with :
  - [*] ip, port
  - [*] connect and disconnect button
  - [ ] a security button to desactivate 
    - [ ] the serial / tcp chooser
    - [ ] the ip, port and connect button
    - [ ] relese security when disconnect occurs
  - [ ] connection info (feedback sadam.tcpClient)

####in maxuino.amxd (Ableton m4l device)
- [ ] make a chooser between serial and tcp
- [ ] make a tcp interface with :
  - [ ] ip, port
  - [ ] connect and disconnect button
  - [ ] a security button to desactivate 
    - [ ] the serial / tcp chooser
    - [ ] the ip, port and connect button
    - [ ] relese security when disconnect occurs
  - [ ] connection info (feedback sadam.tcpClient)
