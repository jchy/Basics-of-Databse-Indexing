## Database Indexing
### Problem
- 1. explain what is indexing in simple analogy?
- 2. why do we use it?
- 3. explain in simple terms how indexing pros and cons.
- 4. if you can explain a bit about the data structure used
- 5. what is compound indexing?

### Solutions
- 1. Indexing is similar to that of a book, Like in books we do indexing to find out chapters or topics very easily similar to that we do indexing in databse to execute the query at faster rate and minimize the number of documents scan for a read operation.

- 2. We use indexing to maximize the efficiency of read operation of the database. So when we do indexing we only scan those dopcuments which are relavent and may contain the desired output.
Indexing significantly reduces the number of documents scan and hence the performance of reading from the database is much more increased.

- 3.1 Pros of Indexing are :~
- i. Indexing increase the read performance of carrying out a query
- ii. Indexing reduces the total number of documents scanned 
- iii. It only scan the relavent documents
- iv. Time take by the query to be execute decreased significantly

- 3.2 Cons of Indexing are :~
- i. Indexing is done using a data structure called B-Tree
- ii. Insertion of new dopcuments become costly operation.
- iii. Updation of dopcuments become costly operation.
- iv. Deletion of dopcuments become costly operation.

- 4. B-Tree data structure is used in implementation of indexing in the database.
- 5. When we do indexing using multiple fileds to create a index, it is called compound indexing.
Ex. db.collection_name.createIndex({filed_1_name:type, field_2_name : type});