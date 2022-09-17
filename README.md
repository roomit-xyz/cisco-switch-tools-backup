# DONATE

1. Ethereum : <pre>0xB0e6e6c379389bBB30fACD427e02d74d27ec0C78</pre>
2. Near Blockchain : <pre>xoreth.near</pre>
3. Mina Protocol : <pre>B62qiiBBXKN5CdgXv7wPkXxC1prdzQxwfaTMAi3isAeb9F7gCbzi5dU</pre>


# CISCO SWITCH BACKUP CONFIG#

As such a title, this tools for automatic network configuration backup switch cisco.

## License ##
```bash
 ---------------------------------------------------------------------------------
 "THE BEER-WARE LICENSE" (Revision 42):
 <phk@FreeBSD.ORG> wrote this file.  As long as you retain this notice you
 can do whatever you want with this stuff. If we meet some day, and you think
 this stuff is worth it, you can buy me a beer or coffee in return. Poul-Henning Kamp
 ---------------------------------------------------------------------------------
 
 Created : Dwiyan
 https://panthalassa.eth
 https://github.com/luneareth
```
## Requierment ##

* python3
* configparser
* pip3
* paramiko



Install Depedency
```bash
pip3 install -r req.txt
```


# CISCO SWITCH #
## How to Play Cisco Switch?? ##
This script can handle backup via telnet and ssh, if telnet not worked so ssh can be handle for backup.
Example, we have added in switch-cisco.cfg cisco switch-f:

```bash
[asa-01]
IP = xxx.xxx.xxx.xxx # IP Firewall
USER = user_administrator # User Admin
PASSWORD = password_user_administrator # Password
ENABLE = password_mode_administrator # Password Root Enable
PATH = /data/backup/data # Directory save your confiuration
```

## How To Use? ##

```bash
python3 switch-cisco-backup

```
