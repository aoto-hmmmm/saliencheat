# saliencheat
------
简化STEAM18年夏促游戏挂机脚本操作的小脚本
挂机脚本来源于[此](https://github.com/SteamDatabase/SalienCheat)
[0.2.0] 增加了检测脚本更新机制,能自动更新脚本

## 环境需求
> * docker
> * linux

## 使用之前
拉取脚本文件并进入
```bash
git clone https://github.com/aoto-hmmmm/saliencheat.git
cd saliencheat
```
将saliencheat文件中 [you steam token] 改为自己steam的token值
> 浏览器上登录STEAM账户并访问 https://steamcommunity.com/saliengame/gettoken 即可获取token值

## 使用脚本
```bash
chomd 755 saliencheat checkUpdate
./saliencheat update
```

## 脚本相关命令
更新并启动
```bash
./saliencheat update
```
启动
```bash
./saliencheat start
```
停止运行
```bash
./saliencheat stop
```
查看游戏运行日志(如果有更新该日志将自动删除并重建)
```bash
./saliencheat log
```
