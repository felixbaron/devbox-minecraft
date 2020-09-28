# DevBox Minecraft

This DevBox helps you to launch your own bedrock Minecraft server in minutes.

```Shell
docker pull itzg/minecraft-bedrock-server
docker run -d -it -e EULA=TRUE -p 19132:19132/udp -v mydockervolume:/data itzg/minecraft-bedrock-server
```
