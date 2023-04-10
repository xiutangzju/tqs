  
This page lists all bug reports that we created for MySQL, MariaDB and TiDB.  
  
## Bug List  

### MySQL  

**1. Incorrect Semi-join Execution**  
Links: [bugtracker](https://bugs.mysql.com/bug.php?id=106713)  
Severity: S2 (Serious)  
State: Verified  
  

**2. Incorrect left hash join with subquery in condition**  
Links: [bugtracker](https://bugs.mysql.com/bug.php?id=106715)  
Severity: S2 (Serious)  
State: Verified  
  
**3. Incorrect Inner hash join when transforming materialization condition**  
Links: [bugtracker](https://bugs.mysql.com/bug.php?id=106716)  
Severity: S2 (Serious)  
State: Verified  
  
**4. Incorrect nested loop antijoin when using materialization strategy**  
Links: [bugtracker](http://bugs.mysql.com/106717)  
Severity: S2 (Serious)  
State: Verified  
  
**5. Incorrect inner hash join when using materialization strategy**  
Links: [bugtracker](http://bugs.mysql.com/106718)  
Severity: S2 (Serious)  
State: Fixed  

**6. Nested Null-Safe Equal gives wrong result**  
Links: [bugtracker](https://bugs.mysql.com/bug.php?id=106611)  
Severity: S2 (Serious)  
State: Fixed  

**7. Semijoin may give wrong result**  
Links: [bugtracker](https://bugs.mysql.com/bug.php?id=106710)  
Severity: S1 (Critical)  
State: Fixed  

**8. Inner table of OUT-JOIN is nullable, after applying OUTER2INNER transformation**  
Links: [bugtracker](https://bugs.mysql.com/bug.php?id=106473)  
Severity: S3 (Non-critical)   
State: Verified  
  

**9. Item_ref in Having Clause points to invalid outer table field**  
Links: [bugtracker](https://bugs.mysql.com/bug.php?id=99273)  
Severity: S2 (Serious)  
State: Verified  

**10. Incorrect Left Outer Join Execution**  
Links: [bugtracker](https://bugs.mysql.com/bug.php?id=109211)  
Severity: S1 (Critical)  
State: Fixed  

**11. Incorrect Hash Semijoin Execution**  
Links: [bugtracker](https://bugs.mysql.com/bug.php?id=109212)  
Severity: S1 (Critical)  
State: Verified  
  

### MariaDB
  
**1. Incorrect Join Execution When Controlling BKA and BKAH Join Algorithms**  
Links: [bugtracker](https://jira.mariadb.org/browse/MDEV-28214)  
Priority: Major  
State: CONFIRMED  


**2. Incorrect Join Execution When Controlling BNLH and BKAH Join Algorithms**  
Links: [bugtracker](https://jira.mariadb.org/browse/MDEV-28215)  
Priority: Major  
State: CONFIRMED    

**3. Incorrect Join Execution When Controlling Outer Join Operations**  
Links: [bugtracker](https://jira.mariadb.org/browse/MDEV-28216)  
Priority: Major  
State: CONFIRMED  

**3. Incorrect Join Execution When Controlling Outer Join Operations**  
Links: [bugtracker](https://jira.mariadb.org/browse/MDEV-28216)  
Priority: Major  
State: CONFIRMED  


**4. Incorrect Join Execution When Controlling Join Buffer Size**  
Links: [bugtracker](https://jira.mariadb.org/browse/MDEV-28217)  
Priority: Critical  
State: CONFIRMED  

**5. Incorrect Join Execution When Controlling Join Cache**  
Links: [bugtracker](https://jira.mariadb.org/browse/MDEV-29695)    
Priority: Major  
State: CONFIRMED   


### TiDB  

**1. Incorrect Merge Join Execution when transforming hash join to merge join**  
Links: [bugtracker](https://github.com/pingcap/tidb/issues/33039)  
Severity: Critical  
State: Fixed  

**2. Merge Join executed incorrect resultset which missed -0**    
Links: [bugtracker](https://github.com/pingcap/tidb/issues/33041)      
Severity: Critical  
State: Fixed  

**3. Merge Join executed incorrect resultset which returned empty resultset**  
Links: [bugtracker](https://github.com/pingcap/tidb/issues/33042)  
Severity: Critical  
State: Fixed  

**4. Merge Join executed incorrect resultset which returned NULL**  
Links: [bugtracker](https://github.com/pingcap/tidb/issues/33045)  
Severity: Critical  
State: Fixed  
  

**5. Merge Join executed incorrect resultset which missed rows**  
Links: [bugtracker](https://github.com/pingcap/tidb/issues/33046)  
Severity: Critical  
State: Fixed  

