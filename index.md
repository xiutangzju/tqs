This page lists all bug reports that we created for MySQL, MariaDB and TiDB.

## Bug List

### MySQL

1. /*+ no_semijoin()*/ Inner hash join with Materialize
 https://bugs.mysql.com/bug.php?id=106713
State:verified  join col: self join:int
S2 (Serious)


2. SET optimizer_switch='subquery_to_derived=on';
https://bugs.mysql.com/bug.php?id=106715
State:verified     join col: float join text semi join float in  test
S2 (Serious)

3. SET optimizer_switch='materialization=off';
https://bugs.mysql.com/bug.php?id=106716
State:Verified      join col: float join float semi join float in float 
S2 (Serious)

4. SET optimizer_switch='firstmatch=off’; 等于materialization=on
http://bugs.mysql.com/106717
State:Verified      join col: decimal semi join decimal 
S2 (Serious)

5. SET optimizer_switch='duplicateweedout=off'; 等于materialization=on
http://bugs.mysql.com/106718
State:Verified      join col: self join : longtext semi join 
S2 (Serious)

6. 0=-0 已修复 8.0.18版本
Nested Null-Safe Equal 已修复
https://bugs.mysql.com/bug.php?id=106611
State:Duplicate
S2 (Serious)

7. Semijoin may give wrong result 
https://bugs.mysql.com/bug.php?id=106710
State:verified  
S1 (Critical)

8. Inner table of OUT-JOIN is nullable, after applying OUTER2INNER transformation
https://bugs.mysql.com/bug.php?id=106473
State:verified 
S3 (Non-critical)

9. Item_ref in Having Clause points to invalid outer table field
https://bugs.mysql.com/bug.php?id=99273
State:verified 
S2 (Serious)

### MariaDB

1. join_cache_bka
https://jira.mariadb.org/browse/MDEV-28214

2. join_cache_hashed
https://jira.mariadb.org/browse/MDEV-28215

3. outer_join_with_cache
https://jira.mariadb.org/browse/MDEV-28216

4. optimize_join_buffer_size
https://jira.mariadb.org/browse/MDEV-28217

5. join_cache_incremental
https://jira.mariadb.org/browse/MDEV-29695

### TiDB

1. Incorrect Merge Join Execution when transforming hash join to merge join
hash join to merge join 缺少varchar数据
join col: int join bigint join bigint
https://github.com/pingcap/tidb/issues/33039

2. Merge Join executed incorrect resultset which missed -0
join col: varchar join varchar int join bigint join bigint
https://github.com/pingcap/tidb/issues/33041

3. Merge Join executed incorrect resultset which returned empty resultset
join col: int join bigint join bigint int join bigint 
https://github.com/pingcap/tidb/issues/33042

4. Merge Join executed incorrect resultset which returned NULL
join col: varchar join varchar join varchar
https://github.com/pingcap/tidb/issues/33045

5. Merge Join executed incorrect resultset which missed rows
join col:varchar join float join int 
https://github.com/pingcap/tidb/issues/33046
