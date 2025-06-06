# Jaeger部署指南

## ‌一、环境准备

### 系统配置
> -  服务器：鲲鹏服务器
> -  操作系统：Huawei Cloud EulerOS 2.0 64bit
> - CPU: 2vCPUs 或更高
> - RAM: 4GB 或更大
> - Disk: 至少 40GB

## ‌二、下载安装

###1.下载
```bash
# 下载 
cd /opt 
wget https://github.com/jaegertracing/jaeger/releases/download/v1.68.0/jaeger-1.68.0-linux-amd64.tar.gz

# 解压文件
tar -xzf jaeger-1.68.0-linux-amd64.tar.gz
cd jaeger-1.68.0-linux-amd64

```
###2.启动 jaeger
```bash
./jaeger-all-in-one
```