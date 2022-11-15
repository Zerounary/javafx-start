## JavaFX系列框架项目导航
- [JDK8 & JavaFX & SpringBoot](https://gitee.com/westinyang/javafx-boot) `加持SpringBoot，项目示例，Maven打包插件带可执行程序`
- **[JDK8 & JavaFX](https://gitee.com/westinyang/javafx-start)** `不依赖SpringBoot，项目示例，Maven打包插件带可执行程序`
- [JDK11+ & JavaFX15](https://gitee.com/westinyang/javafx-jdk11-start)  
    - `使用 jlink 打包为精简版jvm，7z压缩后约16m左右`
    - `使用 GraalVM native-image 静态编译不依赖jvm，7z压缩后13m左右`

---

![LOGO](./src/main/resources/icon/icon.png)

# javafx-start

# 介绍
JavaFx快速开始脚手架、示例应用。JavaFx+SpringBoot版本请移步至该仓库：[javafx-boot](https://gitee.com/westinyang/javafx-boot)

# 配置（app.properties）
```properties
title=JavaFx Quickly Start
icon=icon/icon.png
stage.width=640
stage.height=440
stage.resizable=false
```

# 运行效果

- 暂无截图

# 打包教程
```
mvn jfx:native
```

# 参与贡献

1.  Fork 本仓库
2.  新建 Feat_xxx 分支
3.  提交代码
4.  新建 Pull Request
