Project: NoSQL 
Author: Samuel Atiemo

Project Tasks:


0. List all databases
mandatory
Write a script that lists all databases in MongoDB.

1. Create a database
mandatory
Write a script that creates or uses the database my_db:


2. Insert document
mandatory
Write a script that inserts a document in the collection school:

The document must have one attribute name with value “Holberton school”
The database name will be passed as option of mongo command

3. All documents
mandatory
Write a script that lists all documents in the collection school:

The database name will be passed as option of mongo command

4. All matches
mandatory
Write a script that lists all documents with name="Holberton school" in the collection school:

The database name will be passed as option of mongo command

5. Count
mandatory
Write a script that displays the number of documents in the collection school:

The database name will be passed as option of mongo command

6. Update
mandatory
Write a script that adds a new attribute to a document in the collection school:

7. Delete by match
mandatory
Write a script that deletes all documents with name="Holberton school" in the collection school:

The database name will be passed as option of mongo command

8. List all documents in Python
mandatory
Write a Python function that lists all documents in a collection:

9. Insert a document in Python
mandatory
Write a Python function that inserts a new document in a collection based on kwargs:

10. Change school topics
mandatory
Write a Python function that changes all topics of a school document based on the name:

11. Where can I learn Python?
mandatory
Write a Python function that returns the list of school having a specific topic:

Prototype: def schools_by_topic(mongo_collection, topic):

12. Log stats
mandatory
Write a Python script that provides some stats about Nginx logs stored in MongoDB:

13. Regex filter
#advanced
Write a script that lists all documents with name starting by Holberton in the collection school:

The database name will be passed as option of mongo command


14. Top students
#advanced
Write a Python function that returns all students sorted by average score:

Prototype: def top_students(mongo_collection):

15. Log stats - new version
#advanced
Improve 12-log_stats.py by adding the top 10 of the most present IPs in the collection nginx of the database logs:


