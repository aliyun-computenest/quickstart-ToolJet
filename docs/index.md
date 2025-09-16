# ToolJet社区版 快速部署

## 概述。

ToolJet 是一个开源的低代码框架，用于以最少的工程工作量构建和部署内部工具。ToolJet 的拖放式前端构建器可让您在几分钟内创建复杂、响应迅速的前端。此外，您还可以集成各种数据源，包括 PostgreSQL、MongoDB 和 Elasticsearch 等数据库；具有 OpenAPI 规范和 OAuth2 支持的 API 端点；

## 前提条件

部署ToolJet社区版服务实例，需要对部分阿里云资源进行访问和创建操作。因此您的账号需要包含如下资源的权限。
**说明**：当您的账号是RAM账号时，才需要添加此权限。

| 权限策略名称                          | 备注                         |
|---------------------------------|----------------------------|
| AliyunECSFullAccess             | 管理云服务器服务（ECS）的权限           |
| AliyunVPCFullAccess             | 管理专有网络（VPC）的权限             |
| AliyunROSFullAccess             | 管理资源编排服务（ROS）的权限           |
| AliyunComputeNestUserFullAccess | 管理计算巢服务（ComputeNest）的用户侧权限 |

## 计费说明

ToolJet社区版在计算巢部署的费用主要涉及：

- 所选vCPU与内存规格
- 系统盘类型及容量
- 公网带宽

## 部署流程

1. 访问计算巢ToolJet社区版[部署链接](https://computenest.console.aliyun.com/service/instance/create/cn-hangzhou?type=user&ServiceName=ToolJet%E7%A4%BE%E5%8C%BA%E7%89%88)，按提示填写部署参数：
   ![image.png](1.jpg)

2. 参数填写完成后可以看到对应询价明细，确认参数后点击**下一步：确认订单**。

3. 确认订单完成后同意服务协议并点击**立即创建**进入部署阶段。

4. 等待部署完成后就可以开始使用服务，进入服务实例详情点击服务地址。
   ![image.png](2.jpg)

5. 加载完成后即可使用ToolJet服务。
   ![image.png](3.jpg)

## 使用帮助
更多用法请参考[ToolJet官方文档](https://docs.tooljet.ai/docs/)。
