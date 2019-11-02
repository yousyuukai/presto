# 利用Docker搭建Presto POC环境

## 环境准备
#### Docker
1. Container1<hadoop0>
  - Hadoop 2.7.7 master机
  - Hive 2.3.5
  - Presto 0.224
2. Container2<hadoop1>
  - Hadoop slave机
3. Container3<Mysql>
  - Mysql5.7(Hive meta信息管理用)

具体构建请参见Issues
