# Remotely-visible-IDE   -- This is a client-server architecture of remote sharing desktop application with access of mouse and keyboard of client PC with serverPC. 
WE have to run codes of client.main and server.main in two different pc's to make a connection between them (both system should be in same network). 

Brief description of project:
 - This application works similar  to TeamViewer but only for a LAN
- Server PC can control many Client PCs

Functionalities of project:
- Server PC can view desktop of client PCs
- Server PC can control client PCs with server's mouse and keyboard

  How to use-
- Connect two/more laptops/PCs in same network
- Start server program on one PC/laptop. Use port as 50500
- Start client program on other PCs/laptop. Enter LAN IP of server PC (obtained by ipconfig/ifconfig on server PC for Windows/Linux) and port as 50500
- Once connected properly, you can view and control client PC from server PC

TECHNOLOGIES USED- Java, socketProgramming, javaSwing, opps, java networking
