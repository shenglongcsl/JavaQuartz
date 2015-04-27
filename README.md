####参考博客
[Quartz百度百科](http://baike.baidu.com/link?url=Vm-OvO8u0Wa85inUXVuxhBnZm7P74y7pyZPo-eRGqQwnHq7epP72gl24nblhVlkOmBpjYcv71Q3P0GQ5cgutC86YD16dbsuSeL5S5F9zBp7)
[Quartz官方代码示例](http://quartz-scheduler.org/documentation/quartz-2.2.x/examples/)
[quartz官方文档](http://quartz-scheduler.org/)

如果我们想在每个星期一早上10点执行任务，节假日除外，那么这可以看成是个调度任务。提起调度，最简单的方式是java.util包提供的Timer类，其和Quartz的区别我没有详细研究过，这里重点介绍Quartz。
