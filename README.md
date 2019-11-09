# edu

## 사전준비
- ubuntu image 다운로드 <br>
https://drive.google.com/open?id=1sAN1Feo2PWu2Jv_elu7KcYQ0HlgMUdCU

- ubuntu network 파일 수정
```
$) su //비밀번호 testpw
$) cd /etc/network/
$) vi interfaces
$) 수정 내용
auto lo
iface lo inet loopback

auto enp0s8
iface enp0s8 inet static
address 192.168.57.10
netmask 255.255.255.0
```