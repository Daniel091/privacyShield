# PrivacyShield
- Node, Express - Backend Server: `npm run server`
- React App in client directory
- Running both: `npm run dev`


## Node Libaries we may use
- https://github.com/node-pcap/node_pcap
 

- Raspberry: pi24
- privacyshieldwifi 


## IP-Adress Display ✅
- Tutorial: https://projects.raspberrypi.org/en/projects/getting-started-with-the-sense-hat/2 

## Remote Development
- https://code.visualstudio.com/docs/remote/ssh


# Remove Mongodb
https://askubuntu.com/questions/147135/how-can-i-uninstall-mongodb-and-reinstall-the-latest-version
Install sqlite3: https://github.com/converge/instapy-dashboard/issues/19


# Iptables, Blacklisting-Approach
- `sudo modeprobe br_netfilter` to enable iptables (netfilter) on bridge interface
-  Setup Rule for MAC: `sudo iptables -A FORWARD -m mac --mac-source XX:XX:XX:XX:XX:XX -j DROP`
- Delete Rule for MAC: `sudo iptables -D FORWARD -m mac --mac-source XX:XX:XX:XX:XX:XX -j DROP`



Delete Rule:
iptables -D 
