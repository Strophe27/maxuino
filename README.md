# maxuino
Software connection between Cycling '74's Max, Arduino compatible hardware, and Ableton Live, through Firmata

#This fork is about add TCP feature to Maxuino

##22-07-16

###Done :
- Full working with NodeMCU v2 with sadam.tcpClient as Max objectand, and StandardFirmataWifi on the Arduino

###To do :
####in maxuino.maxpat
- [ ] test with ethernet shield
- [x] make something to choose between serial or tcp connection
- [ ] make ip and port entries
- [ ] make auto init after connected
- [ ] make autoconnect after disconnect accidentaly
- [ ] add #0-from-tcp debug patcher

####in maxuino-gui.maxpat
- [x] make a chooser between serial and tcp
- [ ] make a tcp interface with :  
      - **Work in progress in  RPJ test TCP 1.amxd** (*amxd because I'm on Max4Live... if you need maxpat, open an issue*)
  - [x] ip, port                    
      - *There is a bpatcher needed, stored on work_in_progress_TCP\support\ maxuino-gui-choose-serial-ip.maxpat*
  - [x] connect and disconnect button
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
