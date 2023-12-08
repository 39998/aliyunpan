# Ubuntu阿里云盘一键安装脚本

如何获取RefreshToken
浏览器登录阿里云盘网页版
在Microsoft浏览器按F12点击控制台，输入以下代码
```
JSON.parse(localStorage.getItem("token")).refresh_token
```
登录
```
aliyunpan > login -RefreshToken=32994cd2c43...4d505fa79
```
以下直接复制
```
login -RefreshToken=
```

源代码地址https://github.com/tickstep/aliyunpan

