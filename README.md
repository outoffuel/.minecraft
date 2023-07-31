# .minecraft
kinda minecraft's dotfiles
<details>
<summary>how to install fabric<quilt> profile</summary>

### 1. download latest installer from [fabric](https://fabricmc.net/use/installer/),[quilt](https://quiltmc.org/en/install/)
### 2. run installer
![CopyQ YjSRdc](https://github.com/outoffuel/.minecraft/assets/47512014/12f779f3-f41f-4bc6-a655-dc455317cb60)
![CopyQ rucvCK](https://github.com/outoffuel/.minecraft/assets/47512014/31c04bbc-37ea-4987-bf75-9a5f0826ac7d)
### 3. create a directory where you want to put the minecraft game directory
  E.G.<br>
  ```D:\game\.minecraft\.minecraft_fabric1.20``` <br>
  ```D:\game\.minecraft\.minecraft_quilt1.20```
### 4. run minecraft launcher
Edit installation <br>
  Change Game Directory to you created before <br>
  Change Java Executable to <br>```D:\.scoop\apps\openjdk17\current\bin\javaw.exe``` <br>
  Change JVM Arguments <br>
  ```
  -Xms8G -Xmx8G -XX:MaxNewSize=2G -XX:MetaspaceSize=2G -XX:MaxMetaspaceSize=2G -XX:+UseG1GC -XX:MaxGCPauseMillis=100 -XX:ParallelGCThreads=8 -XX:ConcGCThreads=8 -XX:+DisableExplicitGC
  ```
### 5. run minecraft
### 6. install mods,saves under game directory you created before
</details>

### backup to mega.nz every 30mins
```
backup 'D:\game\.minecraft' /.minecraft --period="0 30 * * * *" --num-backups=2
```
