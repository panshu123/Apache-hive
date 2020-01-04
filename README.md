In this project m using dynamic partition which helps me give fastest result if m just load the dataset in a hive table and perform select query with where clause it search on a whole table it take time but partition creates differenet tables in backend of all countries which helps me give a fastest result because if  m perform select query with where clause on partition table it searches only on that particular backend table instead of whole table.

In this project m using DDL and DML commands of hive with the help of apache hive.org.

And m storing the output on local directory inside the hive_project folder by using this command (hive -e 'use deepanshu; query' | sed 's/[\t]/,/g' > /home/training/hive_project/.........csv)

m taking some help with stackoverflow and google and  i have completed this project in 2 days
