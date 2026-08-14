CLI is more efficient and less resource-demanding than a GUI, obviously.
cmd.exe is the built in Windows CLI tool
systeminfo -> command to view system, OS, processor etc. information

Network Troubleshooting:
ipconfig -> network info
ipconfig /all -> more detailed info like DNS servers, DHCP details, server's MAC address etc.
ping example.com -> check connection to website
tracert target_name -> trace the route to target website (all hops/routers on the way)
nslookup example.com -> return the IP address of a host or domain
netstat -> shows active connections and listening ports (netstat -h for help and see what other commands we can use with it)

File and Disk Management:
cd targetname -> change directory to target child destination
dir -> list child directories
tree -> visually represent child directories
mkdir name -> make directory
rmdir name -> remove directory
type name -> view contents of file
copy src dest -> copy file
move filename -> move file to current directory
del OR erase -> delete file
* to refer to multiple files e.g:
copy *.MD C:\Markdown -> copies all markdown files to directory Markdown
chkdsk -> checks the file system and disk volumes for errors and bad sectors
driverquery -> list installed and active device drivers
sfc /scannow -> scans system files for corruption and possibly repair them

Task and Process Management:
tasklist -> basically like Task Manager; shows all running tasks
tasklist /? -> help **rely on this to filter and sort e.g:
   tasklist /FI "filtername eq any.exe"
taskkill /PID ID -> kill task once process ID is known
shutdown /s -> shutdown
shutdown /r -> restart
shutdown /a -> abort scheduled shutdowns
