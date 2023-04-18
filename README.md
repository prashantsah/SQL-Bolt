# SQL-Bolt
## ANSWER









### SQL Lesson 12: Order of execution of a Query <br>
-- Find the number of movies each director has directed 
SELECT director, count(director)
from movies
group by director
