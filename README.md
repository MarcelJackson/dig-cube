# RTRSBOX 
Opensource realtime remote sensor box.

Overview - 

The intent is to provide a client server model for relaying remote information for the end user in situations in which is impractical for the user to be where the hardware is deployed. The design process is so that a user can check his client and find information that the actual hardware deployed in the remote  locations is viewing. Because of its capability in not only scripting but also in application development the Python language has been chosen. For choice of techonology software wise, I have decided to go with an simple linux executable. This is because the target hardware platforms that would normally run such an server would be linux based. There could possible be made a cross compatilbe application as well with Windows and OSX based systems but that would require a compiling the binary for each platform. The software is open source meaning that it can be distributed and modified as needed by future users and developers. The client server software solution in its original form is intended for  enthusiasts and users who want to experiment with remote management capabilities of deployed hardware. Testing will be done on a case basis. Will originally be tested for common faults with further testing done with field use. 

There are three main parts to this system 

Server - runs on the hardware, recieves input from sensors and relays that information to the client
 
Client - runs on the users system. Recieves the data from the server and makes it available to the end user 

GUI - This is what the end user will interface with, is more of a design focus and is basically integrated with the client
