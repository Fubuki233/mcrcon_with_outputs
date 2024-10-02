How to use:
1. You need to put mcrcon.exe to the same path as the server kernel
2. As the same useage of original version, you need to enable rcon in server.properties and set rcon port and ip:
example:
   enable-rcon=true
   rcon.port=25576
   rcon.ip=0.0.0.0
   rcon.password=1
4. In terminal, move to your server's root path and connect to your server with rcon ip, port and password:
   cd x:/your-server-path
   ./mcrcon -H 127.0.0.1 -P 25576 -p 1 -t

For more help, type ./mcrcon -h


----------------------------------------------------------------------------------------------------------------------


如何使用：
1. 你需要把mcrcon.exe放到与服务器核心相同的路径（服务端根目录）
2. 与原版mcrcon相同, 你需要先在server.properties启用rcon并设置ip与端口:
例如:
   enable-rcon=true
   rcon.port=25576
   rcon.ip=0.0.0.0
   rcon.password=1
4. 在终端中切换到服务端根目录并启动,注意需要使用rcon的ip与密码:
   cd x:/your-server-path
   ./mcrcon -H 127.0.0.1 -P 25576 -p 1 -t

更多帮助请输入./mcrcon -h

----------------------------------------------------------------------------------------------------------------------
