- 用 `IDEA` 打开该项目

<br>

- 配置 `IDEA` 的启动类， 配置 `MainClass` ， 并配置 `VM` 参数

```java
# 该路径为 tomcat 的路径
-Dcatalina.home=D:/source/tomcat/home
-Dcatalina.base=D:/source/tomcat/home
-Djava.util.logging.manager=org.apache.juli.ClassLoaderLogManager
-Djava.util.logging.config.file=D:/source/tomcat/home/conf/logging.properties
```

![](http://note.youdao.com/yws/public/resource/7971bc9a04256c64b7d559dd08e94a8e/xmlnote/4D3212684B444B0685B50EA77A526ACF/105346)

<br>

- 删除 `test` 模块


<br>


- 启动主方法，运行 `Tomcat`，访问 `Tomcat`

![](https://note.youdao.com/yws/public/resource/7971bc9a04256c64b7d559dd08e94a8e/xmlnote/38F218595EDC446E835C9C87967A8DE7/69022)