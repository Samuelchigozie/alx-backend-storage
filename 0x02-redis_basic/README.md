# Redis Basics

This project focuses on learning to use the Redis NoSQL data storage application through Python3.

## Tasks

### 0. **Writing strings to Redis**
- Python script: [exercise.py](exercise.py)
- Creates a `Cache` class with methods to store data in Redis using random keys.

### 1. **Reading from Redis and recovering original type**
- Python script: [exercise.py](exercise.py)
- Adds a `get` method to the `Cache` class for retrieving data from Redis with optional type conversion.

### 2. **Incrementing values**
- Python script: [exercise.py](exercise.py)
- Implements a `count_calls` decorator to count method calls in the `Cache` class.

### 3. **Storing lists**
- Python script: [exercise.py](exercise.py)
- Defines a `call_history` decorator to store the history of inputs and outputs for a particular function.

### 4. **Retrieving lists**
- Python script: [exercise.py](exercise.py)
- Implements a `replay` function to display the history of calls for a particular function.

### 5. **Implementing an expiring web cache and tracker**
- Python script: [web.py](web.py)
- Implements a `get_page` function that obtains HTML content from a URL, tracks access count, and caches the result with a 10-second expiration time.

## Resources
- [Redis commands](https://intranet.alxswe.com/rltoken/lQ8ANhVfxDTxDr2UDSyQRA)
- [Redis Python client](https://intranet.alxswe.com/rltoken/imfgFhAZPlg7YMZ_tHvFZw)
- [How to Use Redis With Python](https://intranet.alxswe.com/rltoken/7SluvFvgckwVgsvrfOf1CQ)
- [Redis Crash Course Tutorial](https://intranet.alxswe.com/rltoken/hJVo3XwMMFFoApyX8zPXvA)