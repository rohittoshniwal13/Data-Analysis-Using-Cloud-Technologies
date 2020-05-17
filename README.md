# Data-Analysis-Using-Cloud-Technologies
Questions to be solved in this Assignment
1. Get data from Stack Exchange 
Acquire the top 200,000 posts by viewcount (see notes on Data Acquisition) 
2. Load them with PIG 
Using Pig or MapReduce, extract, transform and load the data as applicable
3. Query them with Hive 
Using Hive and/or MapReduce, get: 
I. The top 10 posts by score 
II. The top 10 users by post score 
III. The number of distinct users, who used the word “Hadoop” in one of their posts 
4. Calculate TF-IDF with MapReduce (Note: plenty of versions of code online in both Java and Python, just acknowledge the source and the changes you had to do to it)
Using Mapreduce calculate the per-user TF-IDF (just submit the top 10 terms for each of the top 10 users from Query 3.II)
