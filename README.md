# Command
1. apt-get update && apt-get upgrade -y && update-grub && sleep 2 && reboot
2. sysctl -w net.ipv6.conf.all.disable_ipv6=1 && sysctl -w net.ipv6.conf.default.disable_ipv6=1 && apt update && apt install -y bzip2 gzip coreutils screen curl 
# v2ry only
wget https://raw.githubusercontent.com/rioxy/AutoScriptSSH/main/ins-vt.sh && chmod +x inst-vt.sh && sed -i -e 's/\r$//' ins-vt.sh && screen -S ins-vt ./ins-vt.sh
