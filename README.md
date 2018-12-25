# maven-repo
A personal Maven repository.

**以下内容仅供个人学习交流使用**

# 版本库使用

```xml
<repositories>
    <repository>
        <id>xavier-maven-repo</id>
        <url>https://raw.githubusercontent.com/NewGr8Player/maven-repo/master/</url>
    </repository>
</repositories>
```

# spring-boot-starter-canal:0.0.1-REALEASE
**源项目地址:[spring-boot-starter-canal](https://github.com/chenqian56131/spring-boot-starter-canal)**
> 个人学习使用，仅更改包名，修改pom文件，方便打包，保留原有所有注释与说明
# spring-boot-starter-canal:0.0.2-REALEASE
**在原版本基础上进行较大规模调整，改变除基础方法外的部分逻辑，添加表名，便于响应动态配置。**

```xml
<dependency>
	<groupId>com.xavier</groupId>
	<artifactId>starter-canal</artifactId>
	<version>${version}</version>
</dependency>
```

# spring-boot-starter-fastdfs:0.0.1-SNAPSHOT
**能够启动项目，对fastdfs进行简单操作。**
# spring-boot-starter-fastdfs:0.0.1-RELEASE
**修改部分bug，解决并发问题。**

```xml
<dependency>
    <groupId>com.xavier</groupId>
    <artifactId>spring-boot-starter-fastdfs</artifactId>
    <version>${version}</version>
</dependency>
```