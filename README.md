# dubbo-spring-boot-best-pratice
dubbo-spring-boot-best-pratice 是 Dubbo Spring Boot 最佳实践整合 Demo

## Roadmap

- 利用 Dubbo Spring Boot Starter 项目整合 Dubbo
- 注册中心：ZooKeeper / ETCD 两种实现
- 同一个 API ，同一套服务层（一个入口代码），实现 HTTP 协议和 Dubbo 协议服务。原因是为了异构语言调用 HTTP ，Java 工程调 Dubbo
- 请求和响应包装
- Bean 数据校验
- 错误码
- 因为同时实现两套，各自原生的 Filter 都不能用。所以得实现请求拦截，用于两种请求响应耗时，入参出参打印方便。
- 等等

## 推荐 
由于工作原因，我发表原创博客也需要编写的时间。期间很多人私我问题，没有及时得到回复，这里说声抱歉。因此，建一个星球

「泥瓦匠BYSocket」和朋友们讨论技术相关的话题，你一起来吧？

[泥瓦匠BYSocket 星球](https://t.zsxq.com/nMzjqbe "泥瓦匠BYSocket")

[泥瓦匠BYSocket 星球](https://t.zsxq.com/nMzjqbe "泥瓦匠BYSocket")

[泥瓦匠BYSocket 星球](https://t.zsxq.com/nMzjqbe "泥瓦匠BYSocket")

这个星球里面讲深入讨论 Java 、Java EE、Spring Boot 等框架技术及工作经验交流，分享一路技术走来的经验、教训。硬实力软实力、择业、职业规划等。

Web Flux 努力进行中，尽情期待。唯一文章入口：[GitChat文章地址](http://gitbook.cn/gitchat/author/58968d35f2b669527d7a7c57 "gitchat")

## Spring For All 社区
[Spring For All 社区](http://www.spring4all.com/ "spring4all")是新组建的关于 Spring 的纯技术交流社区（涵盖 Spring Boot、Spring Cloud 等内容），集诸多开源爱好者和技术大牛贡献内容和交流问题。我们不夸大、不装逼、做最纯粹的技术分享！！！

看看我们超强的群众基础，欢迎有兴趣的朋友加入QQ群分享与交流：[点击立即加入](http://www.spring4all.com/about "about")

## 作者与学习乐园
源码地址：我的[GitHub地址](https://github.com/JeffLi1993 "GitHub")<br>
作者：[泥瓦匠BYSocket](http://www.bysocket.com/ "泥瓦匠BYSocket")<br>
关注微信公众号【泥瓦匠BYSokcet】，及时得到技术文章推送<br>
![公众号](http://www.bysocket.com/wp-content/uploads/2017/01/qrcode_for_gh_cd421e7eb7d6_430.jpg)

