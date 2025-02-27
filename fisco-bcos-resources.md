# FISCO-BCOS Resources

 ## 实践步骤
 
 1. 部署区块链，[指导手册](https://fisco-bcos-documentation.readthedocs.io/zh_CN/latest/docs/installation.html)
 2. 合约开发，[指导手册](https://segmentfault.com/a/1190000012996636)
 3. 应用开发脚手架，[项目下载和指导手册](https://github.com/FISCO-BCOS/spring-boot-starter)
 4. 体验案例，[存证](https://github.com/FISCO-BCOS/evidenceSample)
 5. 其他，体验分布式身份标识[WeIdentity](https://github.com/WeBankFinTech/WeIdentity)和体验物联网连接器[WeEvent](https://github.com/WeBankFinTech/WeEvent)
 
 ### 系统要求

| 配置     | 最低配置          | 推荐配置                                                     |
| -------- | ----------------- | ------------------------------------------------------------ |
| CPU      | 2核 1.5GHz        | 4核 2.4GHz                                                   |
| 内存     | 2G                | 4GB                                                          |
| 带宽     | 1M                | 5M                                                           |
| Java     | Java(TM) 1.8      | 推荐`Oralce JDK`；<br />如果在`CentOS`中使用`Open JDK`，请先升级到`1.9` |
| 操作系统 | 能正常运行JVM即可 | 快速安装Bash脚本在以下环境测试通过：<br />`CentOS7.2 + `、`Ubuntu16.04`、`RedHat7.4`<br />`Java`服务在以下环境测试通过：<br />`CentOS7.2`、`Ubuntu16.04`、`RedHat7.4` |

### 文档

#### 单机部署区块链
  进行开发、测试，以及演示的时，可以使用单机模拟
  - [单机部署指导手册](https://fisco-bcos-documentation.readthedocs.io/zh_CN/latest/docs/installation.html)
  - [FISCO-BCOS源码地址](https://github.com/FISCO-BCOS/FISCO-BCOS)

#### 应用开发脚手架
  开发者可以通过下载脚手架，进行配置修改可以直接进行开发。
  
  该项目是基于`Web3SDK`的`spring boot`版本的示例项目。提供`FISCO BCOS`区块链应用开发的基本框架和基本的测试案例，帮助开发者基于 `FISCO BCOS`区块链快速进行应用开发。此版本只支持`FISCO BCOS 2.0`。

  - [项目文档和地址](https://github.com/FISCO-BCOS/spring-boot-starter)

#### 区块链开发工具集

1. Web3SDK
  Web3SDK为FISCO BCOS提供Java API。利用FISCO BCOS JAVA SDK可以简单快捷的基于FISCO-BCOS进行区块链应用开发。
  - [操作文档](https://fisco-bcos-documentation.readthedocs.io/zh_CN/latest/docs/sdk/sdk.html)
  - [源码地址](https://github.com/FISCO-BCOS/web3sdk)

2. Python SDK
  Python SDK为FISCO BCOS提供Python API，使用FISCO BCOS Python SDK可以简单快捷的基于FISCO-BCOS进行区块链应用开发。
  - [项目文档和代码](https://github.com/FISCO-BCOS/python-sdk)

3. Nodejs SDK
  Node.js SDK为FISCO BCOS提供Node.js API，使用FISCO BCOS Node.js SDK可以简单快捷地基于FISCO-BCOS进行区块链应用开发。
  - [项目文档和代码](https://github.com/FISCO-BCOS/nodejs-sdk)

4. console
  console 控制台是FISCO BCOS 2.0的重要交互式客户端工具。控制台拥有丰富的命令，包括查询区块链状态、管理区块链节点、部署并调用合约等。
  - [操作文档](https://fisco-bcos-documentation.readthedocs.io/zh_CN/latest/docs/installation.html#id7)
  - [源码](https://github.com/FISCO-BCOS/console)

#### 区块链通用组件
  - 展示工具: 
  [区块链浏览器](https://github.com/FISCO-BCOS/fisco-bcos-browser)

  - 上链组件：
  [WeBASE](https://github.com/WeBankFinTech/WeBASE)


#### 应用场景案例
1. 区块链存证示例
  FISCO-BCOS区块链存证是聚焦于企业级应用服务的区块链技术平台，从电子数据的全生命周期介入，实现区块链存证、取证、维权、核证，让司法机构参与到业务过程中，实时见证，为后续的证据核实、纠纷解决、裁决送达提供了可信、可追溯、可证明的技术保障。适用场景：金融行业网络信贷、消费金融、理财等，重点解决可信和司法认可。
  - [案例说明](https://github.com/FISCO-BCOS/evidenceSample)

2. WeIdentity(DID): 
  WeIdentity是一套基于区块链的分布式多中心的技术解决方案，提供分布式实体身份标识及管理、可信数据交换协议等一系列的基础层与应用接口，可实现实体对象（人或物）数据的安全授权与交换。
  - [产品文档](https://fintech.webank.com/weidentity)
  - [源码地址](https://github.com/WeBankFinTech/WeIdentity)
  - [在线文档](https://weidentity.readthedocs.io/zh_CN/latest/)


3. WeEvent(EDA): 
  WeEvent是一套分布式事件驱动架构，实现了可信、可靠、高效的跨机构、跨平台事件通知机制。秉承分布式商业模式中对等合作、智能协同、价值共享的设计理念，致力于提升机构间合作效率，降低合作成本，同时打通应用程序、物联网、云服务和私有服务等不同平台，最终在不改变已有商业系统的开发语言、接入协议的情况下，做到跨机构、跨平台的事件通知与处理。
  - [产品文档](https://fintech.webank.com/weevent)
  - [源码地址](https://github.com/WeBankFinTech/WeEvent)
  - [在线文档](https://weeventdoc.readthedocs.io/zh_CN/latest/)


#### 更多材料

- [智能合约开发说明文档](https://fisco-bcos-documentation.readthedocs.io/zh_CN/latest/docs/manual/smart_contract.html)
- [智能合约语法介绍](https://solidity.readthedocs.io/en/v0.4.25/solidity-by-example.html)
- [SDK使用sample](https://github.com/FISCO-BCOS/evidenceSample)
- [参数说明和配置解释](https://fisco-bcos-documentation.readthedocs.io/zh_CN/latest/docs/sdk/sdk.html)
