# JRQ-Order-Collector
金融圈 订单 采集系统
#Python3.5 项目

#Main.py 为主执行文件
	UserList 可配置 打算监听的牛人
#MailManager.py  为邮件服务器配置
	receivers 可以配置收信邮箱
	DEBUG_MODE 初次执行请设置成True (否则会短时间内收到很多信)
	

#规划
	目前实现的功能:
		1.订单采集
		2.订单解析
		3.新订单与订单状态发生改变进行邮件通知
	后续计划:
		1.止盈止损发生改变时发送邮件
		2.独立出配置文件,保密发信帐户密码
		3.Sqlite 改成 MySql
		4.做一个网页,可以单独跟踪统计一些订单
		5.MT4 交易端 对服务器 单项订阅
