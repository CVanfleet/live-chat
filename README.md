# Overview

In my two years of programming and developing applications, I have never created an app that uses a network to connect multiple clients! So I thought, what a great way to get my feet wet by creating a simple live chat!

This live chat uses the Client/Server approach, and getting connected is really easy! All you need to do is run the server.py script on a terminal/console window. The server will be the connector for the clients. Then you can open up other separate terminals to run the client.py script. This will connect to the server and you can now send messages back and forth to each other! 

To connect individual computers together, you will need the client ip target and the server ip target to be the ip address of your router, and then you just do the same process and talk to your friends/family over the network. 

[Software Demo Video](https://youtu.be/u7DsW936hJI)

# Network Communication

This program uses the client/server approach

Used TCP port # 1234

utf-8

# Development Environment

Visual Studio Code

Terminal

Python
- socket package
- select package
- sys package
- errno package

# Useful Websites

* [Python.org - socket](https://docs.python.org/3/library/socketserver.html)
* [Python.org - socketserver](https://docs.python.org/3/library/socket.html)

# Future Work

* Create a UI
* Rework to allow messages to populate automatically
* Think of a purpose to use this in the real world