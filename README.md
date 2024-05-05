Setup verysync on Kindle
==========================

1. You need jailbreak and [KULA](http://www.mobileread.com/forums/showthread.php?t=203326) first.
2. Download this [repository](https://github.com/powersee/verysync-kindle/archive/master.zip)
3. Download [verysync-linux-arm](https://www.verysync.com/download.php?platform=linux-arm) and copy `verysync` binary to `verysync/bin/`
4. Connect Kindle Touch to Your PC
5. Copy `verysync/` to `KINDLE-ROOT/extensions/verysync/`
6. Select "Open Firewall for Kindle" from KUAL
7. Select "Start verysync INSECURE Admin" from KUAL
8. Find out your Kindle IP address by type `;711` in search, then open `http://IP-ADDRESS:8886` in your browser. <br>
9. Configure all peers and folders
10. Ignore kindle auto generated index files: `*.sdr`
11. Select "Close INSECURE Admin port" from KUAL (Optional, for security reason)
12. Select "Stop verysync" and then "Start verysync" from KUAL
13. Note: connect kindle to computer or restart kindle will terminate verysync process and firewall.
