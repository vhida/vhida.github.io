Traditional row-based relational database is write-optimised, which is not so effective for ad hoc query of large amount of data. To address the issue, this paper presents the design of a column-based relational database. 
The distinctiveness of the design is its column organisation of data, which conduces to various techniques of data compression and hence read performance improvement. 
The paper also presents a non-traditional transaction implementation of read-only transactions. It separates reads and writes and avoids use of lock on reads. It mainly applies snapshot isolation and periodic synchronisation.