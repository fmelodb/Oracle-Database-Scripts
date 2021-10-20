# OracleDBScripts
This repository contains scripts for DBA operations on Oracle Database. The following code is my own, and not by Oracle Corporation. This is only for testing and learning purposes, use it in production at your own risk.

The following was tested on 18c in CDB architecture (it works on a PDB):

<B>Limit Parallel Queries with Resource Manager</B>: it is a sample code for limiting the number of parallel degree per sql statement. The script creates 3 groups (high, medium, low) and assigns a limit for each. It is then mapped to an user in the database.

The following was tested on 12.1 (capture) and 19c (replay) -- comments in portuguese:

<B>Usando_SPA_com_APIs</B>: Using SQL Performance Analyzer to capture SQL TUNING SETs on source database and compare it after changes on a target database.

<B>Usando_DBReplay_com_APIs</B>: Using Database Replay on source database and compare it after changes on a target database.
