1.测试时关闭watch dog，防止话机重启中断测试

2.关闭通话记录，可以减少额外的内存消耗

3.开启话机内存信息记录，话机会每分钟以syslog的形式记录当前内存

4.系统日志处填写电脑ip，开启wireshark抓包，过滤话机ip，抓syslog包

5.将抓包保存为.csv格式

6.使用procemem.sh脚本处理数据  procemem.sh xxx.csv
 
