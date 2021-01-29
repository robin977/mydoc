# 更新日志

## 2.0.4-RELEASE

2019/9/30

```xml
jar名称                  历史版本             升级后版本
fastjson                 1.2.58               1.2.60
bcprov-jdk15on                                1.57
门户跳转业务系统扩展session读不到的问题
新增一机多用户绑定情况下，动态切换用户
redis加密问题
排除redisson与dubbo的netty依赖在测试环境下无法找到子类
```

## 2.0.5-RELEASE

2019/10/18

```xml
1,用户会话中新增cas返回的serviceticket，以此扩展，方便集成到第三方系统
2,对外暴露为app**开头的url，但是必须实现验证接口，确保此接口的安全性
    配置cuckoo.web.authorized.request.api.url
3，mvc拦截器，添加静态资源放行
```



## 2.0.6-RELEASE

2020/4/7

```xml
1，提前读取prop-config下的properties文件，主要是应用于configuration注解声明类中的属性条件注解
2,shiro配置文件中放行swagger资源
3,swagger配置类添加开关(swagger.enable)属性,默认是开启，生产环境需要手动指定为swagger.enable=false
4，fastjson升级到1.2.67
```



## 2.0.7-RELEASE

2020/5/12

```xml
1，增加门户跳转过滤器
```

## 2.0.8-RELEASE

```xml
1，增加cat监控
2，修复spring国际化bug
3，去除service aop log记录
4, 添加日志记录异步化
5，添加dubbo白名单
6，添加自定义用户登录登出接口
```



## 小结

