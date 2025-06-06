<h1 align="center">Jaeger Distributed Tracing System</h1>
<p align="center">
    <strong>English</strong> | <a href="README_ZH.md">中文简体</a>
</p>

## Table of Contents

- [Repository Introduction](#repository-introduction)
- [Prerequisites](#prerequisites)
- [Image Description](#image-description)
- [Get Help](#get-help)
- [How to Contribute](#how-to-contribute)

## Repository Introduction

[Jaeger](https://github.com/jaegertracing/jaeger) is a distributed tracing system developed by Uber, mainly used for monitoring and troubleshooting in microservice architectures. Inspired by Dapper and OpenZipkin, Jaeger is developed in Go language, aiming to solve problems such as complex service call relationships and difficult debugging in microservice architectures.

**Functions and Features:**

**Distributed Context Propagation:** Jaeger supports context propagation across service calls to ensure complete tracking of requests.

**Distributed Transaction Monitoring:** Monitor distributed transactions to help identify the root causes of problems.

**Root Cause Analysis:** Quickly locate the specific环节 where problems occur through tracking and analysis.

**Service Dependency Analysis:** Analyze the dependencies between services to optimize the service call process.

**Performance/Latency Optimization:** Optimize service performance and response time through tracking data.

The open-source image product [**Jaeger Distributed Tracing System**](https://marketplace.huaweicloud.com/hidden/contents/f339961a-eb5a-4c3b-87f1-306496e6368c#productid=OFFI1121282090660507648) provided by this project has Jaeger version 1.68.0 and its related operating environment pre-installed, and also provides deployment templates. Refer to the usage guide and start your "out-of-the-box" efficient experience now!

> **System Requirements:**
> - CPU: 2vCPUs or higher
> - RAM: 4GB or more
> - Disk: At least 40GB

## Prerequisites

[Register a Huawei account and activate Huawei Cloud](https://support.huaweicloud.com/usermanual-account/account_id_001.html)

## Image Description

| Image Specification | Feature Description | Remarks |
| --- | --- | --- |
| [Jaeger1.68.0-arm-v1](https://github.com/HuaweiCloudDeveloper/jaeger-image/tree/Jaeger1.68.0-arm-v1) | Installed and deployed based on Kunpeng servers + Huawei Cloud EulerOS 2.0 64-bit |  |

## Get Help

- For more questions, you can contact us via [issues](https://github.com/HuaweiCloudDeveloper/jaeger-image/issues) or the service support of the specified product in the Huawei Cloud Marketplace.
- For other open-source images, refer to [open-source-image-repos](https://github.com/HuaweiCloudDeveloper/open-source-image-repos).

## How to Contribute

- Fork this repository and submit a merge request.
- Update README.md based on your open-source image information.