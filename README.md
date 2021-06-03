# 如何重新安装 macOS 系统

**方法一**：[通过 macOS 恢复功能启动](https://support.apple.com/zh-cn/HT204904)

**方法二**：[U盘安装器](https://support.apple.com/zh-cn/HT201372)

**方法三**：[通过时间机器备份恢复 macOS](https://support.apple.com/zh-cn/HT203981)

---

**抹掉（格式化）磁盘**：https://support.apple.com/zh-cn/HT208496

---

### 行列

```
defaults write com.apple.dock springboard-rows -int 9 
defaults write com.apple.dock springboard-columns -int 10
killall Dock
```

### Dock栏时间
```
defaults write com.apple.dock autohide-delay -int 0
killall Dock
```


### 允许任何来源
```
sudo spctl --master-disable
```


### 密码位数
```
pwpolicy -clearaccountpolicies
```


