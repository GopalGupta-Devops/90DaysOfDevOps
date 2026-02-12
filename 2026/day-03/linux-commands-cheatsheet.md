Day 3
Process ammand

ps aux → Show all running processes
top / htop → Monitor processes in real time
kill <PID> → Terminate a process by ID
pkill <name> → Kill processes by name
jobs → List background jobs

File system cammand

ls -l → List files with details
pwd → Show current directory
cd <dir> → Change directory
cp <src> <dest> → Copy files
mv <src> <dest> → Move or rename files
rm <file> → Delete file
find /path -name <file> → Search for a file
df -h → Show disk usage
du -sh <dir> → Show directory size



Networking Troubleshooting
ping <host> → Test connectivity
curl <url> → Fetch data from a URL
wget <url> → Download files
ifconfig / ip addr → Show network interfaces
netstat -tulnp → List open ports and services
ss -tuln → Modern replacement for netstat
traceroute <host> → Trace route to host
nslookup <domain> / dig <domain> → DNS lookup
telnet <host> <port> → Test connectivity to a port
