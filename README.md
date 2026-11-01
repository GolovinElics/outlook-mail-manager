# Outlook Mail Manager（Java）

基于 Microsoft Graph 的 Outlook 邮件、日历和联系人管理 Java 示例。原仓库名为 `java-tutorial`，整理后使用 `outlook-mail-manager`，方便按实际用途查找。

这是历史教程示例代码。原项目说明及 Microsoft 版权声明见 [原始 README](./java-tutorial/README.md)。

## 代码位置

- `java-tutorial/`：Maven Web 应用。
- `java-tutorial/src/main/java/com/outlook/dev/`：认证、邮件、联系人与日历控制器和服务。
- `java-tutorial/src/main/resources/auth.properties`：应用认证配置模板。
- `java-tutorial/src/main/webapp/`：JSP 页面及 Spring MVC 配置。

## 原示例运行方式

项目使用 Java 8、Maven、Spring MVC 和 Jetty。按原始 README 配置本地应用注册信息后，在源码目录运行：

```bash
cd java-tutorial
mvn package
mvn jetty:run
```

原示例访问地址为 `http://localhost:8080`。本次整理仅核对源码与文档结构，没有重新验证 Microsoft 登录流程；依赖版本和原教程中的注册入口较旧，重新部署前需要核对当前配置要求。

真实应用密钥和用户令牌应保存在本地配置中，公开仓库只保留占位值。
