#Project Description
这是一个将database中的表转化成对象的小工具. 目的是以最小的代码量来实现所需的功能, 方便以后以module或jar的形式加入到其他project中.

#About Project

###project structure
![Project Structure](https://raw.githubusercontent.com/RoyWorld/Dolphins/master/src/main/resources/images/projectStructure.png)

###domain
常用的domain其实就是`Table`和`Column`

###how to use
在配置文件中加入database相关的配置信息, 然后直接执行以下代码, 获取`tableList`
```java
List<Table> tableList = TableFactory.getInstance().getAllTables();
```
###properties
* location: 在resource下的database.xml
* content: database相关的信息




