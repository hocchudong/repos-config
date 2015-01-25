# repos-config
Các ghi chép cấu hình repos

deb http://172.16.69.21/ubuntu1404 trusty universe
deb http://172.16.69.21/ubuntu1404 trusty main restricted
deb http://172.16.69.21/ubuntu1404 trusty-updates main restricted


:%s/192.168.1/172.16.69/g


192.168.1


echo 'Acquire::http { Proxy "http://172.16.69.21:3142"; };' >  /etc/apt/apt.conf.d/02proxy


http://172.16.69.21:3142/

deb http://172.16.69.21:3142/ubuntu/ trusty main restricted
deb-src http://172.16.69.21:3142/ubuntu/ trusty main restricted


deb http://172.16.69.21:3142/ubuntu/ trusty-updates main restricted
deb-src http://172.16.69.21:3142/ubuntu/ trusty-updates main restricted


deb http://172.16.69.21:3142/ubuntu/ trusty universe
deb-src http://172.16.69.21:3142/ubuntu/ trusty universe
deb http://172.16.69.21:3142/ubuntu/ trusty-updates universe
deb-src http://172.16.69.21:3142/ubuntu/ trusty-updates universe
