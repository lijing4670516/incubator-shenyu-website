---
title: 配置流程介绍
keywords: ShenYu
description:  配置流程介绍
---

## 说明

* 本篇是对 shenyu-admin 后台操作数据以后，同步到网关的流程介绍。

## 使用

* 用户可以在 shenyu-admin 后台任意修改数据，并马上同步到网关的 jvm 内存中。
* 同步 ShenYu 的插件数据，选择器，规则数据，元数据，签名数据等等。
* 所有插件的选择器，规则都是动态配置，立即生效，不需要重启服务。

* 下面是数据流程图：
 ![](/img/shenyu/dataSync/plugin-data.png)

## 作用

* 用户所有的配置都可以动态的更新，任何修改不需要重启服务。
* 使用了本地缓存，在高并发的时候，提供高效的性能。
