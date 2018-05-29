# mac安装

![](media/15055634667533.jpg)


# 测试

数据准备：
	
	sysbench --test=fileio --file-num=16 --file-block-size=16384 --file-total-size=1G prepare
	
![](media/15055641973272.jpg)

测试顺序写入：
	
	sysbench --test=fileio --num-threads=4 --file-total-size=1G --file-test-mode=rndrw run
	
	
![](media/15055646378252.jpg)


清理数据：
![](media/15055646683540.jpg)





