## 沉溺于学习，无法自拔 ##

### SCU_urp教务系统Python抢课 ###

此程序是纯粹无聊写出来玩一下，目的是为熟悉下Python语法和HTTP方法。

自己基本上也没有什么课需要去通过程序抢。 

*修改时也请不要太过分，间隔时间尽量大一点，以免对学校服务器造成压力。* 

也感谢白会（*白琦*）的不吝赐教。

**分享出来也是为了和大家交流学习之用，严禁任何人为其他不良目的使用此程序。**

-------

使用了requests库，需pip安装。
```
pip install requests
```

####  Features： ####
-　配置了log日志文件,方便查看信息，也不至于输出太乱 

-　解决了需选择多课程问题 

-　然后就没什么features了，如果需要实现一台机子上抢多个账号的话，需要代理到不同的ip去开进程。不太推荐多线程，容易竞争数据。 


#### 欢迎大家评论和交流 ####

##### Hint: #####
说实话，程序挺简单的，只是这个urp教务系统，需要**一步一步去模拟**，直接post数据过去的话，他的服务器端并不能反映过来，会缺少一个表单信息。
