# Firewall
Firewall is build base iptables, comment of rules are in Albanian.

So Firewall protect u from Dos attack and any other forms to detect you over the network.
Using this firewall by default you can use 443 port.
If u need custom rules for ssh or any service but write source and destination.
Anyone cant bruteforc your services... 

Parameter need to replace 
in this example have a Private IP class C 

INET_IFACE="your interface name"             # int name       
INET_ADDRESS="192.168.x.149"   # ip add

LOCAL_IFACE="wlp2s0"
LOCAL_IP="192.168.x.1"         # Gateway
LOCAL_NET="192.168.x.0/24"     # Network
LOCAL_BCAST="192.168.x.255"    # Broadcast


Its easy to setup 

git clone https://github.com/AdriatikMehmeti/Firewall.git

unzip Firewall-master.zip
cd Firewall-master
cp Firewall /usr/bin/Firewall
chmod +x /usr/bin/Firewall

Done 
just replace parameter needed 
nano /usr/bin/Firewall
after finish 
alt + F2 in box type Firewall 
