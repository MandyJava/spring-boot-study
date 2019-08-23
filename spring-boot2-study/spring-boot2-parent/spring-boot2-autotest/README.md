# sprint-boot2-autotest

【自动化测试】技术点

功能介绍

1. 如何编写单元测试案例，具体用法有哪些
2. 单元测试场景：四种业务场景，例如如何进行接口api测试，服务层代码测试，MockMvc用法等

## 本项目教程

[如何进行单元测试编写和场景案例分析](https://blog.csdn.net/hemin1003/article/details/90214986)

## 该系列教程

[SpringBoot2系列](https://blog.csdn.net/hemin1003/column/info/40170)


## 个人说明

期望和大家”一起学习，一起成长“，共勉，O(∩_∩)O谢谢

不讲虚的，只做实干家

Talk is cheap，show me the code

<br/>


## [关于我](http://heminit.com/about/)

欢迎交流问题，可加我的个人QQ 469580884，或Q群号 751925591，一起探讨交流问题

[我的博客地址](http://blog.csdn.net/hemin1003)

[个人域名](http://heminit.com)


## 知识点 - 注解说明

@SpringBootTest注解底层实际上还是使用了Junit框架

Junit基本注解介绍
@BeforeClass 在所有测试方法前执行一次，一般在其中写上整体初始化的代码
@AfterClass 在所有测试方法后执行一次，一般在其中写上销毁和释放资源的代码
@Before 在每个测试方法前执行，一般用来初始化方法
@After 在每个测试方法后执行，在方法执行完成后要做的事情
@Test(timeout = 1000) 测试方法执行超过1000毫秒后算超时，测试将失败
@Test(expected = Exception.class) 测试方法期望得到的异常类，如果方法执行没有抛出指定的异常，则测试失败
@Test 编写一般测试用例
