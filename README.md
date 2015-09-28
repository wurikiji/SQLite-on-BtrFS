# SQLite-on-BtrFS
Optimize the SQLite database on the BtrFS which supports copy-on-write mechanism. 

BtrFS provides copy_file_range() operation inside of it. SQLite has an opportunity to use this system call to improve and solve the journaling performance 

Base version of SQLite: 3.8.11.1
