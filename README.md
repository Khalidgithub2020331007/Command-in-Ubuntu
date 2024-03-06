# Command-in-Ubuntu

# Cheak Port Adress:
    sudo lsof -i -P -n | grep LISTEN

# Apache Status
    sudo systemctl status apache2
# Apache Start
    sudo systemctl start apache2
# Apache restart
    sudo systemctl stop apache2
# Apache Stop
    sudo systemctl restart apache2
# Wifi speed test
Only for 1st time install it:
```
sudo apt install speedtest-cli
```
Then run this command to cheack net speed:
```
speedtest-cli
```
