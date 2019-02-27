# Jssp(javascript server page)

------
类似于php和jsp,不同的是后端开发语言为js(不同于nodejs),这样可以使前后端开发语言统一,让开发者更快速的开发项目

#### 实现步骤：

* 选择一个合适的web框架
* 选择一个该语言可调用的js解释器
* 实现一个简单的静态文件服务器
* 对于jssp请求,首先解析模板,再用js引擎解释
* 对于jsjs请求,直接使用js引擎解释

#### Jssp规范：
* 开源项目协议使用GPL
* 默认端口为2019
* http响应头加入Server信息:jssp-[lang]-[version]
* jssp api正在制定中

#### Jssp实现:
|项目|web框架|js引擎|
|:----:|:----:|:----:|
|[jssp-golang](https://github.com/javascript-server-page/jssp-golang)|net/html|otto
|[jssp-python](https://github.com/javascript-server-page/jssp-python)|||
|[jssp-java](https://github.com/javascript-server-page/jssp-java)|vertx|nashorn|
