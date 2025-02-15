注意：以下功能均为对应版本已实现的功能，实测可用。

|   应用    |     方向     | 功能                                        |  进展   |
|:-------:|:----------:|-------------------------------------------|:-----:|
|  开发中心   |  FlinkSQL  | 支持 sql-client 所有语法                        | 0.4.0 |
|         |            | 支持 Flink 所有 Configuration                 | 0.4.0 |
|         |            | 支持 Flink 所有 Connector                     | 0.4.0 |
|         |            | 支持 SELECT、SHOW 等查询实时预览                    | 0.4.0 |
|         |            | 支持 INSERT 语句集                             | 0.4.0 |
|         |            | 新增 SQL 片段语法                               | 0.4.0 |
|         |            | 新增 AGGTABLE 表值聚合语法及 UDATF 支持              | 0.4.0 |
|         |            | 新增 CDCSOURCE 多源合并语法支持                     | 0.6.0 |
|         |            | 新增 FlinkSQLEnv 执行环境复用                     | 0.5.0 |
|         |            | 新增 Flink Catalog 交互查询                     | 0.4.0 |
|         |            | 新增 执行环境的共享与私有会话机制                         | 0.4.0 |
|         |            | 新增 多种方言的作业目录管理（FlinkSQL、SQL、Java）         | 0.5.0 |
|         |            | 新增 作业配置与执行配置管理                            | 0.4.0 |
|         |            | 新增 基于 Explain 的语法校验与逻辑解析                  | 0.4.0 |
|         |            | 新增 JobPlan 图预览                            | 0.5.0 |
|         |            | 新增 基于 StreamGraph 的表级血缘分析                 | 0.4.0 |
|         |            | 新增 基于上下文元数据自动提示与补全                        | 0.4.0 |
|         |            | 新增 自定义规则的自动提示与补全                          | 0.4.0 |
|         |            | 新增 关键字高亮与代码缩略图                            | 0.4.0 |
|         |            | 新增 选中片段执行                                 | 0.4.0 |
|         |            | 新增 布局拖拽                                   | 0.4.0 |
|         |            | 新增 SQL导出                                  | 0.5.0 |
|         |            | 新增 快捷键保存、校验、美化                      | 0.5.0 |
|         |            | 支持 local 模式下 FlinkSQL 提交                  | 0.4.0 |
|         |            | 支持 standalone 模式下 FlinkSQL 提交             | 0.4.0 |
|         |            | 支持 yarn session 模式下 FlinkSQL 提交           | 0.4.0 |
|         |            | 支持 yarn per-job 模式下 FlinkSQL 提交           | 0.4.0 |
|         |            | 支持 yarn application 模式下 FlinkSQL 提交       | 0.4.0 |
|         |            | 支持 kubernetes session 模式下 FlinkSQL 提交     | 0.5.0 |
|         |            | 支持 kubernetes application 模式下 FlinkSQL 提交 | 0.5.0 |
|         |            | 支持 UDF Java 方言Local模式在线编写、调试、动态加载         | 0.5.0 |
|         |  Flink 作业  | 支持 yarn application 模式下 Jar 提交            | 0.4.0 |
|         |            | 支持 k8s application 模式下 Jar 提交             | 0.5.0 |
|         |            | 支持 作业 Cancel                              | 0.4.0 |
|         |            | 支持 作业 SavePoint 的 Cancel、Stop、Trigger     | 0.4.0 |
|         |            | 新增 作业自动从 SavePoint 恢复机制（包含最近、最早、指定一次）     | 0.4.0 |
|         |  Flink 集群  | 支持 查看已注册集群的作业列表与运维                        | 0.4.0 |
|         |            | 新增 自动注册 Yarn 创建的集群                        | 0.4.0 |
|         |    SQL     | 新增 外部数据源的 SQL 校验                          | 0.5.0 |
|         |            | 新增 外部数据源的 SQL 执行与预览                       | 0.5.0 |
|         |     BI     | 新增 折线图的渲染                                 | 0.5.0 |
|         |            | 新增 条形图图的渲染                                | 0.5.0 |
|         |            | 新增 饼图的渲染                                  | 0.5.0 |
|         |    元数据     | 新增 查询外部数据源的元数据信息                          | 0.4.0 |
|         |            | 新增 FlinkSQL 和 SQL 的自动生成                   | 0.6.0 |
|         |     归档     | 新增 执行与提交历史                                | 0.4.0 |
|  运维中心   |     暂无     | 暂无                                        | 0.4.0 |
|  注册中心   | Flink 集群实例 | 新增 外部 Flink 集群实例注册                        | 0.4.0 |
|         |            | 新增 外部 Flink 集群实例心态检测与版本获取                 | 0.4.0 |
|         |            | 新增 外部 Flink 集群手动一键回收                      | 0.4.0 |
|         | Flink 集群配置 | 新增 Flink On Yarn 集群配置注册及测试                | 0.4.0 |
|         |  User Jar  | 新增 外部 User Jar 注册                         | 0.4.0 |
|         |    数据源     | 新增 Mysql 数据源注册及测试                         | 0.4.0 |
|         |            | 新增 Oracle 数据源注册及测试                        | 0.4.0 |
|         |            | 新增 postgreSql 数据源注册及测试                    | 0.4.0 |
|         |            | 新增 ClickHouse 数据源注册及测试                    | 0.4.0 |
| OpenApi |     调度     | 新增 submitTask 调度接口                        | 0.5.0 |
|         |  FlinkSQL  | 新增 executeSql 提交接口                        | 0.5.0 |
|         |            | 新增 explainSql 验证接口                        | 0.5.0 |
|         |            | 新增 getJobPlan 计划接口                        | 0.5.0 |
|         |            | 新增 getStreamGraph 计划接口                    | 0.5.0 |
|         |            | 新增 getJobData 数据接口                        | 0.5.0 |
|         |   Flink    | 新增 executeJar 提交接口                        | 0.5.0 |
|         |            | 新增 cancel 停止接口                            | 0.5.0 |
|         |            | 新增 savepoint 触发接口                         | 0.5.0 |
|   关于    |  关于 Dinky  | 版本更新记录  