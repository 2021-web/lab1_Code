# lab1_Code-ssm_demo
此项目包含了一个ssm的示例。部署前要先在服务器中制作maven_tomcat镜像。同学们需要重点理解Dockerfile中的内容。

**几个注意点：**

1、先创建数据库ssm_demo，然后执行`source sys_schema.sql`文件添加表

2、修改数据库配置：在`/src/main/resources/resource/jdbc.properties`文件中修改host、用户名和密码等。