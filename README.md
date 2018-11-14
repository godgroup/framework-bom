## bom单使用方式

在pom文件中增加如下配置
```
  <dependencyManagement>
        <dependencies>
            <dependency>
                <groupId>org.godgroup.framework</groupId>
                <artifactId>framework-bom</artifactId>
                <version>1.0.0-SNAPSHOT</version>
                <scope>import</scope>
                <type>pom</type>
            </dependency>
        </dependencies>
    </dependencyManagement>
```

本 bom 单已经定义好常用依赖的版本，使用方不需要再自行定义依赖的版本；
