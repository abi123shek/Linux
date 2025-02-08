# 8. Advanced Networking

## how do you configure a network interface?
``` ip addr add IP_ADDRESS dev interface```
## how do you bring an interface up or down?
``` ip link set interface up or ip link set interface down```
## how do you test DNS resolution?
``` nslookup domain_name```
## how do you display ARP table entries?
``` arp -a ```
## how do you configure a firewall using iptables?
``` iptables -A INPUT -p tcp --dport port -j ACCEPT```
## how do you check open ports on system?
``` ss -tuln```
## how to you trace the route to a host?
``` traceroute hostname```
## how do you monitor packet flow?
``` tcpdump```
## how do you edit the hosts file?
``` nano or vim /etc/hosts
