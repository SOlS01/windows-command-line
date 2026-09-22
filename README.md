# windows-command-line


 

Windows command line >> 

Set > to show where the MS windows will execute the commands. 

Ver > to determine the windows operating system version 

Systeminfo > information about the system like processor, memory 

We can pipe the large contents with more so it will display page by page like systeminfo | more go to next page with space 

Ipconfig > to display our network information (ipconfig /all to see more information about network configuration) 

Network troubleshooting > we can use: 

ping target-Ip-address    ping google.com 

Tracert target-name     

Nslookup >> to looks up a host or domain and returns its IP address 

Netstat >> it will display current network connections and listening ports. Netstat –abon notice that after the local address there is the port which is service listening on port then find the name is on the left-hand side. 

 

Dir > to display the directories 

Dir /a to display hidden and system files 

Dir /s display files int he current directory and all subdirectory 

Or just type tree and it will be displayed like a tree 

Cd > for changing between directories cd .. means go back one step 

Mkdir > to make a directory 

Del/ move/ copy > for files 

Type > to see the content of a file 

To list running process > tasklist (to see the help page use /? After the command) (to find the running process related to notepad.exe = tasklist /FI “imagename eq notepad.exe”) to kill a process we use taskkill . 

 
