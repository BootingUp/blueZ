# blueZ-5.45

官网： [http://www.bluez.org/](http://www.bluez.org/) 



## 编译

方法一：使用systemd
` ./configure --prefix=/usr/local/bluez5/bluez5 --with-systemdsystemunitdir=/lib/systemd/system --with-systemduserunitdir=/usr/lib/systemd`

方法二：不适用systemd
./configure --prefix=/usr/local/bluez5/bluez5 --disable-systemd 

