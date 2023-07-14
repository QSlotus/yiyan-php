## QiuSYan's API 

这个目录中包含的是可以直接使用 curl 命令进行访问的 API 接口。
<br>
包含 **随机一言** （`yiyan.php`）、**IP地址获取** （`ip.php`）。

## 随机一言

php简单实现随机一言。
<br>
调用方式：在命令行中输入

```bash
curl https://api.qiusyan.top/curl/yiyan.php 
```

数据文件为 `data/yiyan-data.dat` ，欢迎PR！

## 获取IP地址

php简单实现获取客户端IP。

调用方式：在命令行中输入
```bash
curl https://api.qiusyan.top/curl/ip.php
```

## 持续更新中...