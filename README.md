# maven
自己的maven仓库，可以直接引用
#### 添加仓库地址
```xml
 <repositories>
    <repository>
        <id>maybe-mvn-repo</id>
        <url>https://raw.githubusercontent.com/QuietSugar/xu-repository/master/maven</url>
    </repository>
</repositories>
```
#### 引用
```xml
<dependency>
    <groupId>com.maybe.plugin</groupId>
    <artifactId>mybatis</artifactId>
    <version>1.0-SNAPSHOT</version>
</dependency>
```
