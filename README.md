# 关于Inception  
MySQL语句的审核，在业界都已经基本被认同了，实际上也是对MySQL语句写法的统一化，标准化，而之前的人工审核，针对标准这个问题其实是很吃力的，标准越多，DBA越累，开发也越累。
那么在这个都追求自动化运维的时代，审核也必须要跟上步伐，因此Inception诞生了。而Inception可以做的工作远不止是一个自动化审核工具，同时还具备执行，生成对影响数据的回滚语句（类似闪回的功能），这样一条龙服务的工具，将会给DBA的工作带来翻天覆地的变化，DBA从此就从繁重的审核、登上去执行，出错了很难回滚（如果提前没有备份的话）的被动局面解放了出来，突然发现，做DBA原来可以这么轻松，工作可以不饱和了，那就有更多的自由时间学习、进一步向自动化运维平台的实现等更智能化的方向去发展，是具有里程碑意义的。

## 声明  
Inception是一个开源系统，每个人或者每个公司都可以自由使用，由于MySQL代码的复杂性，在审核过程中不可能入戏太深，主要是将最重要的审核完成即可，面对很多复杂的子查询、表达式等是不容易检查到的，所以有些就直接忽略了，那么大家在使用过程中，有任何疑问或者发现任何BUG，都直接提出来，我们大家一起将Inception维护得更好。

## 文档地址  
http://mysql-inception.github.io/inception-document/

