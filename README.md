# Fabric-Traceability

[![Build Status](https://travis-ci.org/chenwbyx/Fabric-Traceability.svg?branch=master)](https://travis-ci.org/chenwbyx/Fabric-Traceability)  ![](https://img.shields.io/badge/language-go-blue.svg)


> 一个基于 [Fabric-SDK-Go](https://github.com/hyperledger/fabric-sdk-go) 的商品溯源防伪查询系统。
> 在此之前请确保已安装 [Hyperledger Fabric](https://github.com/hyperledger/fabric)（本项目基于Hyperledger Fabric v1.1)

------

### 所需环境
```
Ubuntu 16.04
Go version>=1.12 and GO111MODULE=on
docker 18.09.2
docker-compose 1.12.0
```

### 安装及配置
* Step 1：
   * 创建并进入目录 /home/ubuntu/go/src/github.com/chenwbyx
        > 此为证书文件所需路径，可自行在代码里修改
   * 拉项目```git clone https://github.com/chenwbyx/Fabric-Traceability.git ```
   * 进入文件夹：```cd Fabric-Traceability```
* Step 2：
   * 敲命令：```make```
   * 看到如下输出表示运行成功
     ![img](https://github.com/chenwbyx/Fabric-Traceability/blob/master/img/build.png)
* Step 3：
   * 访问```http://localhost:8000```
     ![img](https://github.com/chenwbyx/Fabric-Traceability/blob/master/img/index.png)


------
作者 [@chenwb](https://github.com/chenwbyx/)
2019 年 3 月 30 日