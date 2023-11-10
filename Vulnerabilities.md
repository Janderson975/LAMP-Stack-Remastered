# Vulnerabilities:

## Easy:
Forensics 1 and 2
Firewall enabled
Firewall logs all traffic
Removed the user Will from the adm group
Removed the user Sessa
User James has a strong password (?)
Default minimum password age set
Default minimum password length set
SSH is configured correctly x3
Removed bad media file


## Medium:
Forensics 3 and 4
Port 22 is allowed
Port 443 is allowed
Removed the hidden user Ginger
Removed Steam (?)
Removed Virtual Box (?)
sysctl.conf x3
apt gets packages from the correct repository
Malicious alias removed x3
Removed malicious sudoers configuration
Removed bad media file



## Hard:
Forensics 5 and 6
Removed the hidden user deamon
Correct permissions on sshd_config
Stickybit set
Audits set up
Malicious mySQL table removed
Removed backdoor in /etc/profile.d
Forkbomb protection put into place
Apache2 set to its own directory
Apache2 is configured correctly x3
MySQL is configured correctly x3
PHP is configured correctly x3
Samba is configured correctly x3
Removed malicious SUID permissions on binary files


## Advanced:
Forensics 7
Changed malicious IP tables configuration
Removed Bind9
Machine is disconnected from LDAP server


49
