# pragure
官网：http://pragure.cn或http://www.pragure.cn

### pragure-util
一个工作中的小工具集合
* [硬件资源工具]，使用sigar实现的CPU、内存、硬盘数据收集工具；
* [监控工具]，基于[硬件资源工具]实现的具有实时监控功能的工具；
* [文件清理工具]，清理指定文件及文件内容的工具；
* [版本处理工具]，处理不同版本保留不同代码的工具；
* [SVN差异文件工具]，根据SVN的changeLog.txt提取差异文件及提交注释；
* [Consul服务清理工具]，实时剔除consul注册中心中已下线的服务；

### pragure-data
一个数据上报组件
* 基于httpclient实现；
* 数据格式json；
* 字符编码utf-8，可配置；--规划中
* 支持条件/定时上报；--规划中
* 支持数据量大小控制、拆分上报；--规划中
