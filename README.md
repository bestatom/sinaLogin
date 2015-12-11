# sinaLogin

新浪微博自动登录脚本，使用python3，登录的是手机微博(weibo.cn)

# 运行情况

在linux下使用python3运行通过，windows下没有测试。

有时登录需要验证码，本程序的解决方案是弹出一个图片框，人工识别然后填进去。

# 使用方法

首先将`weibo = Weibo('username', 'password')`这句中的username, password换成你的用户名和密码，然后运行

```python
python3 sinaLogin.py
```
