# 组件接入指引

蓝鲸监控目前覆盖 （Apache 、 Nginx 、Tomcat 、MySQL） 等开源组件、中间件服务的性能指标监控，具体配置请参照以下接入指引。

 ![-w2020](../../assets/component_acesess_tips.png)
 <center>图 1. 接入指引</center>

- 组件名称：
- 采集类型：说明该组件由什么采集器上报，采集器说明参考 [文档](5.1/蓝鲸监控/二次开发/Plugins.md)
- 支持系统：支持该组件采集的系统类型
- 已验证版本：已验证的组件版本，若组件版本不一致，可能会导致采集异常或部分数据上报异常
- 组件接入指引：蓝鲸监控根据每个组件不同的数据和采集方式提供的接入说明

如果你使用的组件不在此列，或者是组件提供的接入提示说明不清晰/按说明无法成功接入，请联系蓝鲸助手 QQ: [800802001](http://wpa.b.qq.com/cgi/wpa.php?ln=1&key=XzgwMDgwMjAwMV80NDMwOTZfODAwODAyMDAxXzJf) 反馈给蓝鲸监控团队。
