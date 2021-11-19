# Project_1_scudb
## Thanks for Mr Yang's visiting my assignment

## Info
* **SID:2019141460198**

* **NAME:侯俊臣**

## Desc
During the semester, you will be building a new disk-oriented storage manager for the SQLite DBMS. Such  a storage manager assumes that the primary storage location of the database is on disk. You will be using  SQLite's Virtual Table interface; this will allow you use your storage manager in SQLite without changing  application-level code. You do not need to know exactly how SQLite works to complete these assignments. 

The first programming project is to implement a buffer pool in your storage manager. The buffer pool is  responsible for moving physical pages back and forth from main memory to disk. It allows a DBMS to  support databases that are larger than the amount of memory that is available to the system. Its  operations are transparent to other parts in the system. For example, the system asks the buffer pool for  a page using its unique identifier ( page_id ) and it does not know whether that page is already in memory  or whether the system has to go retrieve it from disk. 

Your implementation will need to be thread-safe. Multiple threads will be accessing the internal data  structures at the same and thus you need to make sure that their critical sections are protected with  latches (these are called "locks" in operating systems). You will need to implement the following three  components in your storage manager: 
• Extendible Hash Table
• LRU Page Replacement Policy 
• Buffer Pool Manager 

Although SQLite is written in C, all of the code in this programming assignment must be written in C++  (specifically C++11). We are providing you with the scaffolding to have your C++ code build and link with  SQLite's virtual table API. 

This is a single-person project that will be completed individually (i.e., no groups).
