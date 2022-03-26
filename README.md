SMBMS

## 源码下载



[smbms-云盘下载](https://www.aliyundrive.com/s/XnCLHD6Fe5C)



## 一,项目搭建-前期准备

### 1.  创建mavenweb项目

### 2. 添加Tomcat

### 3. 测试localhost访问

### 4. 导入jar包

   1. ```
      servlet-api  
      jsp-api    
      mysql-connector-java
      jstl-api
      standard
      ```
2.maven项目导入pom.xml
```
	<!--   servlet依赖  -->
    <dependency>
      <groupId>javax.servlet</groupId>
      <artifactId>servlet-api</artifactId>
      <version>2.5</version>
    </dependency>
    <!--   JSP依赖  -->
    <dependency>
      <groupId>javax.servlet.jsp</groupId>
      <artifactId>jsp-api</artifactId>
      <version>2.2</version>
    </dependency>
    <!--   jdbc依赖  -->
    <dependency>
      <groupId>mysql</groupId>
      <artifactId>mysql-connector-java</artifactId>
      <version>5.1.47</version>
    </dependency>
    <!--   jstl标签依赖  -->
    <dependency>
      <groupId>javax.servlet.jsp.jstl</groupId>
      <artifactId>jstl-api</artifactId>
      <version>1.2</version>
    </dependency>
    <dependency>
      <groupId>taglibs</groupId>
      <artifactId>standard</artifactId>
      <version>1.1.2</version>
    </dependency>
     <!--   单元测试依赖  -->
    <dependency>
      <groupId>junit</groupId>
      <artifactId>junit</artifactId>
      <version>4.10</version>
    </dependency>

    <!--    阿里fastjson依赖-->
    <!-- https://mvnrepository.com/artifact/com.alibaba/fastjson -->
    <dependency>
      <groupId>com.alibaba</groupId>
      <artifactId>fastjson</artifactId>
      <version>1.2.62</version>
    </dependency>
```
### 5. 创建项目结构

   <img src="https://gitee.com/xbd_zc/images/raw/master/img/image-20220310201631161.png" alt="image-20220310201631161" style="zoom:80%;" />

### 6. 编写实体类

      1. ORM映射: 表-;类映射

### 7. 编写基础公共类
