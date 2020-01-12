
# Plz add our HackerEnv.com community server on discord: https://discord.gg/sB5ruJ6

# hackerEnv
This tool uses other tools in kali linux and it performs ip sweep, port, vulernablities scan, exploit vulernablities and generates a report
This tool, was NOT coded by a professional{I do not know what i am doing}, works in Kali Linux ONLY and you must be root.
By running this program, you are agreeing on NOT running it aginst any public, corporate or unauthorized networks.
Performed only when you have authorization to do.
# Update Kali
```
apt update; apt dist-upgrade -y
```
# Donwload hackerEnv
```
cd /opt/
git clone https://github.com/abdulr7mann/hackerEnv.git
chmod +x hackerEnv
```

# Usage:
```
bash /opt/hackerEnv -h             Display this help message.
bash /opt/hackerEnv                Scan the entire network.
bash /opt/hackerEnv -t <ip>        Pass a specific target's IP.
bash /opt/hackerEnv -t <'ip\nip'>  Pass mutipule targets' IPs. Ex: '10.10.10.10\n20.20.20.20'
bash /opt/hackerEnv -i <eth0>      To specify an interface.
bash /opt/hackerEnv -a <ip>        Pass attacker's IP.
bash /opt/hackerEnv -s </24>       To specify subNetwork 10.10.10.10/24 or /23 etc.
bash /opt/hackerEnv -e		         Enable aggressive port scan
```
