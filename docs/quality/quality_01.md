# 质量属性

这个部分提供digitalops-mall网站所需的质量属性（非功能需求）的信息。

## 性能

目前digitalops-mall采用公网服务器+内网穿透+树莓派（4GB内存+1.5Ghz CPU）的技术方案部署，只能但演示以及学习用，如果要商用的话，还是得采取全部应用部署到云平台（阿里云，腾讯云，百度云等），再进行性能测试，以后有机会会补上。

- [ ] 性能测试会采用**[gatling](https://github.com/gatling/gatling)**进行压力测试

## 可伸缩性

- [ ] 应用采取docker+docker compose部署，后续会结合**kubernetes**增加伸缩性；

- [ ] 数据库采用mysql，后续会采取**mysql集群部署**方案；

## 安全性

采用spring security + jwt token认证方案。

## 可用性

理由参考性能。

## 国际化

目前所有用户界面文字只用中文呈现。

## 本地化

所有信息都只使用中文的格式。

## 浏览器兼容性

digitalops-mall网站应该在以下浏览器中表现一致：

Safari；

Firefox；

Chrome；

Internet Explorer 8（及以上）。