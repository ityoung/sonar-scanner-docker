## 项目描述

一键构建SonarScanner基础镜像，用该镜像对Python项目进行静态代码分析。

## 使用步骤

1. 修改`sonar-scanner.properties`中的`sonar.host.url`为你的docker宿主机 **IP:端口**
2. 构建镜像：
    ```
    docker build -t sonar-scanner .
    ```

## 作者

联系： ityoung@foxmail.com

简书： [严北](https://www.jianshu.com/u/164741981042)
