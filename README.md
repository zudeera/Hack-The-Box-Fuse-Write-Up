![alt text](https://github.com/zudeera/Hack-The-Box-Fuse-Write-Up/blob/main/Fuse.jpg?raw=true)
# Hack-The-Box-Fuse-Write-Up
This is a write up about the Windows box Fuse.

The whole scenario was to exploit an automated printer installment process. There is webpage related to this printer which contains some usernames which can be used for the enumeration of guessing passwords. And by querying the domain controller you can get the password of the service account which you can use later to get a reverse shell to the domain controller. Printer service account has the privileges to load drivers. So we will load a malicious driver for the privilege escalation.
