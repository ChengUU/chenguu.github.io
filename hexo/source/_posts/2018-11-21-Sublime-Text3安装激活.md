---
title: Sublime-Text3安装激活
date: 2018-11-21 18:55:36
categories:
- 开发工具
tags:
- 软件安装激活
---
Sublime Text 是一个代码编辑器（Sublime Text 2是收费软件，但可以无限期试用），也是HTML和散文先进的文本编辑器。下面将介绍如何下载Sublime- Text3安装包并激活详细步骤,**请支持正版软件**.

1. Sublime Text3可以通过下载安装包直接安装,由于最新版本获取免费注册码困难,所以我们退而求其次,安装旧版本以满足我们的需要,安装下载地址格式: https://download.sublimetext.com/sublime-text_build-版本号_amd64.deb, 例如:[Sublime-text_build-3143](https://download.sublimetext.com/sublime-text_build-3143_amd64.deb)

2. 通过以上方式下载安装包后双击即可安装,博主安装的版本为Sublime-text_build-3143
通过百度找到以下可使用的注册码:
```
    —— BEGIN LICENSE ——  
    TwitterInc  
    200 User License  
    EA7E-890007  
    1D77F72E 390CDD93 4DCBA022 FAF60790  
    61AA12C0 A37081C5 D0316412 4584D136  
    94D7F7D4 95BC8C1C 527DA828 560BB037  
    D1EDDD8C AE7B379F 50C9D69D B35179EF  
    2FE898C4 8E4277A8 555CE714 E1FB0E43  
    D5D52613 C3D12E98 BC49967F 7652EED2  
    9D2D2E61 67610860 6D338B72 5CF95C69  
    E36B85CC 84991F19 7575D828 470A92AB  
    —— END LICENSE ——  
```

3. 通过该注册码激活后可能会出现,注册码失效的情况,原因是该软件在线服务器会在线验证该激活码的有效性,所以可以通过阻止在线验证信息的传输间接实现软件破解.修改主机hosts文件,添加如下域名解析信息:
```
# Sublime Text3
127.0.0.1 license.sublimehq.com
127.0.0.1 45.55.255.55
127.0.0.1 45.55.41.223
```
![详细配置](/images/20180505164219.png)

4. 修改软件更新信息'Preference->settings-User'
```
{
	"font_size": 12,
	"ignored_packages":
	[
		"Vintage"
	],
	"update_check": false,
}
```
![详细配置](/images/20180505164043.png)

**不要忘记每行结尾的逗号**
