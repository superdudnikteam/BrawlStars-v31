# Brawl Stars v31

Brawl Stars v31.96 server emulator written in Python.

![ScreenShot](https://cdn.discordapp.com/attachments/874296198775853117/889799539232481300/Screenshot_20210921-120310_BS_v31.jpg) 

### Requirements:
- Python 3.7 or higher
- pymongo
- dnspython
- colorama

### MongoDB configuration
First you'll need to put your MongoDB connection string in `config.json`. If you don't know how to get it here's a quick tutorial: https://imgur.com/a/oXI34dA

### Running the server
In a terminal, type __`pip install -r requirements.txt`__ then run the server using __`python Main.py`__

### Configuring the client app
To connect to your server, a **patched client** is required. Download this [base APK](https://mega.nz/file/KKxw2ZwR#ss4_VDlSynrV8FHMHjmpH5QdMdOiBoGEenXgp0QmqxY) and change the IP in `libmg.config.so`. 
### Battles
We've enabled offline battles so you can directly press "PLAY" to start a match.
![ScreenShot](https://cdn.discordapp.com/attachments/874296198775853117/889797850710548540/Screenshot_20210921-115836_BS_v31.jpg) 
Unfortunately, the offline logic is mostly broken and some gamemodes might not work correctly or even crash.

### Got any question?
Contact @ShockWave#5158 on Discord or open an issue.
