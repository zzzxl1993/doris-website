---
{
    "title": "CLEAN PROFILE",
    "language": "zh-CN"
}
---

<!--
Licensed to the Apache Software Foundation (ASF) under one
or more contributor license agreements.  See the NOTICE file
distributed with this work for additional information
regarding copyright ownership.  The ASF licenses this file
to you under the Apache License, Version 2.0 (the
"License"); you may not use this file except in compliance
with the License.  You may obtain a copy of the License at

  http://www.apache.org/licenses/LICENSE-2.0

Unless required by applicable law or agreed to in writing,
software distributed under the License is distributed on an
"AS IS" BASIS, WITHOUT WARRANTIES OR CONDITIONS OF ANY
KIND, either express or implied.  See the License for the
specific language governing permissions and limitations
under the License.
-->

## 描述

用于手动清理所有历史 query 或 load 的 profile 信息。

## 语法

```sql
CLEAN ALL PROFILE
```

## 权限控制

执行此 SQL 命令的用户必须至少具有以下权限：

| 权限（Privilege） | 对象（Object） | 说明（Notes）                 |
|:--------------|:-----------|:--------------------------|
| GRANT_PRIV         | 数据库          | 若执行 CLEAN 语句需要获得 GRANT 权限 |

## 示例

```sql
CLEAN ALL PROFILE
```



