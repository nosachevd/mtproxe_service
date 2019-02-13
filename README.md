
# MTProxy service

MTProto Proxy custome service fro RHEL/CentOS 6

#### Requirements
- Installed and configured application - https://github.com/TelegramMessenger/MTProxy
- Generated secret key
- Open 443 port in firewall  

#### Usage
In script find and replace **%%SECRET_KEY%%** to your generated secret key, example

SECRET_KEY="%%SECRET_KEY%%"
to
SECRET_KEY="auhf98YEYDFHYA*YFyhgefhsaef"

Service support standard command

service mtproxyd start
service mtproxyd stop
service mtproxyd status
service mtproxyd restart

Service also can be started with OS:

chkconfig mtproxyd on
