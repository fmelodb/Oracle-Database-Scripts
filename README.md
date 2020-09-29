# OracleDBScripts
This repository contains scripts for DBA operations on Oracle Database. The following code is my own, and not by Oracle Corporation. This is only for testing and learning purposes, use it in production by your own risk.

The following was tested on 18c in CDB architecture (it works on a PDB).

<B>Limit Parallel Queries with Resource Manager</B>: it is a sample code for limiting the number of parallel degree per sql statement. The script creates 3 groups (high, medium, low) and assigns a limit for each. It is then mapped to an user in the database.
