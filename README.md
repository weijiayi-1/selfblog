# SelfBlog

SelfBlog 是一个基于 Spring Boot 的个人博客系统，支持用户注册、登录、博客发布、点赞等功能。

## 主要功能

- 用户注册与登录（支持 Token 验证）
- 博客发布、编辑与删除
- 博客点赞功能
- 个人信息管理
- 管理员初始化脚本

## 项目结构

```
src/
  main/
    java/
      com.example.selfblog/
        config/         # 配置类
        controller/     # 控制器
        entity/         # 实体类
        pojo/           # 数据传输对象
        repository/     # 数据访问层
        service/        # 业务逻辑层
        util/           # 工具类
    resources/
      static/           # 静态资源
      templates/        # 前端模板
      application.properties
      application.yaml
      initsql/          # 初始化SQL
  test/
    java/
      com.example.selfblog/
        SelfblogApplicationTests.java
```

## 快速开始

1. 克隆项目到本地  
   `git clone https://github.com/weijiayi-1/selfblog.git`

2. 导入到 IDEA 或其他 Java IDE

3. 配置数据库连接（修改 `application.properties` 或 `application.yaml`）

4. 初始化数据库（可选，执行 `initsql/creteAdmin.sql`）

5. 访问首页  
   `http://localhost:8080`

## 相关技术

- Spring Boot
- Spring Security
- Thymeleaf
- JPA (Hibernate)
- MySQL

## 贡献

欢迎提交 issue 和 pull request！ 