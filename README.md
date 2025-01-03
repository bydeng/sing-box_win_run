# window11运行singbox

## 安装singbox
1、singbox下载地址
https://github.com/SagerNet/sing-box/releases

2、下载后解压到桌面，将解压文件夹修改成“sing-box”

3、将config.json放到sing-box文件夹

## 运行singbox
### 前台运行
- 管理员运行powershell输入以下命令
```
.\sing-box.exe run -c .\config.json
```
### 后台运行
- 新建文本输入以下命令
```
:: 切换到 PowerShell 并执行命令
PowerShell -Command "Start-Process -FilePath 'C:\Users\xxx\Desktop\sing-box\sing-box.exe' -ArgumentList 'run', '-c', 'C:\Users\xxx\Desktop\sing-box\config.json' -Verb RunAs -WindowStyle Hidden"
```
下面两个按实际情况修改路径
```
'C:\Users\xxx\Desktop\sing-box\sing-box.exe'
'C:\Users\xxx\Desktop\sing-box\config.json'
```
保存后修改后缀名成xxx.bat
第一次运行会弹出提示
