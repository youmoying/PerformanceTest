# 取样器 Sampler 

* 模拟用户执行实际的交互工作，取样器请求生成一个或多个取样结果，在监听器中可以查看
* 取样器支持很多协议，支持FTP，HTTP等，https://jmeter.apache.org/usermanual/component_reference.html
* http取样器： 支持http和https请求发送到web服务器，接受返回结果， 如果多个请求发送同一个服务器，可以使用http请求默认配置元件
* JDBC取样器：将JDBC请求发送到数据库，进行JDBC数据库测试，使用JDBC Requst之前需要设置JDBC连接配置元件

## 取样器的实例

* 请求http request  百度 apache 网站， 断言，查看结果树


# 逻辑控制器

* 逻辑控制器确定取样器的处理顺序和逻辑控制，对元件的执行逻辑进行控制， 如果执行一次控制器，循环控制， 交替执行控制器来满足的实际运行用的复杂需求
* 

