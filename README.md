
# Join us on hackerEnv server discord:
https://discord.gg/sB5ruJ6

# hackerEnv
HackerEnv is an automation tool that quickly and easily sweep ips and scan ports, vulnerablities and exploit them and generates a report.
It uses other tools such as nmap, nikto, metasploit and hydra. Works in kali-linux-2019.3a and Parrot OS. It has some problems in kali-linux-2019.4 still working in fixing them.
I am adding features and vulnerablities exploits consistently. Also, soon there will be a GUI version.
This tool was NOT coded by a professional, "I do not know what i am doing".
By running this program, you are agreeing on NOT running it aginst any public, corporate or unauthorized networks.
Performed only when you have authorization to do.
Greetz to @R2k4n
# Update Kali
```
apt update; apt upgrade -y
```
# Donwload hackerEnv
```
cd /opt/
git clone https://github.com/abdulr7mann/hackerEnv.git
cd /opt/hackerEnv
chmod +x hackerEnv
```

# If you want to use it anywhere on the system, create a shortcut using:
```
ln -s /opt/hackerEnv/hackerEnv /usr/local/bin/
```

# Usage:
```
Usage:
    hackerEnv <flag> <argument>

Example:
    hackerEnv -t 10.10.10.10
    hackerEnv -t "10.10.10.10\n20.20.20.20"
    hackerEnv -t 10.10.10.10 -i eth0
    hackerEnv -i eth0 -s 24
    
Flages:
    hackerEnv -h, --help          Display this help message.
    hackerEnv --update            Update tool.
    hackerEnv                     Scan the entire network.
    hackerEnv -t                  Pass a specific target's IP.
    hackerEnv -t                  Pass mutipule targets' IPs separated by comma Ex: hackerEnv -t 10.10.10.10,20.20.20.20
    hackerEnv -i                  To specify an interface.
    hackerEnv -a                  Pass attacker's IP.
    hackerEnv -s                  To specify subNetwork 10.10.10.10/24 or /23 etc exclude /
    hackerEnv -e, --aggressive    Enable aggressive port scan
```
# in Gnome terminal
![alt text](https://i.imgur.com/uHk0Ypt.png)
# in tmux
![alt text](https://i.imgur.com/ppCLMUw.png)
# Report
![alt text](https://i.imgur.com/CCbcKMJ.png)
