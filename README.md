# 后台权限管理系统

### 简述

本系统开发的初衷是为了快速的搭建后台管理权限系统，零开发拥有最全的权限控制，控制力度可以达到文字，按钮级别的控制，并且拥有多级管理员，多级权限组和单独权限的分配，完全可以应对现在系统后台多人员的管理。

另外，权限使用简单易用，你无需再开发，同时系统提供多个权限示例和功能模块开发示例，轻松实现一个增删改查的列表。

[测试地址](http://admin.codebooks.cn/)

欢迎加群讨论 669852173

### 用户管理

添加用户，编辑用户权限

用户分为四种类型，超级管理员，管理员，普通管理员，普通用户。

1. 超级管理员内置，不可被分配，权限不可被编辑，拥有系统全部增删改查权限。超级管理员可以创建全部类型用户。

2. 管理员拥有除特殊系统目录的全部操作权限，权限不可被编辑，可以创建普通管理员和普通用户。

3. 普通管理员权限可被编辑被分配，可以创建普通用户，普通管理员只能赋予普通用户自己所拥有的权限。

4. 普通用户没有访问后台管理目录的权限，仅能使用被分配的权限

### 权限组管理

支持创建权限组，同类型的权限可以分配到一个权限组中，权限组可以分配给某个用户，该用户则可以拥有权限组的全部权限。用户被分配权限组后依然会可以添加独立权限，独立权限与权限组权限取并集。

### 目录管理

用于添加左侧目录和功能权限，添加的权限用于用户和权限组种被分配，具体操作后面详解

### 配置管理

用于创建全局可以调用的参数

### 模板创建

模板创建 可以手动选择数据表，配置基本搜索table列表展示，直接生成相应文件，逻辑比较简单，还没有时间写文档，欢迎进群交流。


项目尚在完善中 问题和建议欢迎加群讨论  669852173

