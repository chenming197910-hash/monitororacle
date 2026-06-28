# monitororacle

Oracle 监控重构部署包。

- 元数据库：Oracle 19c PDB `emccpdb`
- 默认 schema：`newmonitor`
- 原则：监控采集只读，不修改被收集数据库对象
- DDL 发布中心：独立人工变更模块，需发布密码、两次确认和确认短语

部署包：

- `gjzqdb-ops-monitor-oracle-rebuild-p1-20260628.tar.gz`
