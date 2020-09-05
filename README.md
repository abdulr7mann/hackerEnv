### Reach me at:
- [![Twitter](https://img.shields.io/twitter/follow/abdulr7mann?style=social)](https://twitter.com/intent/follow?screen_name=abdulr7mann)
- [![Discord](https://user-images.githubusercontent.com/7288322/34429152-141689f8-ecb9-11e7-8003-b5a10a5fcb29.png?label=Join&amp;style=social)](https://discord.gg/pN5dPYu)

# hackerEnv [![Tweet](https://img.shields.io/twitter/url/http/shields.io.svg?label=Tweet%20it&amp;style=social)](https://twitter.com/intent/tweet?text=hackerEnv%20-%20an%20automation%20tool%20that%20quickly%20and%20easily%20sweep%20ips%20and%20scan%20ports,%20vulnerablities%20and%20exploit%20them%20and%20generates%20a%20report.%20by%20@abdulr7mann%20https://github.com/abdulr7mann/hackerEnv.git&hashtags=security,hacking,redteam,pentester,pentest,kali,kali-linux)
hackerEnv is an automation tool that quickly and easily sweep IPs and scan ports, vulnerabilities and exploit them. Then, it hands you an interactive shell for further testing. Also, it generates HTML and docx reports.
It uses other tools such as nmap, nikto, metasploit and hydra. Works in kali linux and Parrot OS. Do not run it in Qterminal, works in gnome-terminal, terminator and tmux.
This tool was NOT coded by a professional, I do not know what i am doing. 
**This was a school project, which means i am not gonna work on it any more. However, In the faaaaaaaaaaar future, I will make a python framework that does better job than this shitshow.**
By running this program, you are agreeing on NOT running it against any public, corporate or unauthorized networks.
Performed only when you have authorization to do.
Greetz to @R2k4n
## Update Kali/Parrot
```
apt update; apt upgrade -y
```

### Download hackerEnv
```
cd /opt/
git clone https://github.com/abdulr7mann/hackerEnv.git
cd /opt/hackerEnv
chmod +x hackerEnv
```

### If you want to use it anywhere on the system, create a shortcut using:
```
ln -s /opt/hackerEnv/hackerEnv /usr/local/bin/
```

### Usage:
```
Usage:
    hackerEnv <flag> <argument>

Examples:
    hackerEnv -t 10.10.10.10
    hackerEnv -t "10.10.10.10\n20.20.20.20"
    hackerEnv -t 10.10.10.10 -i eth0
    hackerEnv -i eth0 -s 24
    hackerEnv -s 24
    
Flages:
    hackerEnv -h, --help          Display this help message.
    hackerEnv --update            Update tool.
    hackerEnv                     Scan the entire network.
    hackerEnv -t                  Pass a specific target's IP.
    hackerEnv -t                  Pass mutipule targets' IPs e.g. hackerEnv -t "10.10.10.10\n20.20.20.20"
    hackerEnv -i                  To specify an interface.
    hackerEnv -a                  Pass attacker's IP.
    hackerEnv -s                  To specify subNetwork 24 or 23 etc. exclude /
    hackerEnv -e, --aggressive    Enable aggressive port scan
    hackerEnv -oA                 genetrate report in HTML and DOCX format
```
[![YouTube video](https://i.imgur.com/cwJ80Pa.png)](https://www.youtube.com/watch?v=-r5iDrLF4xU)
### in Gnome terminal
![alt text](https://i.imgur.com/uHk0Ypt.png)
### in tmux
![alt text](https://i.imgur.com/ppCLMUw.png)
### Report
![alt text](https://i.imgur.com/CCbcKMJ.png)
