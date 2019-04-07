# :beginner:FastJSON

![](http://www.runoob.com/wp-content/uploads/2018/09/fastjson.jpg)

### :trident:Fastjson简介 ###

>Fastjson是阿里巴巴的开源JSON解析库, 是一个 Java 库，可以将 Java 对象转换为 JSON 格式，当然它也可以将 JSON 字符串转换为 Java 对象。Fastjson 可以操作任何 Java 对象，即使是一些预先存在的没有源码的对象。

### :trident:Fastjson优点 ###

 * 速度快 ： fastjson相对其他JSON库的特点是快，从2011年fastjson发布1.1.x版本之后，其性能从未被其他Java实现的JSON库超越。
 
 * 使用广泛 : fastjson在阿里巴巴大规模使用，在数万台服务器上部署，fastjson在业界被广泛接受。在2012年被开源中国评选为最受欢迎的国产开源软件之一。
 
 * 测试完备 : fastjson有非常多的testcase，在1.2.11版本中，testcase超过3321个。每次发布都会进行回归测试，保证质量稳定。
 
 * 使用简单 : fastjson的API十分简洁。
 
```java
String text = JSON.toJSONString(obj); //序列化
VO vo = JSON.parseObject("{...}", VO.class); //反序列化
```

 * 功能完备 : 支持泛型，支持流处理超大文本，支持枚举，支持序列化和反序列化扩展

### :trident:Fastjson下载与安装 ###

**eclipse JavaEE平台下载及使用：**

   最新安装下载地址[点击下载](https://repo1.maven.org/maven2/com/alibaba/fastjson/1.2.53/fastjson-1.2.53.jar)
   
   下载完毕后，记住下载位置，IDEA导入jar包： [引入包流程](https://github.com/Lumnca/FastJSON/blob/master/%E5%AE%89%E8%A3%85%E4%B8%8E%E5%BC%95%E5%85%A5.md)

### :trident:Fastjson基本语法 ###

[基础快速语法](https://github.com/Lumnca/FastJSON/blob/master/%E5%9F%BA%E6%9C%AC%E8%AF%AD%E6%B3%95.md)

[实例运用](https://github.com/Lumnca/FastJSON/blob/master/%E5%AE%9E%E4%BE%8B%E5%BC%95%E7%94%A8.md)
