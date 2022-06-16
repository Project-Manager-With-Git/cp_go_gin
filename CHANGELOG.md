# v2.0.0

本次更新基于golang 1.18,大量改用泛型实现

## 实现修正

+ 提高了每个模块的内聚性
+ 更新了依赖,尽量改为使用泛型实现的版本

# v0.0.2

## 实现修正

+ 将项目结构调整为适应`pmfp@v4.1.6`的形式
+ 大部分重构了每个组件,现在使用`bun`替代了`xormplus`

## 新增组件

| 组件名        | 说明                                                               |
| ------------- | ------------------------------------------------------------------ |
| `simple_auth` | 最简单的用户权限控制模块,两级权限,只有超级用户可以控制用户权限操作 |

# v0.0.1

创建了项目

## 组件包括

| 组件名                | 说明                                      |
| --------------------- | ----------------------------------------- |
| `apis_init`           | RESTfulapi的接口注册模板                  |
| `apis_simple`         | RESTfulapi的简单接口实现模板(ping接口)    |
| `apis_namespace`      | RESTfulapi的复杂接口实现模板              |
| `apis`                | RESTfulapi的整体模板                      |
| `downloads_init`      | 下载接口注册模板                          |
| `downloads_namespace` | 下载接口实现模板                          |
| `downloads`           | 下载接口的整体模板                        |
| `events_init`         | sse接口注册模板                           |
| `events_setting`      | sse接口的设置项模板(主要是定时推送等业务) |
| `events_namespace`    | sse接口的实现模板                         |
| `events`              | sse接口的整体实现模板                     |
| `main`                | 入口函数模板                              |
| `simplemiddleware`    | 中间件工厂模板                            |
| `models`              | 数据模型模块模板,这里使用xormplus作为orm  |
| `apitest`             | 接口测试模板                              |
| `ssetest`             | sse测试模板                               |
| `test`                | 测试的整体模板                            |
