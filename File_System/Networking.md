# 4. Networking
## how do you find the ip address of your system?
```bash ip addr or ifconfig```
## how do you check active network connections?
```bash ss -tuln or netstat -tuln```
## how do you ping a host to check connectivity?
```bash ping host```
## how do you test port connectivity?
```bash telnet hostname port```
## how do you display routing infromation?
```bash route```
## how to you check open ports on your system?
```bash lsof -i```
## how do you download files from the internet?
```bash wget url```
## how do you transfer file between sysyems using scp(secure copy)?
```bash scp source_file user@remote _host:/destination_path```
using ssh
## how do you use ssh to connect to a remote server?
```bash ssh user@remote_host```
## how do you setup a static ip address?
edit the network configuration file e.g(/etc/network/interfaces)
