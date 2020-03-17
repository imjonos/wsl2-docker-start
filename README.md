# wsl2 docker start script
Script adding wsl2 and winhost to windows hosts file
File Windows/System32/drivers/etc/hosts should be writebable for user from which launched WSL2

# How to use
1) Copy to /usr/local/bin
2) $ docker-start
3) Enjoy!)

Your docker server now available here tcp://wsl2:2375
And any other services 

# xDebug config examle

zend_extension=xdebug.so <br>
xdebug.remote_host=winhost <br>
xdebug.remote_enable=1 <br>
xdebug.remote_port=9000 <br>
xdebug.remote_connect_back=0 <br>
xdebug.idekey=PHPSTORM<br>
xdebug.remote_autostart=1<br>
xdebug.remote_log = /home/user/xdebug.log<br>
