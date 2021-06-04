# 整理总结常用的异常数据算法

1、知乎微调异常数据算法资源：https://zhuanlan.zhihu.com/p/58313521

2、异常数据算法实现工具库pyod:https://github.com/yzhao062/pyod/tree/master/examples

3、IForest算法原理：https://zhuanlan.zhihu.com/p/97137153

4、服务器使用总结：

（1）配置

1、进入服务器 ：ssh shan@10.20.36.62

2、创建新的docker：nvidia-docker run -it -p 15599:8888 -p 15576:6006 -p 8033:8022 --ipc=host --name cxg -v /data/cxg:/zjw xuhp/nlp-pt:2.0 /bin/bash

3、开启ssh服务：service start ssh

4、登录自己的docker：ssh root@10.20.36.62 -p 8033

（2）pycharm连接：第一次配置：

1、选择端口号；

2、选择docker里面的解释器路径；

3、选择docker里面的本地文件的映射路径

5.VPN西部世界官网：https://xbsj6147.xyz/portal/order/node
