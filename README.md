# mechine-learning-

linux (ubuntu) + centos-7.iso

open linux create name: centos & memory size 8096 $$ 20GB

setting add 4 CPU & 




#cmd

```sh
pip install matplotlib
```

```sh
pip install pandas
```

```sh
systemctl disable firewalld
```

關閉防火牆

```sh
yum install -y centos-release-openstack-queens
```

```sh
yum update -y
```

```sh
yum install -y openstack-packstack
```

```sh
yum install -y vim
```

```sh
packstack --gen-answer-file answer.txt
```

出現Packstack changed given value  to required value /root/.ssh/id_rsa.pub正常

```sh
vim answer.txt
```

進到頁面後，開始編輯五種，首先利用'?名稱'，然後'.i'打字後，按esc跳出

1?DEFAULT_PASSWORD 打上 自己的密碼

2?NTP_SERVERS 打上 clock.stdtime.gov.tw
