`   `</p>
`yum -y install wget`</p>
`yum -y install unzip`</p>
`wget https://github.com/fanyuanqi/SFORWEB/archive/master.zip`</p>
`unzip master.zip`</p>
`chmod -R 777 SFORWEB-master`</p>
`cd SFORWEB-master`</p>
`cp /etc/localtime /etc/localtime.bak`</p>
`ln -svf /usr/share/zoneinfo/Asia/Shanghai /etc/localtime`</p>
`bash install.sh`</p></p>






![Shadowsocks](https://github.com/teddysun/shadowsocks_install/raw/master/shadowsocks.png)
# Auto install Shadowsocks Server

shadowsocks.sh
===============
- Description: Auto Install Shadowsocks(Python) Server for CentOS/Debian/Ubuntu
- Intro: https://teddysun.com/342.html

shadowsocks-libev.sh
===============
- Description: Auto Install Shadowsocks(libev) Server for CentOS
- Intro: https://teddysun.com/357.html

shadowsocks-libev-debian.sh
===============
- Description: Auto Install Shadowsocks(libev) Server for Debian/Ubuntu
- Intro: https://teddysun.com/358.html

shadowsocks-go.sh
===============
- Description: Auto Install Shadowsocks(Go) Server for CentOS/Debian/Ubuntu
- Intro: https://teddysun.com/392.html

shadowsocks-crond.sh
===============
- Description: Check Shadowsocks(All version) Server is running or not, and start it if not running
- Intro: https://shadowsocks.be/6.html

shadowsocksR.sh
===============
- Description: Auto Install ShadowsocksR Server for CentOS/Debian/Ubuntu
- Intro: https://shadowsocks.be/9.html

shadowsocks-all.sh
==================
- Description: Auto Install Shadowsocks Server (all version) for CentOS/Debian/Ubuntu
- Intro: https://teddysun.com/486.html

haproxy.sh
===============
- Description: Auto Install haproxy for Shadowsocks Server
- Intro: https://shadowsocks.be/10.html

Copyright (C) 2014-2017 Teddysun <i@teddysun.com>
