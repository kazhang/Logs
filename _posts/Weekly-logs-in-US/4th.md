#The 4th week in US
##Scheduler
上周说要做个Graph Database，周一我们已经有了初步的设计模型，周二我们开组内会议的时候邀请了Mike，把设计好的数据库图给他看，Mike说挺好的，但是要有个Demo更好了。确实，我们组有8个人，8个人干两周，就弄出个数据库的图实在说不过去。想想也是，那做个什么Demo呢？组里有人说，我们做数据库不就是为调度器分配资源时提供数据么，做个简单地调度器吧。

说干就干，我们组分成了三拨，一拨人研究算法，一拨人写UI，一拨人构建数据库。我和鹏飞负责数据库构建，就是从OpenStack拉数据，通过一个叫Neograhpy得Ruby gem写入到Neo4j中。在周五的时候已经完成了脚本代码，可惜我们目前只把OpenStack部署在一台Server上，节点很少，出来的图也很简单，下一步我们将申请大集群的权限，构建出更复杂的图。其他两条战线也陆续完成了工作，期待周一合装备。


