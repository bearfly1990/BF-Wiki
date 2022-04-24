# Maven

## 配置国内镜像

```xml
<mirror>
   <id>nexus-aliyun</id>
   <mirrorOf>*</mirrorOf>
   <name>Nexus aliyun</name>
   <url>http://maven.aliyun.com/nexus/content/groups/public</url>
</mirror> 
```

## 已经下载过的就不下载了

```
-DarchetypeCatalog=internal
```

## Skip Test

```
-DskipTests，不执行测试用例，但编译测试用例类生成相应的class文件至target/test-classes下。

-Dmaven.test.skip=true，不执行测试用例，也不编译测试用例类。
```
