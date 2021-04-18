# minecraft-server

### Prequisite

1. install Java JDK latest and add in env variable path

## Windows:

1. install ngrok
2. from termial in the ngrock directory run:
   ### ngrok.exe tcp -region in 25565
3. another terminal session in the same directory run:
   ### java -Xm4096M -Xms4096M -jar server.jar nogui

## Linux / Mac

1. from shell in the ngrock dir run:
   ### ./ngrok.exe tcp -region in 25565
2. another shell session in the same directory run:
   ### java -Xmx1024M -Xms1024M -jar server.jar nogui

[Source](https://www.minecraft.net/en-us/download/server/)
