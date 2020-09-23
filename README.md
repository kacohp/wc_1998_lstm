# wc_1998_lstm
This  file is coded on python and works with mysql asynchronously. 

This is python code that is asyncronized with mysql.
Takes data from files and using predefined make file creates txt files 
Using this files it cuts eachline and specisic requested time form raw string
String that is cut is going to added to database 
Because the maximum size of adding data into mysql DB at once is 16MB(approximately) which why we created multiple databases for each day 
Next function is going to count the number and add to another day based database by appending them all
Whole database is converted to csv 
Using each csv we are going to train our RNN model that is LSTM.


References
  - ftp://ita.ee.lbl.gov/traces/WorldCup/ (This is where you can download all workload 1998 traces)
  - http://colah.github.io/posts/2015-08-Understanding-LSTMs/ (This is from where you can read about LSTM more)
