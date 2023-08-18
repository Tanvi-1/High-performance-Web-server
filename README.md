# High-performance-Web-server

This assignment is part of course work for CS 744 Design and Engineering of Computing Systems.
The link to problem statement is :
Building a simple echo server with multi-threading: https://github.com/cserl-iitb/bootcamp2022/tree/main/application_software/week2
Adding HTTP processing to the server: https://github.com/cserl-iitb/bootcamp2022/tree/main/application_software/week3
Adding master-worker thread pool: https://github.com/cserl-iitb/bootcamp2022/tree/main/application_software/week4
Creating load generator :  https://github.com/cserl-iitb/bootcamp2022/tree/main/application_software/week5

The scope of this assignment is to develop a HTTP web server which concurrently processes the incoming requests using one of its thread from its thread pool. The web server runs on local hist and upon client request it fetches the required page and return success or error accordingly.
The setup was tested using a closed loop load generator which emulated concurrent users to find out bottleneck components in the system.
