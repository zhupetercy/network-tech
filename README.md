# 朱承遥 · 网络技术成果集

北京信息科技大学 计算机科学与技术 本科（2023.09 – 2027.09）
星融元数据技术有限公司 国际拓展部 · 产品专员实习生（2026.9 – 2026.12）

这里收录了我在星融元实习期间的技术产出，包括白皮书、SRv6 技术文章、方案汇总报告、产品学习文档和仿真实验拓扑。每项都是我本人撰写或搭建的，点开文件即可在线查看（内容仅涉及公司公开产品与通用技术的学习成果，不涉及公司机密）。

联系邮箱：zcy20050228@163.com

## 成果一览

| 成果 | 内容 | 文件 |
| --- | --- | --- |
| 技术白皮书（中文版） | 面向超大规模 AI 训练的端网协同智算网络：星融元 AI 控制器与 EasyRoCE 联合架构解析。独立撰写，用 LaTeX 排版 | [PDF](whitepaper/AI控制器与EasyRoCE联合架构白皮书_中文版.pdf) |
| 技术白皮书（英文版） | 上述白皮书的英文版（Joint Architecture Analysis of Asterfusion AI Controller and EasyRoCE） | [PDF](whitepaper/AI-Controller-EasyRoCE-Whitepaper_EN.pdf) |
| SRv6 深度技术解密 | 告别 MPLS 标签束缚：SRv6 的核心特性与实验现象 | [PDF](srv6/SRv6深度技术解密_核心特性与实验现象.pdf) |
| SRv6 实践与应用 | 在星融元 CX308P-48Y-M（AsterNOS）真机上以 IS-IS 打底、通过 MP-BGP 跑通多租户 L3VPN，并结合抓包分析 SRH 报头与 TE 动静态选路 | [PDF](srv6/SRv6实践与应用_IS-IS_L3VPN_TE选路.pdf) |
| EasyRoCE 与 AI 控制器协作汇总报告 | 梳理 EasyRoCE 无损网络方案与 AI 控制器的协作流程 | [PDF](easyroce/EasyRoCE与AI控制器的协作-汇总报告.pdf) · [Word](easyroce/EasyRoCE与AI控制器的协作-汇总报告.docx) |
| 无缝切换对比文档 | CX-N 数据中心无缝迁移 vs CX-M 园区无线无缝漫游：从场景、机制、关键技术三方面对比两类无缝切换方案 | [PDF](product-notes/CX-N无缝迁移_vs_CX-M无线无缝漫游.pdf) |
| 产品学习文档 | 公司全系列产品手册、公司简介、Open Networking、NPB 原理的学习总结（思维导图） | [产品手册](product-notes/产品手册总结.pdf) · [公司简介](product-notes/公司简介总结.pdf) · [Open Networking](product-notes/Open-Networking总结.pdf) · [NPB 原理](product-notes/NPB原理.pdf) |
| GNS3 仿真实验拓扑 | 基于 GNS3 和 vAsterNOS 虚拟设备搭建的 OSPF、跨 VLAN 实验拓扑，配合 Wireshark 抓包验证 | [OSPF](gns3-labs/OSPF实验拓扑.drawio) · [跨 VLAN](gns3-labs/跨VLAN实验拓扑.drawio) |

拓扑图是 draw.io 格式，GitHub 无法直接预览。下载后可以用 [app.diagrams.net](https://app.diagrams.net) 打开。

## 涉及技术

VLAN · OSPF · IS-IS · BGP / MP-BGP · SRv6 L3VPN · TE 选路 · VXLAN · RoCE 无损网络 · GNS3 · Wireshark · LaTeX
