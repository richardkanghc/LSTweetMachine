# LSTweetMachine 
### Generating Trashy Big Data Tweets
### ... with LSTM
<hr>
#### Prerequisites:

```.sh
sudo apt-get install sqlite3
pip3 install -r requirements.txt
```

<hr>
#### Useful sqlite3 cmds:
```.sh
.tables
select * from tweets limit 10
drop table tweets
select count(*) from tweets
``` 
<hr>
#### Description of directories:

/data:
/data/setup_sqlitedb.py -> Sets up sqlite3 database in /database dir 
/data/get_tweets.py -> Reads twitter usersfrom profiles.txt, fetches their latest tweets and stores them in the db created above

/lib: 
Habit

/src:
Habit

/docs:
Put any documentation needed here


