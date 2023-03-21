# Final_Project_Cyber_Management_System
NEU CS5008 Final Project

"Cyber Management System
The system consists of 2 modules: Client and Server. The server module is responsible for managing settings and client requests. On the other hand, the client component provides clients with internet access to the location's services. Both these parts have separate source code and run in sync with one another. The cyber management system can be programmed by utilizing the advanced features of C, such as socket programming and multithreading.
Topics covered: Socket Programming (basics), multithreading."

In this project, socket programming was used to connect the server and the client. After the server and the client components connected successfully, the client sent the text file “cyber.txt” generated by the “cyber_system.c” program to the server; the server sync the text file and converted the received file to a new text file named “cyber_received.txt”.

This project includes the following files:

1) cyber_system.cfile:providedfortheusertogenerate,manipulateandstorethe student data if they log in with correct username and password. The final student data was saved in cyber.txt.
2) client.c and server.c: contains codes for connection with socket programing and methods to send file and receive file.
3) theservercomponentacceptstheconnectrequestfromtheclientandsyncsthe file sent by its connected client, and the received file is named "cyber_received.txt".
