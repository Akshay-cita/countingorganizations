# Counting Organizations
This application will read the mailbox data (mbox.txt) and count the number of email messages per organization (i.e. domain name of the email address) using a database sqlite3
## Note:
If you run the program multiple times in testing or with dfferent files, make sure to empty out the data before each run. 
## Libraries Used:
* sqlite3
* re
## Linux commands to unlock your database:
Why because when we open the database in DB Browser for sqlite you will get an error like this "Could not open database file.Reason: database is locked".If you are using Linux Os/MacOs the process forsolving this error is similar.I'm using LinuxOs.

I got the database file name is ``emaildb.sqlite``

Run the following command::

`$ fuse emaildb.sqlite`

then you will get the result something similar to this:

`/home/ak/Pictures/python_db_coursera/emaildb/emaildb.sqlite:  7167`

then,

`kill -9 7167`

Great!!! You are unlocked your DB :)



    
