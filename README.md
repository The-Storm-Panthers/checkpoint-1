# Checkpoint 1: SQL Analytics

### How to run our queries

* Clone our directory (in a location you will remember) using `git clone insert_link_here`
* Open your terminal, navigate to the directory you just cloned. Then cd into the src folder
* For **q1_a**, un the following command: `psql -f q1_a.sql -h cpdb.cgod7egsd6vr.us-east-2.rds.amazonaws.com -U cpdb-student -d cpdb -p 5432`
    - If you are prompted for a password, enter the following: ***datasci4lyf**
    - If typing the password in doesn't work, try to copy-and-paste it
* Repeat the above steps for each of our questions, replacing **q1_a.sql** with the corresponding file name. Here is a complete list of our SQL files that need to be executed:
    - q_1a
    - q_1b
    - q_1c
    - q_2
    - q_3
    - q_4

### Question glossary and expected output

#### **q_1b**: Are there any officers who’ve been involved in more than one home invasion?
```
officer_id | count 
------------+-------
      12478 |    41
      27778 |    39
      17397 |    32
       5913 |    29
      26096 |    29
      25306 |    28
       5193 |    28
       2725 |    28
      11634 |    26
      22828 |    26
      13095 |    26
      18205 |    26
       6678 |    25
      21703 |    24
      19888 |    23
      28280 |    23
      12491 |    23
      28378 |    22
      24521 |    21
      13420 |    21
      21260 |    21
```


#### **q_4a**: How many Wrong Address allegations have been made?
4 rows
#### **q_4b**: How many Wrong Address allegations led to settlements?
1 row
#### **q_4c**: Are officers involved in Wrong Address allegations linked to related settlements?
18 summaries
