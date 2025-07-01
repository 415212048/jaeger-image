 <h1 align="center">Jaeger分布式追踪系统</h1>
  <p align="center">
    <a href="README.md"><strong>English</strong></a> | <strong>简体中文</strong>
  </p>


## 目录

- [仓库简介](#项目介绍)
- [前置条件](#前置条件)
- [镜像说明](#镜像说明)
- [获取帮助](#获取帮助)
- [如何贡献](#如何贡献)

## 项目介绍

[Jaeger](https://github.com/jaegertracing/jaeger) 是一个由 Uber 开发的分布式追踪系统，主要用于微服务架构中的监控和问题排查。Jaeger是受 Dapper 和 OpenZipkin 启发而设计的，采用 Go语言 开发，旨在解决微服务架构中服务调用关系复杂、调试困难等问题‌

**功能和特性：**

**‌分布式上下文传播‌：** Jaeger支持跨服务调用的上下文传播，确保请求的完整跟踪。

**‌分布式交易监控‌：** 对分布式交易进行监控，帮助识别问题根源。

**‌根本原因分析‌：** 通过跟踪和分析，快速定位问题发生的具体环节。

**‌服务依赖性分析‌：** 分析服务之间的依赖关系，优化服务调用流程。

**‌性能/延迟优化‌：** 通过跟踪数据，优化服务的性能和响应时间。

本项目提供的开源镜像商品 [**Jaeger分布式追踪系统**](https://marketplace.huaweicloud.com/contents/f339961a-eb5a-4c3b-87f1-306496e6368c#productid=OFFI1121282090660507648) 已预先安装1.68.0版本的Jaeger及其相关运行环境，并提供部署模板。快来参照使用指南，轻松开启“开箱即用”的高效体验吧。


> **系统要求如下：**
> - CPU: 2vCPUs 或更高
> - RAM: 4GB 或更大
> - Disk: 至少 40GB

## 前置条件
[注册华为账号并开通华为云](https://support.huaweicloud.com/usermanual-account/account_id_001.html)

## 镜像说明

| 镜像规格                                                                                                       | 特性说明 | 备注 |
|------------------------------------------------------------------------------------------------------------| --- | --- |
| [Jaeger-v1.68.0-kunpeng](https://github.com/HuaweiCloudDeveloper/jaeger-image/tree/Jaeger-v1.68.0-kunpeng) | 基于鲲鹏服务器 + Huawei Cloud EulerOS 2.0 64bit 安装部署 |  |

## 获取帮助
- 更多问题可通过 [issue](https://github.com/HuaweiCloudDeveloper/jaeger-image/issues) 或 华为云云商店指定商品的服务支持 与我们取得联系
- 其他开源镜像可看 [open-source-image-repos](https://github.com/HuaweiCloudDeveloper/open-source-image-repos)

## 如何贡献
- Fork 此存储库并提交合并请求
- 基于您的开源镜像信息同步更新 README.md