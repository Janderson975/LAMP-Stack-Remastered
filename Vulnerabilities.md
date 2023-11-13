# Vulnerabilities:

## Easy:
Forensics 1 and 2
Firewall enabled
Firewall logs all traffic
Removed the user Ofoe from the adm group
Removed the user Sessa
User Link created
Default minimum password age set
Default minimum password length set
SSH is configured correctly x3
Removed bad media file


## Medium:
Forensics 3 and 4
Port 22 is allowed
Port 443 is allowed
Removed the hidden user Wachter
Removed malicious bash script x2
sysctl.conf x3
apt gets packages from the correct repository
Malicious alias removed x3
Removed malicious sudoers configuration
Removed bad media file
Removed malicious cronjob



## Hard:
Forensics 5 and 6
Removed the hidden user deamon
Correct permissions on sshd_config
Stickybit set
Audits set up
Malicious mySQL table removed
Removed backdoor in /etc/profile.d
Forkbomb protection put into place 
Apache2 is configured correctly x4
MySQL is configured correctly x3
PHP is configured correctly x3
Samba is configured correctly x3
Removed malicious SUID permissions on binary files


## Advanced:
Forensics 7 and 8
Changed malicious IP tables configuration
Removed Bind9
SSH public key imported from the ftp server
Necessary files imported from ftp server and placed in /srv/ftp x2
