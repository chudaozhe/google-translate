# 关于Google Chrome浏览器内置翻译无法使用的解决办法
下面以`114.250.70.33`为例，实际你可以从`hosts.txt`文件中任选一个或多个

## Windows
打开 `C:\Windows\System32\drivers\etc\hosts`，在文件末尾追加
```
114.250.70.33 translate.googleapis.com
```

## macOS
```
sudo vi /etc/hosts
114.250.70.33 translate.googleapis.com
```

## 视频教程

https://www.bilibili.com/video/BV14d4y1i738/