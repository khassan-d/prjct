# [Project] Chat Application
A prototype chat interacts with TCP/IP sockets, providing a reliable exchange of messages between users. 
Designed to communicate between users through a multi-user interface developed via the Windows presentation Foundation (WPF) following the architectural pattern of the MVVM,
as well as to demonstrate the basic functionality for the chat using modern user interface and current development tools. 


## Properties 
- **Multi-user interface:** A convenient and modern UI for communicating with many users at a time. 
-	**Architecture:** The server listens to incoming connections on the specified port number, allowing users to connect to the server and communicate with each other via text messages.  When the client is connected, the server creates a new thread to handle the client's requests.  Each client is identified by a unique identification number. 
-	**WPF Design:** Windows presentation Foundation (WPF) is used to create a modern and attractive interface design. 
-	**TCP/IP sockets:** The use of TCP/IP protocol to ensure stable and reliable messaging between users. Exchange of messages in real time.
  
## Repository content 
1.	Client part (UI provided) 
2.	Server part (Console)
   
## Covering the requirements of laboratory works 
-	Object-oriented programming (OOP): The project is implemented in accordance with the principles of OOP and with the data structures that these principles implement. 
-	Graphical User interface (GUI): Graphical interface in the form of desktop application. 
-	External libraries: Active use of external libraries.
  
## Usage
To use the chat, follow these steps: 
1.	Copy the repository on your local machine. 
2.	Open the "Chat-app.sln" file in Visual Studio. 
3.	Build a solution. 
4.	Start the server by running a "Server" project. 
5.	Run multiple instances of the client by running the "Client" project. 
