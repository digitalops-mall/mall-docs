# digitalops-mall项目介绍及架构

## 项目简介
​    疫情以来，本人突然有个想搭建一套移动版电子商城的想法，于是寻找各种开源技术来搭建，发现现有开源的电子商城大多数没有一套从前台到后台到支付完整流程的项目。于是本人决定利用现有开源技术搭建一套完整的移动多端电子商城。Google了一番，发现Github上的[mall项目](https://github.com/macrozheng/mall)和[xxpay项目](https://github.com/jmdhappy/xxpay-master)stars比较多，就基于这两套系统来做一套完整的移动多端电子商城。考虑到现在移动端android和ios都非常受欢迎，所有考虑用多端技术。又考虑到一些大学生以及小型企业所承担的服务器成本问题，本人选用树莓派来搭建digitalops-mall项目。下面一些基本的多端技术比较以及开源协议的简要介绍和digitalops-mall项目的总体架构.

## 多端技术选型

### 支持的小程序框架

![image-20201201124314535](https://digittalops.oss-cn-beijing.aliyuncs.com/docs/image-20201201124314535.png)

### 总体生态对比

![image-20201201124421426](https://digittalops.oss-cn-beijing.aliyuncs.com/docs/image-20201201124421426.png)

详情请看以下链接：

[小程序多端框架全面测评：chameleon、Taro、uni-app、mpvue、WePY](https://www.cnblogs.com/fundebug/p/compare-wechat-app-frameworks.html)

[小程序框架选型必看：Taro vs uni-app选型经历！](https://cloud.tencent.com/developer/article/1631593)

## 开源协议简要介绍

沿用开源技术，那就得遵守开源协议，尊重作者的劳动成果。以下是阮一峰大神的一篇[开源协议介绍](https://www.ruanyifeng.com/blog/2011/05/how_to_choose_free_software_licenses.html)图.

![image-20201201130732912](https://digittalops.oss-cn-beijing.aliyuncs.com/docs/image-20201201130732912.png)

## 项目架构

### 总体简要架构

![image-20201201175414504](https://digittalops.oss-cn-beijing.aliyuncs.com/docs/image-20201201175414504.png)

### 技术架构（连载中...）