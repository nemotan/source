## JDK8执行
![](media/15071886357463.jpg)


![](media/15071889533414.jpg)



	java -Xms20m -Xmx20m -Xmn10m -XX:+PrintGCDetails -XX:PretenureSizeThreshold=3145728  com.nemo.gc.JavaTest2
	
	
![](media/15071901580624.jpg)

	
	java -XX:MaxTenuringThreshold=1 -XX:+PrintGCDetails -Xms20m -Xmx20m -Xmn10m com.nemo.gc.JavaTest3
	
![](media/15071908477196.jpg)

## JDK6执行
	
	/Library/Java/JavaVirtualMachines/1.6.0.jdk/Contents/Home/bin/java -XX:+PrintGC -XX:+PrintGCDateStamps -XX:+PrintHeapAtGC -Xms20m -Xmx20m -Xmn10m -XX:+PrintGCDetails -XX:PretenureSizeThreshold=3145728  com.nemo.gc.JavaTest2
	
![](media/15071911516121.jpg)

	
	/Library/Java/JavaVirtualMachines/1.6.0.jdk/Contents/Home/bin/java -XX:+PrintGC -XX:MaxTenuringThreshold=1 -XX:+PrintGCDetails -Xms20m -Xmx20m -Xmn10m com.nemo.gc.JavaTest3

![](media/15071912846157.jpg)


## JDK7执行


	/Library/Java/JavaVirtualMachines/jdk1.7.0_79.jdk/Contents/Home/bin/java -XX:+PrintGC -XX:+PrintGCDateStamps -XX:+PrintHeapAtGC -Xms20m -Xmx20m -Xmn10m -XX:+PrintGCDetails -XX:PretenureSizeThreshold=3145728  com.nemo.gc.JavaTest2


	/Library/Java/JavaVirtualMachines/jdk1.7.0_79.jdk/Contents/Home/bin/java -XX:+PrintGC -XX:MaxTenuringThreshold=1 -XX:+PrintGCDetails -Xms20m -Xmx20m -Xmn10m com.nemo.gc.JavaTest3

![](media/15071914427099.jpg)


