# [Project Report] Chat Application
A prototype chat interacts with TCP/IP sockets, providing a reliable exchange of messages between users. 
Designed to communicate between users through a multi-user interface developed via the Windows presentation Foundation (WPF) following the architectural pattern of the MVVM,
as well as to demonstrate the basic functionality for the chat using modern user interface and current development tools. 
- Technologies Used: Windows Presentation Foundation (WPF), TCP/IP sockets, MVVM pattern.
- Programming Language: C#.
- Framework: .NET.

## Project Architecture
MVVM Pattern:
- Model: Handles the logic of an application.
- View: User interface components.
- ViewModel: Intermediary between the Model and View.

## Properties 
1. **Client-Server Architecture**
- *Server: Controlling incoming connections and manages client requests.*
- *Client: Interfaces with the user and communicates with the server.*

2. **User Interface (UI)**
- *Developed using WPF for a modern and responsive layout.*
- *Customizable window with controls for minimizing, maximizing, and closing.*
- *User list and chat area with real-time message updates.*

3. **Networking**
- *TCP/IP sockets for reliable communication.*

4. **Code Highlights**
- *RelayCommand for command binding in MVVM.*
- *UserModel for user data management.*
- *XAML for UI design, demonstrating a clean and organized structure.*
   
## Covering the requirements of laboratory works 
1. **Number of Classes**
   - *5 main classes: RelayCommand, UserModel, MainViewModel, PacketBuilder and PacketReader.*
2. **Number of Methods**
   - *Over 20, considering constructors, connection commands, message sending methods, and event handlers.*
3. **Inheritance Hierarchies and Polymorphism Cases**
   - MVVM often involves polymorphism and inheritance, so it is used frequently in ViewModel and Model components of this program.
4. **UI Elements**
   - Over 10, including main buttons of the application (minimize, maximize, close), lists (users, messages), input text fields, and elements displaying user status and messages.

## Future Enhancements
At this point, it is planned to add additional features like:
1. File sharing.
2. Voice and video calls.
3. UI/UX improvements for better user engagement.

## Sources and Code References
Throughout the development of this project, a wealth of educational resources were utilized to guide and enhance the coding process. Below are the key sources that greatly helped to write unique code:

- Networking and TCP/IP Sockets:
  
1. [TCP/IP Socket Programming for Coders Using C# .NET](https://www.udemy.com/course/tcpip-socket-programming-for-coders-using-csharp-net/)
    > This course provided in-depth knowledge on TCP/IP socket programming, crucial for implementing the reliable message exchange system in this chat application.

2. [C# TCP/IP Sockets Tutorial](https://youtu.be/AXpTeiWtbC8?si=5K3BFHAnQxTu2-iu)
    > A YouTube tutorial that offered practical insights into creating a networked application in C#, which was instrumental in developing the client-server architecture.

- Windows Presentation Foundation (WPF) and MVVM:
  
3. [WPF and MVVM Tutorials](https://www.youtube.com/playlist?list=PLrBlx8GuLtIFJHtOQl37b-kHNgk1FR3wk)
    >A playlist of tutorials on YouTube that provided a comprehensive guide on WPF and the MVVM pattern, essential for designing and structuring the user interface of the chat.

4. [WPF MVVM Step by Step](https://www.youtube.com/watch?v=V9DkvcT27WI&list=RDCMUCOoKt2u-bE1NuELXSFaEdUw&ab_channel=Payload)
    >Provided practical steps for implementing the MVVM pattern in WPF, which was pivotal in developing the data binding and command logic of this application.

5. [Understanding WPF and MVVM for Chat Applications](https://youtu.be/kxhvwGEqvcs)
    >This video helped to create a user-friendly interface and to manage data and commands in a chat application effectively, aligning well with the development techniques used in the project.



## Usage
To use the chat, follow these steps: 
1.	Copy the repository on your local machine. 
2.	Open the "Chat-app.sln" file in Visual Studio. 
3.	Build a solution. 
4.	Start the server by running a "Server" project. 
5.	Run multiple instances of the client by running the "Client" project. 
