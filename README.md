# reducing-back-to-table-lookups
减少回表查询/回表优化

## 满足条件
1. 索引：B+树

    [B+树介绍](https://www.bilibili.com/video/BV1pJ4m1j7Pm)

2. `SQL`的执行顺序
   1. `FROM`、`JOIN`
   2. `WHERE`、`GROUP BY`、`HAVING`
   3. `SELECT`、`ORDER BY`、`LIMIT`

4. 内层`SELECT`只搜索主键

5. 在外层`SELECT`出实际字段之前会过滤掉很多的行

## 案例一-深度分页

## 案例二-历史表（显示最新版本/显示所有版本）

## 案例三-数据字典
