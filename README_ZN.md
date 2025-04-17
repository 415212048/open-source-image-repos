# 开源易用性提升介绍 | [English](README.md)
本项目通过 **华为云商店开源镜像** 以及 **多种场景化方案** 为开发者提供更丰富、便捷、高效的开源资源与服务。华为云商店开源镜像资源丰富，含多类语言组件、操作系统及工具镜像，配置与使用简单便捷（自动化部署），并提供多种场景化方案帮助开发者更好地利用开源技术达成业务创新与发展。

## 1 开源镜像（开源 + 华为云）
本次规划旨在为开发者提供多种领域的开源镜像服务。

- **开源项目**：开源项目名称及源码地址
- **版本**：开源项目版本
- **云商店地址**：开源镜像地址
- **适配项**：华为云云服务适配清单
- **操作系统**：开源镜像使用的OS
- **镜像使用指南**：开源镜像使用指南，内含配置说明

### 1.1 大数据

| 序号 | 开源项目 | 工具类型 | 版本 | 云商店地址 | 适配项 | 操作系统 | CPU架构 | 镜像使用指南 | 备注 |
| --- | --- | --- | --- | --- | --- | --- | --- | --- | --- |
| 1 | Flink | 流批一体计算引擎 | 1.13.0 | https://marketplace.huaweicloud.com/hidden/contents/992480da-64a3-4ba8-90cb-686d1832e96a#productid=OFFI1111485128289529856	 | ECS | Huawei Cloud EulerOS 2.0 64bit | ARM |  |
| 2 | DolphinScheduler | 任务调度 | 3.2.2 | https://marketplace.huaweicloud.com/intl/hidden/contents/9f9bc006-7f3b-4038-8a12-3c271bbbfdb4 | GaussDB | Ubuntu 24.04 server 64bit | X86 |  |

### 1.2 数据库
| 序号 | 开源项目 | 工具类型 | 版本 | 云商店地址 | 适配项 | 操作系统 | CPU架构 | 镜像使用指南 | 备注 |
| --- | --- | --- | --- | --- | --- | --- | --- | --- | --- |
| 1 | redis6 | 内存数据库 | 6.2.7 | [云商店镜像地址]（https://marketplace.huaweicloud.com/hidden/contents/61248ad4-be4d-4078-a918-ad59ef63a52f#productid=OFFI1111824746859552768） | ECS | Huawei Cloud EulerOS 2.0 64bit | ARM |  |

### 1.3 AI
| 序号 | 开源项目 | 工具类型 | 版本 | 云商店地址 | 适配项 | 操作系统 | CPU架构 | 镜像使用指南 | 备注 |
| --- | --- | --- | --- | --- | --- | --- | --- | --- | --- |
| 1 | Flair | NLP | en-ner-conll03-v0.4.pt | https://marketplace.huaweicloud.com/intl/hidden/contents/a89da69c-28f1-41ec-bd37-7b056c927389 | ECS | Huawei Cloud EulerOS 2.0 64bit | ARM |  |
| 2 | InternLM |多模态大模型  | internlm2_5-1_8b-chat | https://marketplace.huaweicloud.com/intl/hidden/contents/a998b510-95d8-45cc-984b-8ee4fb8bd4b7	 | ECS | Huawei Cloud EulerOS 2.0 64bit | ARM |  |

## 2 场景化方案

| 序号 | 方案名称 | 业务场景 | 核心功能 | Demo地址 | 云商店地址 | 备注 |
| --- | --- | --- | --- | --- | --- | --- |
| 1 | 基于 airflow + openMetadata + openSearch + OBS 的元数据平台建设 |  |  |  |  |  |
| 2 | 基于 spark + hetu + DataArts + jupterhub 的数据查询&处理 |  |  |  |  |  |
| 3 | 基于 rclone + OBS 的多种异构数据迁移 |  |  |  |  |  |
| 4 | 基于 superset 的数据可视化 |  |  |  |  |  |
| 5 | 基于 seatunnel/datax 的实时/离线数据采集 |  |  |  |  |  |
| 6 | 基于 azkaban + hadoop 的任务调度 |  |  |  |  |  |
| 7 | 基于 flink + hudi 的数据湖建设 |  |  |  |  |  |
| 8 | 基于 hive + spark + OBS 的数据仓库建设&数据治理方案 |  |  |  |  |  |
| 9 | 基于 debezium + doris 的低成本大数据报表查询方案 |  |  |  |  |  |
| 10 | 基于 ranger 的数据数据安全方案 |  |  |  |  |  |

更多问题可通过 [issue](https://github.com/HuaweiCloudDeveloper/open-source-image-repos/issues) 或 [华为云开源协作创新平台](https://developer.huaweicloud.com/programs/opensource/contributing/) 与我们取得联系。
