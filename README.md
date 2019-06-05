# Snapd V2

## Modified version of the original code found [here](https://www.exploit-db.com/exploits/46361)
This modified exploit of the original exploit by @init_string, takes the command to execute from the command line and runs it as root. This removes the need to compile a snap everytime one needs to run a different command.

 > Usage : python CVE-2019-7304.py "touch /root/MUHAHA"

 # CAUTION 

If the systems is connected to the internet, it is better to run the original exploit [here](https://www.exploit-db.com/exploits/46361). As sideloading a snap will force an upgrade on snapd on some versions of Ubuntu. So you would want that command to be a good one. :)


Original Finder : [@init_string](https://twitter.com/init_string)   
Edited : [@D3fa1t](https://twitter.com/D3fa1t_)