# NodePractice
study for Node

教程中mime选用的1.2.7版本
其中的mime.lookup在2.x.x中renamed 为getType()

socket.io报错解决方法：[TypeError]: fn.bind is not a function
版本问题
只需将io.socket.clients(room)改成io.sockets.adapter.rooms[room]即可
io.sockets.manager.rooms改成io.sockets.adapter.rooms