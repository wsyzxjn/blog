---
title: How to utilize the streaming media enhancement feature in OpenClash
published: 2024-04-08
description: ''
image: ''
tags: [OpenWRT]
category: 'OpenWRT'
draft: false 
---

# 准备工作

* 确认你的openclash插件已经正常安装。并且配置文件可以正常启动。
* **确保你没有开启一键生成功能 (如下图)**
![streaming media](image.png)

# 具体步骤

1. 创建一个策略组，名字为你需要使用流媒体增强的应用。**确保策略组类型为Select** ，按你的实际情况选择需要包含的其他策略组。
![alt text](image-1.png)
2. 打开 插件设置-流媒体增强 勾选自动选择解锁节点  
如果是使用Netflix、Disney Plus，建议勾选：**实验性：预解析 Netflix、Disney Plus 域名**  
建议勾选 **关闭旧链接**，不建议勾选 **展开策略组**
3. 在下方列表中勾选你需要使用流媒体增强的应用  
在策略组筛选中填入第一步你创建的策略组名称  
**解锁区域**根据你的需求填写，**解锁节点**筛选可以不填
4. 保存并应用配置，查看日志是否有相关输出