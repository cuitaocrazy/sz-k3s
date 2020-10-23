# 说明

应用: Oracle Database Server 12c R2 Enterprise Edition

版本: 12.2.0.1

服务命: oracle

跨namespace短域名: oracle.dbs

全域名: oracle.dbs.svc.cluster.local

暴漏端口

| 端口 | 说明 |
|-----|------|
| 1521 | 数据库端口 |
| 5500 | em管理页面 |

环境配置

| 名称 | 环境变量 | 值 |
|------|---------|----|
| SID  | DB_SID  | ORCLCDB  |
| PDB  | DB_PDB  | ORCLPDB1 |
| 域   | DB_DOMAIN | localdomain |

上述环境可在oracle.yaml的container中设置启动环境变量

卷: 动态pvc