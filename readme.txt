量化宝bftrader lianghuabao BF QQ交流群：571255193，
点击链接加入群【量化宝基于C++CTP架构适合PYTHON和GOLANG编写策略的量化交易中间件】：
https://jq.qq.com/?_wv=1027&k=5KvE0Iz


======

快速上手
======
1. 下载bftrader发布包
下载地址: https://github.com/lianghuabao/lianghuabao/releases
下载地址: http://pan.baidu.com/s/1nvgrNst

2. 安装golang编译器和IDE
   2.1 安装 golang1.6.2 windows x86
   2.2 安装 liteide x29 windows x86
   2.3 安装git for windows
   
3. 下载bygo源代码
   3.1 go get github.com/lianghuabao/bfgo

4. 写策略，调试策略  
   4.1 运行ctpgateway.exe,datafeed.exe
   4.2 点击ctpgateway的net/netStart,点击datafeed的net/netStart
   4.3 运行datarecorder/main.go，以连接ctpgateway datafeed
   4.4 点击ctpgateway的ctp/ctpStart
   4.5 可以看到datarecorder跑起来啦

网友策略列表
======
datarecorder/：tick收集器，演示BfTraderClient+BfRun的用法
laowangcelue/：grpc例子
wangyicelue/: 1分钟方向策略 多周期多品种收集器

（完）
