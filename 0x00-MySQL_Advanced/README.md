# MySQL Advanced Tasks

This project encompasses advanced MySQL tasks for efficient database management.

## Task Summaries

### 0. **We are all unique!**
- File: [0-uniq_users.sql](0-uniq_users.sql)
- Description: Creates a `users` table with unique attributes using SQL. Ensures the table's existence without failures.

### 1. **In and not out**
- File: [1-country_users.sql](1-country_users.sql)
- Description: Creates a `users` table with country enumeration. Sets default values and ensures script execution on any database.

### 2. **Best band ever!**
- File: [2-fans.sql](2-fans.sql)
- Description: Ranks country origins of bands based on the number of non-unique fans. Utilizes a provided table dump [metal_bands.sql](metal_bands.sql).

### 3. **Old school band**
- File: [3-metal_bands.sql](3-metal_bands.sql)
- Description: Lists Glam rock bands ranked by longevity using data from [metal_bands.sql](metal_bands.sql).

### 4. **Buy buy buy**
- File: [4-store.sql](4-store.sql)
- Description: Creates a trigger to decrease item quantity after adding a new order. Manages data consistency for a better application experience.

### 5. **Email validation to sent**
- File: [5-valid_email.sql](5-valid_email.sql)
- Description: Implements a trigger for resetting the `valid_email` attribute when the email is changed. Enhances user email validation directly in the database.

### 6. **Add bonus**
- File: [6-bonus.sql](6-bonus.sql)
- Description: Creates a stored procedure `AddBonus` for adding corrections to a student's project. Dynamically handles new or existing projects.

### 7. **Average score**
- File: [7-average_score.sql](7-average_score.sql)
- Description: Develops a stored procedure `ComputeAverageScoreForUser` to calculate and store the average score for a student.

### 8. **Optimize simple search**
- File: [8-index_my_names.sql](8-index_my_names.sql)
- Description: Adds an index `idx_name_first` on the `names` table for optimizing searches based on the first letter of names.

### 9. **Optimize search and score**
- File: [9-index_name_score.sql](9-index_name_score.sql)
- Description: Adds an index `idx_name_first_score` on the `names` table for optimizing searches based on the first letter of names and the score.

### 10. **Safe divide**
- File: [10-div.sql](10-div.sql)
- Description: Implements a function `SafeDiv` for safe division, handling cases where the divisor is zero.

### 11. **No table for a meeting**
- File: [11-need_meeting.sql](11-need_meeting.sql)
- Description: Creates a view `need_meeting` to list students needing a meeting based on low scores and absence or overdue last meetings.

### 12. **Average weighted score**
- File: [100-average_weighted_score.sql](100-average_weighted_score.sql)
- Description: Creates a stored procedure `ComputeAverageWeightedScoreForUser` to compute and store the average weighted score for a student.

### 13. **Average weighted score for all!**
- File: [101-average_weighted_score.sql](101-average_weighted_score.sql)
- Description: Creates a stored procedure `ComputeAverageWeightedScoreForUsers` to compute and store the average weighted score for all students.

## Resources
Explore these MySQL resources for enhanced understanding and performance optimization:
- [MySQL cheatsheet](https://intranet.alxswe.com/rltoken/8w9di_hk19DIMSBEV3EayQ)
- [MySQL Performance: How To Leverage MySQL Database Indexing](https://intranet.alxswe.com/rltoken/2GJbZ48zRPA70o2YhTdH7g)
- [Stored Procedure](https://intranet.alxswe.com/rltoken/K180X2OCzb6gzPngjn-EIg)
- [Triggers](https://intranet.alxswe.com/rltoken/cJ1qA4o-rRm4rWIsqYKSZg)
- [Views](https://intranet.alxswe.com/rltoken/vHg1z3UAOcWMvOt8xZHeiA)
- [Functions and Operators](https://intranet.alxswe.com/rltoken/g-c1m6iljScpi4LeqxBRqQ)
- [Trigger Syntax and Examples](https://intranet.alxswe.com/rltoken/gLVwKjQfRL0Jr_nWqAS7VQ)
- [CREATE TABLE Statement](https://intranet.alxswe.com/rltoken/X789nJ22H6HVh1uCQPl0lg)
- [CREATE PROCEDURE and CREATE FUNCTION Statements](https://intranet.alxswe.com/rltoken/mfrWMt1KL3NHXblJykMgZg)
- [CREATE INDEX Statement](https://intranet.alxswe.com/rltoken/oCu8Rg9WfKyF4BhTt8dZGQ)
- [CREATE VIEW Statement](https://intranet.alxswe.com/rltoken/FEZNlZFKZmD1ISnLINkCwQ)