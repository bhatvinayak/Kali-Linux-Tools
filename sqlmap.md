# Sqlmap

sqlmap is an open source penetration testing tool that automates the process of detecting and exploiting SQL injection flaws and taking over of database servers. It comes with a powerful detection engine, many niche features for the ultimate penetration tester and a broad range of switches lasting from database fingerprinting, over data fetching from the database, to accessing the underlying file system and executing commands on the operating system via out-of-band connections.

**Syntax**

> # sqlmap -u [url] [options]

* To know the `Database name` :

    > sqlmap -u [url] --dbs
  
* To know the `Table name` :

    > sqlmap -u [url] -D [database_name] --tables
    
 * To know the `Attribute name` :

    > sqlmap -u [url] -D [database_name] -T [table_name] --columns
    
 * To `dump data` :
    
    > sqlmap -u [url] -D [database_name] -T [table_name] -C [column_name] --dump
    
* For help :
    
    > sqlmap -h
