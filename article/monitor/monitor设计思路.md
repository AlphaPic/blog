# Monitor #

## 设计思路 ##

#### 为了使逻辑层代码不至于耦合度过高，因此把基础服务和业务代码的实现进行区分，业务代码为springMVC构建的web程序，使用REST方式的URL进行请求。消息传输的方式是json，实现的功能还包括以下一些 ####

* #### [ 接口调用的统计 ](#接口调用的统计) ####
* #### [ 访问的过滤 ](#visit_filter) ####
* #### [ 访问的拦截 ](#visit_interceptor) ####
* #### [ 接口访问用户的统计 ](#visit_count) ####

### 接口调用的统计 ###

### <span id="visit_filter">访问的过滤</span> ###

### <span id="visit_interceptor">访问的拦截</span> ###

### <span id="visit_count">接口访问用户的统计</span> ###