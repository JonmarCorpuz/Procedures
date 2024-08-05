TFTP Server
```Bash
#
sudo apt -y update && sudo apt -y upgrade

#
sudo apt-get -y install tftpd-hpa

#
TFTP_DIRECTORY="/var/lib/tftpboot"
TFTP_ADDRESS="<ip_address>:<port_number>"

#
TFTP_OPTIONS="{--secure|--create|--permissive|--blocksize|--port-range|--timeout|--retry-timeout|--address|--verbose}"
```
