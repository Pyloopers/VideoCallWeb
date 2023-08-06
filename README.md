# VideoCallWeb
Using websocket and rtc for lan users only because need ip to connect.
Check your ip address and make sure your devices( sender and reciever are connected with the same network)
Copy the common ip to do so:
start terminal and type "ifconfig|grep inet"
and copy the ip address paste it to the ws://YouripAdress:3000 in reciever.js and sender.js .
then go to the directory where server.js is located.
open that folder in terminal and run following command: node /server.js
and then open sender.html and username should be the same both sides.
