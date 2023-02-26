# fixcyberpanel phpmyadmin
phpMyAdmin was extracted to the "/usr/local/CyberCP/public" by mistake.

Fix: Delete the extra folders from "/usr/local/CyberCP/public" that belong to phpMyAdmin

1 - Use the fix.sh or run its commands individually.

One click-command to fix the issue:
```
sh <(curl https://raw.githubusercontent.com/andrijs29/fixcyberpanel/main/fix.sh || wget -O - https://raw.githubusercontent.com/andrijs29/fixcyberpanel/main/fix.sh)
```
