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

- ubuntu 네트워크 재시작
```
$) /etc/init.d/networking restart
```

- bitcoin download url
```
- Ubuntu 접속
- FireFox 브라우저 열기
- https://bitcoin.org/en/ 접속
- menu > resource > Bitcoin Core 클릭
- Bitcoin Core release 클릭
- 0.15.2 ReadMore 클릭
- https://bitcoincore.org/bin/bitcoin-core-0.15.2/ 클릭
- ~ linux-gnu.tar.gz 파일 다운로드
```