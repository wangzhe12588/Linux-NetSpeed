# Linux-NetSpeed
```
wget -N --no-check-certificate "https://raw.githubusercontent.com/chiakge/Linux-NetSpeed/master/tcp.sh"
chmod +x tcp.sh
./tcp.sh
```
方便国内使用
不卸载内核
wget -N --no-check-certificate "https://github.000060000.xyz/tcpx.sh" && chmod +x tcpx.sh && ./tcpx.sh
或
wget -N "https://github.000060000.xyz/tcpx.sh" && chmod +x tcpx.sh && ./tcpx.sh
卸载内核
wget -N --no-check-certificate "https://github.000060000.xyz/tcp.sh" && chmod +x tcp.sh && ./tcp.sh
或
wget -N "https://github.000060000.xyz/tcp.sh" && chmod +x tcp.sh && ./tcp.sh

bbr内核更新为5.5/5.4
bbrplus内核更新为4.14.168
bbr/bbrplus 对应的centos6,7,8 debian8,9,10  ubuntu16,18,19都是对应一一编译的
不支持32位系统
锐速内核稍微更新

去掉魔改版 增加xanmod 5.5.1版本
xanmod 只添加了centos7,8 debian9,10

5.5内核支持cake队列 5.4未测试

测试版本，建议先用不卸载内核版本测试，然后再用正常版本
不卸载内核表示不会去卸载现有的内核

测试分支
https://github.com/ylx2016/Linux-NetSpeed/tree/2020.2.3
https://github.com/ylx2016/Linux-NetSpeed/releases

原作者
https://github.com/cx9208/Linux-NetSpeed
https://github.com/chiakge/Linux-NetSpeed

2020.2.3 下午
修改bbr/bbrplus判断
debian锐速内核安装需要运行两次
修复bbrplus卸载问题

2020.2.4
添加xanmod内核
改了下菜单，增加其他输出信息


2020.2.6修复 不卸载内核bbrplus开启问题

欢迎向我提交你们编译的新内核
添加备用地址

2020.2.7 添加 bbr2内核及加速 5.4.0r6内核
支持Centos7-Centos8  debian9-debian10
增加zen魔改版内核5.5.2
支持Centos7-Centos8  debian9-debian10
增加对应版本信息



双持
