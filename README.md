# Wiki 项目架构 1.0

## 1. 介绍

一个以职业方向和技术方向为注重点的 Wiki 系统。主要由管理员新增 “方向” 和 “知识点”，由用户编辑 “知识点”，管理员审核合并。具体内容参考 [PRD](PRD.md)（Product-Requirement-Document，产品需求文档）和[原型图](Prototype.md)（Prototype）。

### 1.1 模块架构

``` lua
wiki
├── common    -- Egg.js 框架公共模块
├── admin     -- 后台管理模块
├── upms      -- 用户权限管理系统
|   ├── upms-common -- upms 公共模块
|   ├── upms-client -- 单点登录（SSO，Single Sign On）客户端
|   └── upms-server -- 单点登录服务端
-- TODO
```

### 1.2 技术选型

#### **后端技术**

| 技术    | 内容                       |
| ------- | -------------------------- |
| Node.js | 基于 JavaScript 的运行平台 |
// TODO

#### **前端技术**
// TODO

### 1.3. 服务器

一台服务器，采用纵向集群，即负载均衡。// TODO


