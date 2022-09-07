
<p align="center"><a href="https://vuejs.org" target="_blank" rel="noopener noreferrer"><img width="400" src="https://raw.githubusercontent.com/FxPool/FxMinerProxyV3/main/image/logo.png" alt="Vue logo"></a></p>
<p align="center">
  <a>
    <img src="https://img.shields.io/badge/Release-8.0.3-orgin.svg" alt="travis">
  </a>
  <a>
    <img src="https://img.shields.io/badge/Last_Update-2022_09_05-orgin.svg" alt="travis">
  </a>
  <a>
    <img src="https://img.shields.io/badge/Language-GoLang-green.svg" alt="travis">
  </a>
  <a>
    <img src="https://img.shields.io/badge/License-Apache-green.svg" alt="travis">
  </a>
</p>
<p align="center">
  <a href="https://github.com/FxPool/FxMinerProxyV3/blob/main/readmes/en.md">English(en-us)</a> •
  <a href="https://console-docs.apipost.cn/preview/280432b691e741ca/411c6c29b9f5d365">文档</a> •
  <a href="https://t.me/+OVih6MkOAFsxYTMx">Telegram 讨论群组</a> •
</p>

## 简介

基于Golang高性能Pow挖矿代理中转服务器软件.FXMinerProxy的升级版本，中文名称傅里叶。全新UI界面，后台SSH控制台，手机APP，程序不重启，1核1G服务器(不是轻量)轻松3000台无压力

## 支持币种

ETH/ETC/BTC/LTC/RVN/CFX/TON/BEAM/ERG/BTG (需要添加新币中请联系我们，如果是芯片机器恰好我们没有，你可以连接我们这边服务器通常一天就能加上，这一天的损失我们承担)

## 手机APP支持 安卓 IOS （开发中9月15号之前出来）

  ![](https://raw.githubusercontent.com/FxPool/FxMinerProxyV3/main/image/phone1.jpg)

## WEB后台首页

  ![](https://raw.githubusercontent.com/FxPool/FxMinerProxyV3/main/image/home.png)
  
## SSH服务器群控后台

  ![](https://raw.githubusercontent.com/FxPool/FxMinerProxyV3/main/image/ssh_zh.jpg)
  
  
## :sparkles: 特性

* :cloud: 支持ETC,ETH,BTC,LTC,RVN,BEAM,ERG,CFX等多币抽水,内置独家开发的加密混淆客户端 一键配置自动生成执行程序win和os都支持,API 开放，独家任何币种双挖支持
* :zap: 高性能百万并发CPU占用极低，30万连接cpu占用10%
* 💻 自定义作者抽水模式(范围0.1-0.2%)，PID抽水算法稳定算力曲线减少切换损耗，实时统计抽水转换率
* 📚 原创抽水算法针对e池优化e池抽水效果最好，无矿机离线bug曲线完美，比其他软件高出几个点
* 💾 安全稳定，原创aes混淆加密，模拟物联网流量安全稳定，后台一键配置自动生成window和linux版本，传统TLS/SSL TCP也支持，防御CC攻击
* :gear: 前置代理模式，内部配置提高访问速度，延迟快速响应支持，让用户的显示的延迟是你当前代理服务器的延迟
* :outbox_tray: 芯片矿机实时计算算力，解决芯片级无法显示算力的问题
* :card_file_box: 配置热修改，拒绝传统配置后需重启修改配置文件等繁琐步骤，支持一键导入导出配置文件
* :art: 精美UI，支持历史记录曲线管理详细到单台矿机支持
* :eye_speech_bubble: 多人社区交流支持，不懂的问题都有人解答，QQ群:809118996，Telegram讨论组:https://t.me/+OVih6MkOAFsxYTMx
* :gear: 实时系统错误日志显示，让你知道任何时候服务器工作状态
* :family_woman_girl_boy: 多系统支持，windows，linux一键安装运行
* 💻 linux SSH2 群控模式 软件自带服务器远程登录一键管理你的服务器

## :hammer_and_wrench: 部署
### linux一键管理脚本(需root权限)
* 如果没有curl命令请输入 apt-get install curl 安装
```shell
  bash <(curl -s -L https://raw.githubusercontent.com/FxPool/FxMinerProxyV3/main/install_zh.sh)
```
* 指定版本下载
```shell
   bash <(curl -s -L https://raw.githubusercontent.com/FxPool/FxMinerProxyV3/main/oldversion/install_zh.sh) 版本号(如8.0.2.1)
```
### windows直接下载解压运行run.exe
* 运行run.exe（可保证程序永不死机）
```shell
  https://raw.githubusercontent.com/FxPool/FxMinerProxyV3/main/fxminerproxyv3windows.zip
```  
## 芯片机器问题
程序的端口会自动判断是显卡机器还是芯片机器所以无效单独配置
A11矿机抽水最好是抽到相同的矿池，不同的矿池可能会出现无效，主要还是要看固件是否支持set_exnaoce方法(动态修改随机数)，保守做法抽到同一个矿池
奶牛、茉莉、亚米等矿机可抽任意矿池


## :alembic: 开发抽水  
* 开启抽水固定0.27%  
* 个人试用不开启抽水，开发者为0，如不相信可以用纯转发软件对比，或软件抓包测试
* 大算力用户请联系我们可激活软件享受更低的开发者抽水

##  加入电报群交流学习讨论 
![](https://raw.githubusercontent.com/FxPool/FxMinerProxyV3/main/image/tg.jpg)
