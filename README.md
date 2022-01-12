# seata实现2pc的demo
## 目录介绍

    |-- dtx  // 代码
    |   |-- discover-server  // 微服务注册
    |   |-- dtx-seata-demo   // seata-demo
    |   |   |-- dtx-seata-demo-bank1  // seata-demo-bank1
    |   |   |-- dtx-seata-demo-bank2  // seata-demo-bank2
    |   |   |-- dtx-seata-demo.iml
    |   |   |-- pom.xml
    |   |-- logs
    |   `-- pom.xml
    `-- seata-server-0.7.1 // seata服务端
        |-- bin
        |-- conf
        |-- lib

## demo介绍

* 开发语言：java.
* 数据库： mysql

## 运行
* 创建bank1,bank2两个库，执行对应的sql.
* 启动seata服务端

## 疑问交流
如果你是一个javaer，可能很好理解代码，且能很好的运行起来。
运行demo遇到问题可与我交流。
* 提issue
* 微信联系

![微信截图_20220112152412](https://user-images.githubusercontent.com/12689759/149082380-a8c60615-1d2b-4472-b6c9-315809be5d99.png)
