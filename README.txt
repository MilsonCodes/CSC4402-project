1.  ssh cs4402xx@classes.csc.lsu.edu
2.  mkdir project
3.  exit server
4.  scp files.zip cs4402xx@classes.csc.lsu.edu:~/project
5.  ssh cs4402xx@classes.csc.lsu.edu
7.  cd project
8.  unzip files.zip
9.  mysql --local-infile -ucs4402xx -pxxxxxx cs4402xx <create_table.sql
10. mysql -ucs4402xx -pxxxxxx
11. use 4402xx
12. run queries