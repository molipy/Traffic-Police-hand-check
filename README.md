# Traffic-Police-hand-check
基于深度学习的【交警手势识别】系统~2026原创+计算机毕设

## 项目介绍

本项目是一套面向交通指挥场景的交警手势识别系统，围绕“图像上传、智能识别、结果展示、历史留存、用户管理、公告发布”等业务需求进行设计与实现。系统前端采用 Vue3 与 Element Plus 构建交互界面，能够完成用户登录、图片上传、识别结果查看、历史记录查询及系统公告浏览等操作；后端采用 Flask 搭建轻量化服务，提供认证鉴权、识别接口、数据管理和文件访问能力；算法部分基于 TensorFlow 框架，引入 ResNet50 深度卷积神经网络模型，实现对“停止、减速指令、变道指令、右转指令、左转、左转待转指令、直行、靠边停车”8 类交警手势的自动分类识别。

![图片](https://oa-project-storage.oss-cn-hangzhou.aliyuncs.com/2a65f04c633543f4af0b52d675d3eefc.png)
![图片](https://oa-project-storage.oss-cn-hangzhou.aliyuncs.com/da9fd69acca2423fbdadf0071b5cacdf.png)
![图片](https://oa-project-storage.oss-cn-hangzhou.aliyuncs.com/a11d15deb4e84c908c66c5d4dbbc5db6.png)

## 演示视频 and 完整代码 and 安装
地址：https://www.yuque.com/ziwu/qkqzd2/enakcdsipmi5nt6c
