# 2019ロボットシステム学課題１
# 概要
　入力した数字の秒数(3まで)点灯するデバイスドライバ．
# 手法
## インストール手順
```
$ git clone https://github.com/KosekiTakashi/myled.git
$ cd myled
$ make
$ sudo insmod myled.ko
$ sudo chmod 666 /dev/myled0
```
## 実行
```
$ echo 1 > /dev/myled0
$ echo 2 > /dev/myled0
$ echo 3 > /dev/myled0
```
## YouTube  

## LICENSE  
This repository is licensed under the GPLv3 license, see COPYING.
