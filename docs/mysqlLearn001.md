# Mysql的学习
> * 一条sql（查询,更新）是怎么执行的
> * 事务隔离
> * 索引
> * 


### 1 一条sql（查询,更新）是怎么执行的
```
select * from test where id = 1;
```
```
mermaid
graph TD
    subgraph SVN Architecture
    client1-->|read / write|SVN((SVN server))
    client2-->|read only|SVN
    client3-->|read / write|SVN
    client4-->|read only|SVN
    client5(...)-->SVN
    SVN---|store the data|sharedrive
    end
```
