# Overview
One, packeged jdbc driver to connect to hive with jdbc based clients (SQuirreL SQ, SQLWorkbench/J, etc.). No need to search and download all required jars to connect to hive with jdbc, you only need to use this jar with your jdbc client.

Based on https://github.com/timveil/hive-jdbc-uber-jar with kerberos auth support

## Motivation
I tried timveil's version of hive-jdb-uber-jar, it worked very well, till I tried with kerberos authentication. It produced an error about illegal hadoop version. I modified the original source to support kerberos authentication and use apache version of hadoop/hive jars.
