Project Synopsis
Using a BeagleBone Black we send messages, over bluetooth, to a NXT Mindstorm brick. The NXT robot maps a room by measuring distances with a NXT IR proximity sensor. Mapped information is displayed on a website with node.js server. Other functionality includes manually controlling the NXT robot using the website interface, manually controlling the robot using the zencape joystick, and increasing/decreasing it’s movement speed using the potentiometer.

Instructions to Run
On your host machine run make to compile the project
On the target device, the application can be found under the public/myApps/ directory
From there navigate to the nxt-server-backup folder
Run node server.js &
Switch back to the project's main directory
Run ./nxtMapper
Access the website by going to 192.168.7.2:8088
Docs
The docs folder contains a guide (FinalProjectGuide.pdf) on how to connect the BeagleBone Black to the NXT brick using bluetooth. Also included are some retrospective documents to review our iterations of this project.
