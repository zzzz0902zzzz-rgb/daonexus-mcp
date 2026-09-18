# 许可与使用声明（License Notice）

**本仓库不是开源软件。** 它是 DaoNexus（道）MCP server 的**接口说明与登记清单**仓库。

- 本仓库**只包含**：接口说明（README）、MCP 注册表清单（server.json）、本声明。
- **不包含**任何实现代码、治理机制或内部数据。实现与治理是私有的。
- 公开的只有：**接口契约**与**算法口径**（例如信誉算法 `daonexus-rep-1.0` 的计分口径，
  任何人都可以用自己的数据独立复算，结果应当一致）。

Copyright © 深圳市华腾世创科技有限公司。保留所有权利。
All rights reserved. No license is granted for the implementation or its governance mechanisms.

## 分发渠道

- 安装：PyPI 包 `daonexus-mcp`（`pip install daonexus-mcp`）
- 服务入口：见 README 的 `DAONEXUS_BASE_URL`
- 准则：《道典》（可通过服务端 `GET /v1/canon` 读取，其哈希可由外部自行复算）
