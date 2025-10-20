## `【大灰狼独家优化】（IPV6大全版  6.6 内核【带DOCKER】`
#### 🚩 源码拉取`coolsnowwolf` `Lienol` `immortalwrt` `x-wrt` `openwrt` 自行选择编译
- 大灰狼编译库`X86-R2C-R2S-R4S-R5S-N1-小米MI`等多系列全部适配OTA自动升级
- 默认IP地址：`192.168.2.1`
- 账户：`root`   密码：`空`

- 自行云编译固件姿势
- ssh-actions改为ssh就可以启动插件选择
- 看到ssh链接会有一个web的链接，打开就是命令行，根据下面命令进入
- 开始 ctrl+c 
- 进ssh选择插件 
``` bash
cd openwrt && make menuconfig
```
- 结束ctrl+d
- REPO_TOKEN密匙制作教程：https://git.io/jm.md
- 云编译需要 [在此](https://github.com/settings/tokens) 创建个```token```,勾选：```repo```, ```workflow```，保存所得的key
- 然后在此仓库```Settings```->```Secrets```中添加个名字为```REPO_TOKEN```的Secret,填入token获得的key

- TG通知```Settings```->```Secrets```中添加个名字为```TELEGRAM_BOT_TOKEN```和```TELEGRAM_CHAT_ID```

## 自动更新固件
![img.png](img/img.png)
![1.png](img/1.png)
![2.png](img/2.png)
![img2.png](img/img2.png)
![img3.png](img/img3.png)

[![Stargazers over time](https://starchart.cc/shidahuilang/openwrt.svg)](https://starchart.cc/shidahuilang/openwrt)
 ### 鸣谢！
 感谢以下各位大佬（排名无分先后）<br />
[`coolsnowwolf`]
[`danshui`]
[`Lienol`]
[`immortalwrt`]
[`P3TERX`]
[`Hyy2001X`]


