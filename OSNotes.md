# Day 1
Stack Number #14 - 10.50.27.50
Stack Number #13 - 10.50.24.234
https://os.cybbh.io/public/os/latest/index.html 

**Linux & Bash**
Commands to help gain situational awareness
  pwd, hostname or uname-a, whoami, w, who, ip addr, ifconfig, ip neigh or arp, ip route, route, ss or netstat, iptables -L (Firewall rules), sudo -l (displayes commands that can be ran at elevated privileges)

  *use "--help" to get info on commands*

  *File System*
    root of everything /
    essential user commands /bin
    user directories /home
    host-specific system config in /etc
    variable data files in /var

    /etc/passwd - all user accounts
    /etc/shadow - all user passwords
    /etc/groups - all groups

     use id command to get uid 
**Linux Boot Process**
commands
lsblk - lists block devices currently in use by linux

Get-Process (not sorted)
Tasklist
Get-Process | Sort -property ID | more (sorted by PID)
tasklist /m | more (display associated .dll's with services running)

(view services in command prompt)
sc query
net start
(view services in GUI)
services.msc
PsService

(viewing scheduled tasks)
Get-ScheduledTask | select * | select -First 1 (powershell, first task)
schtasks /query /tn "*name*" /v /fo list

Get-NetTCPConnection -state Established (show all connections in Established state)
netstat -anob | more (command line)

(viewing net connections in the GUI)
TCPView




  
