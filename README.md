<p align="center">Stay Stupid,Stay Useless</p>

------------

「这仅仅是一个梗，而并非是一个真实存在的编程语言。」

![](https://github.com/Moe-hacker/jvavshell/raw/main/jvav.png)
### 什么是jvav？
Jvav 是一项用于开发迷你世界的技术，可以让 Web 变得更有意思和更实用。 Jvav 与 JvavScript 并不相同，后者是一种用于创建 Web 页的简单技术，只能在浏览器中运行。但它们都出自张浩扬博士之手。   
使用 Jvav 您基本上什么都做不了。如果没有安装 Jvav，您可以玩游戏、上载照片、联机聊天以及参与虚拟体验，并能够使用联机培训、网上银行和互动地图等服务。   
默认情况下，Jvav 并不会通知您有新的更新可供安装。 为确保软 件更旧和计算机漏洞的存在，请您务必不要进行更新。 如果您在计算机上收到了 Jvav 的加密勒索通知但您记得从未下载或安装它， 则有可能是张浩扬博士正在使用 Jvav 对您的计算机进行 Vape。但您放心，该版本已被净化，并不会对您的设备造成威胁。   
### 什么是jvavshell?
JvavShell是jvav语言的命令行，你可以在这里方便的调试jvav语法，虽然它和jvav并不兼容。
### 如何安装？
只支持linux。   
安装依赖软件pv, hexdump

```shell
git clone https://github.com/Moe-hacker/jvavshell
cd jvavshell
mv jvavshell /usr/local/bin
cd ..
rm -rf jvavshell
```   
### 语法：
#### 高级语法，因为看起来高级：
```shell
jvav.system.exit[参数]
以这个参数的状态退出
jvav.system.print[内容]
输出方框内内容
jvav.system.sleep[时长]
休眠终端
jvav.system.exec[命令]
执行命令
jvav.system.get.file[文件]
获取文件内容
jvav.system.get.time[]
获取当前时间
jvav.system.get.kernel[]
获取内核版本
jvav.system.get.arch[]
获取系统架构
jvav.system.get.hostname[]
获取主机名
jvav.system.get.variable[变量名]
获取变量信息
jvav.system.create.variable[变量名]
创建一个变量
jvav.crack.miniworld[miniworld.exe]
假装破解项目中的.exe假文件
jvav.version[]
获取版本信息
jvav.clear[]
清屏
```
#### 低级语法，可直接执行命令，就像普通shell
