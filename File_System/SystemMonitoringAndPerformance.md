# 7. System Monitoring and Performance
## how do you check system uptime?
``` uptime```
## how do you display memeory usages?
``` free -h ```
## how do you monitor disk I/O in real-time?
``` iostat```
## how do you check CPU usages?
``` top or htop```
## how do you check running services?
``` systemctl list-units --type=service```
## how do you enable a service to start on boot?
``` systemctl enable service_name```
## how do you check system load averages?
``` uptime -r cat /proc/loadavg```
## how do you moinityor network traffic in real-time?
``` iftop or nload```
## how do you list hardware infromation?
``` lshw ```
## how do you check kernel version?
``` uname -r```
