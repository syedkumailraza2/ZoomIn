# ZoomIn -  The Video conferencing App

packages used:

frontend:
- react-router-dom : for routing
- socket.io-client : to handle websocket on frontend

backend:
- socket.io

screens:
-lobby
-room

imp files: 
- client/src/App.js : handle all the routings
- client/src/screens/Lobby.jsx : this contains code of lobby screen
- client/src/screens/Room.jsx : thia contains code of web rtc room
- client/src/context/SocketProvider.jsx : this contain the code of handling web sockets
- client/src/service/peer.js : this contain the code of handling web rtc