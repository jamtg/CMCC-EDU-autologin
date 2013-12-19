CMCC-EDU-autologin is a script for solving the captive portal of CMCC WLAN(only for SSID:CMCC-EDU).
It supports logging in,showing remaining time(optionally).
It works in a university located in Jinhua,Zhejiang Province,China.

这是一个用来登录CMCC WLAN（仅支持SSID为“CMCC-EDU”的接入点）的脚本。
它支持登录和剩余时间提醒。
它在浙江省金华市某大学测试通过（其实也是在这里写的）。

**(Require Python3)/(只能工作在Python3下)**
Usage/使用方法
----
Edit config.ini first.Then run t.py .
Use pythonw.exe to run t.py if GUI mode enabled(Windows only).

Cookie will be saved when successfully logged in the first time.When failed logging in by cookie,
it will fallback to no-cookie login method.


先编辑config.ini文件，然后运行t.py。如果启用了GUI模式，（Windows限定）用pythonw来运行t.py。
第一次成功登陆时会保存Cookie。当用Cookie登录失败时会使用无Cookie的登录方式。


----
Using the Scheduled Task of Windows,it can run automatically when connected to CMCC-EDU:[HOWTO](http://superuser.com/questions/262799/how-to-launch-a-command-on-network-connection-disconnection).


借助Windows的计划任务功能，可以在成功连接至CMCC-EDU后自动运行来登录。