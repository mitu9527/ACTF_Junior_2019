找程序，可以从启动项/任务管理器里找到一个不一样svchost.exe。

接下来可以通过查看这个程序相关的活动找到输出文件，里面含有flag。

也可以直接查看系统里所有的IO/网络/注册表等的操作情况来查找。这里推荐一下微软的工具箱SysinternalSuite里的procmon。