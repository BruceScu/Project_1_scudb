# Project_1_scudb
## Thanks for Mr Yang's visiting my assignment

## Info
* **SID:2019141460198**

* **NAME:侯俊臣**

## Desc
OVERVIEW
The second programming project is to implement an index in your database system. The index is responsible 
for fast data retrieval without having to search through every row in a database table, providing the basis for 
both rapid random lookups and efficient access of ordered records.
You will need to implement B+Tree dynamic index structure. It is a balanced tree in which the internal pages 
direct the search and leaf pages contains actual data entries. Since the tree structure grows and shrink 
dynamically, you are required to handle the logic
of split and merge. The project is comprised of the following three tasks:
Task #1 - B+Tree Pages
Task #2 - B+Tree Data Structure
Task #3 - Index Iterator
This is a single-person project that will be completed individually (i.e., no groups).


PROJECT SPECIFICATION
Like the first project, we are providing you with stub classes that contain the API that you need to implement. 
You should not modify the signatures for the pre-defined functions in these classes. If you do this, then it will 
break the test code that we will use to grade your assignment you end up getting no credit for the project. If 
a class already contains certain member variables, you should notremove them. But you may add private 
helper functions/member variables to these classes in order to correctly realize the functionality.
The correctness of B+Tree index depends on the correctness of your implementation of buffer pool, we will 
not provide solutions for the previous programming projects. Since the second project is closely related to 
the third project in which you will implement index crabbing within existing B+ index, we have passed in a 
pointer parameter called transaction with default value nullptr . You can safely ignore the parameter for now; 
you don't need to change or call any functions relate to the parameter.
