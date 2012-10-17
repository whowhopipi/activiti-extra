activiti-extra
==============

本项目是针对Activiti的扩展，包含一些常用的功能以及中国特色的工作流特性。

项目特点
=======

1. 使用Spring作为容器
2. 和Activiti每个版本（从5.10开始）紧密集合
3. 简化常用API
4. 支持中国特色工作流

参与本项目基本要求
=================

1. 熟悉Maven、Git、Github
2. 在实际项目中使用过Activiti
3. 熟悉Junit（本项目大部分的代码需要有对应的单元测试）

开发规范
======

1. 代码风格和Activiti保持一致，导入源码文件夹中eclipse目录的三个xml文件（文件名和Eclipse的配置匹配）
2. 代码提交前在本地做单元测试，所有的测试通过后才能提交


项目发布方式
============

1. 针对Activiti的不同版本创建分支，在次分支上进行构建打包
2. 目前使用Maven手动打包，之后逐步使用[travis-ci](http://travis-ci.org)代替
3. 以Maven仓库方式提供下载（jar、javadoc、source）

RoadMap
=======

## V1.0-alpha

1. 任务自动签收--ok

### TODO 

2. 流程图跟踪工具
。。。

  稍后再补充，有需要可以加入到QQ群讨论：236540304

参与开发
========

1. 发送邮件到yanhonglei[@]gmail.com申请参与
2. 在邮件中写明自己参与过的项目，以及github账号