bannerscan
==========

C段Banner与路径扫描

Require:
Python2.6+
requests

参数：

-s 保存路径（必须参数）

-i 指定ip（指定ip后，会转化为C段进行扫描，如只需扫某个ip，使用-r参数）

-r 指定ip范围，如192.168.1.1-255

-f 指定ip列表文件

-t 指定超时时间

Update[@le4f]:
原代码上加入部分路径

more:
http://x0day.me/archives/bannerscan-py.html
