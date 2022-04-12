 HVNC-2021 C++
Features:

Hidden Desktop (resize in accurate proportions for the best results)
Control Multiple Machines at Once
Open "Run"
Start Powershell
Start Chrome
Start Edge
Start Brave
Start Firefox
Start Internet Explorer
Usage:

In the Client's "Main.cpp" file, edit the ip and port variables.
In the Server's "Server.cpp" file, find "BOOL StartServer(int port)", and replace the port within "addr.sin_port = htons(6666);" with the port you want the Server to listen on.
Compile the Server & Client, and run the Server. Now, when the Client is executed, it will open a new "Hidden Desktop" window. If you right-click on the white bar at the top of the "Hidden Desktop" window, you can view the available commands that you can run on the target machine.

![image](https://user-images.githubusercontent.com/44816275/162880042-f0e2b59b-1876-4de3-a6ce-7f0a74cd1818.png)
![image](https://user-images.githubusercontent.com/44816275/162880080-d766a414-46cd-40f3-99db-d654c735932b.png)

![image](https://user-images.githubusercontent.com/44816275/162880120-f4f04bb4-9725-4d56-a63b-8210612abe3c.png)
![image](https://user-images.githubusercontent.com/44816275/162880212-51542f9e-3131-4c1a-84bd-1ca57bf84991.png)
