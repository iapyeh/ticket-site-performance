# ticket-site-performance
測量自己所在的ISP連線到售票網站的網速

## 程式
主要有2個。
- domaindigger.spy 抓取網站(tixcraft.com)對應的ip address
- checkspeed.spy 測試網站(tixcraft.com)的下載速度

## 安裝
- 需要是Linux/MacOS系統, 且安裝了 "dig" 與 "curl"兩個程式。
- 需要 Python3.10 或以上
- pip install sshscript

## 抓取網站(tixcraft.com)對應的ip, 在console執行
$ sshscript domaindigger.spy

## 測試網站(tixcraft.com)的下載速度, 在console執行
$ sshscript checkspeed.spy
說明：沒有執行domaindigger.spy直接執行這個程式也可以。測試的是在我環境中所抓到的ip。

