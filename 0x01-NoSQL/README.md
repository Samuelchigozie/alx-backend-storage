# MongoDB NoSQL

This project provides tasks for learning MongoDB, a NoSQL database application.

## Tasks

### 0. **List all databases**
- MongoDB script: [0-list_databases](0-list_databases)
- Lists all databases in MongoDB.

### 1. **Create a database**
- MongoDB script: [1-use_or_create_database](1-use_or_create_database)
- Creates or uses the database `my_db`.

### 2. **Insert document**
- MongoDB script: [2-insert](2-insert)
- Inserts a document in the `school` collection with the attribute `name` set to “Holberton school”.

### 3. **All documents**
- MongoDB script: [3-all](3-all)
- Lists all documents in the `school` collection.

### 4. **All matches**
- MongoDB script: [4-match](4-match)
- Lists all documents with `name="Holberton school"` in the `school` collection.

### 5. **Count**
- MongoDB script: [5-count](5-count)
- Displays the number of documents in the `school` collection.

### 6. **Update**
- MongoDB script: [6-update](6-update)
- Adds the attribute `address` with the value “972 Mission street” to all documents with `name="Holberton school"`.

### 7. **Delete by match**
- MongoDB script: [7-delete](7-delete)
- Deletes all documents with `name="Holberton school"` in the `school` collection.

### 8. **List all documents in Python**
- Python script: [8-all.py](8-all.py)
- Lists all documents in a collection using a Python function.

### 9. **Insert a document in Python**
- Python script: [9-insert_school.py](9-insert_school.py)
- Inserts a new document in a collection based on `kwargs` using a Python function.

### 10. **Change school topics**
- Python script: [10-update_topics.py](10-update_topics.py)
- Changes all topics of a school document based on the name using a Python function.

### 11. **Where can I learn Python?**
- Python script: [11-schools_by_topic.py](11-schools_by_topic.py)
- Returns the list of schools having a specific topic using a Python function.

### 12. **Log stats**
- Python script: [12-log_stats.py](12-log_stats.py)
- Provides stats about Nginx logs stored in MongoDB (`logs` database, `nginx` collection).

### 13. **Regex filter**
- MongoDB script: [100-find](100-find)
- Lists all documents with `name` starting by `Holberton` in the `school` collection.

### 14. **Top students**
- Python script: [101-students.py](101-students.py)
- Returns all students sorted by average score using a Python function.

### 15. **Log stats - new version**
- Python script: [102-log_stats.py](102-log_stats.py)
- Improves [12-log_stats.py](12-log_stats.py) by adding the top 10 most present IPs in the `nginx` collection of the `logs` database.

## Resources
- [NoSQL Databases Explained](https://intranet.alxswe.com/rltoken/wweK7dOY4pf8haCqv9Iv6Q)
- [What is NoSQL?](https://intranet.alxswe.com/rltoken/QqqNmgzgwopHBv305ki6bg)
- [MongoDB with Python Crash Course - Tutorial for Beginners](https://intranet.alxswe.com/rltoken/RyyP9OH1EMBWWYpTs4TqoA)
- [MongoDB Tutorial 2: Insert, Update, Remove, Query](https://intranet.alxswe.com/rltoken/9__3tR-NimgXlmjPQwTF-Q)
- [Aggregation](https://intranet.alxswe.com/rltoken/ziEDeniRobC6owPE1_avAQ)
- [Introduction to MongoDB and Python](https://intranet.alxswe.com/rltoken/axwwF4CjO7FnK8Ecochqnw)
- [mongo Shell Methods](https://intranet.alxswe.com/rltoken/lUqnLwOHbbp9FK39ijNmDQ)
- [The mongo Shell](https://intranet.alxswe.com/rltoken/bffQMLcTB4cg1bKqgBW3jw)