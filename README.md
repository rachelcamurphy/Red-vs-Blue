# Red-vs-Blue
Red vs. Blue Team Capstone Project This project presentation details 
both Red and Blue Team operations within a virtualized environment. 

The Red Team followed the following procedures in order to exploit the 
vulnerable machine:

- Utilized nmap for port enumeration and discovery of the vulnerable machine. 
- Utilized Hydra in order to crack the application administrator's password. 
- Utilized Crack Station to elevate privileges and gain access to an Administrator's account. 
- Utilized msfvenom to create a reverse shell script against the vulnerable server
- Utlized msfconsole to create a listener, gain a metepreter shell, and remotely execute commands against the vulnerable server

The Blue Team utilized Kibana in order to monitor and provide mitigations for the attack.

- Utilized log files to create Kibana dashboard
- Identified and provided mitigations for the nmap scan
- Identified and provided mitigations for the brute force attack
- Identified and provided mitigations for the reverse shell .php file upload
