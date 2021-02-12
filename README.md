# 安装BBR Plus加速器步骤【TCP加速 一键安装管理脚本 V1.3.2】
#### 1【获取root权限】
sudo -i
#### 2【安装wget服务】
yum -y install wget
#### 3【安装SSR加速器】
wget -N --no-check-certificate "https://github.com/hbiao0827/BBR-Plus/blob/main/TCP.sh" && chmod +x tcp.sh && ./tcp.sh
#### 4【先输入2，安装 BBRplus版内核，安装完之后重启系统，重启后】
#### 5【获取root权限】
sudo -i
#### 6【再运行脚本】
wget -N --no-check-certificate "https://github.com/hbiao0827/BBR-Plus/blob/main/TCP.sh" && chmod +x tcp.sh && ./tcp.sh
#### 7【输入7，使用BBRplus版加速】
#### 8【再次运行脚本，查看是否安装成功，后退出。】
wget -N --no-check-certificate "https://github.com/hbiao0827/BBR-Plus/blob/main/TCP.sh" && chmod +x tcp.sh && ./tcp.sh
