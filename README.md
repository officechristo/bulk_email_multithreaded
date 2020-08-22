# Python Threaded E-mail sender #

This is a simple implementation for thread based mailing using SMTP and MySQL

### Setting Up ###

* $ git clone https://github.com/officechristo/bulk_email_multithreaded.git
* $ cd python-threaded-mailer
* $ mysql -u <username> -p < table.sql
* Configure mailer.py and populate_table.py
* $ python populate_table.py
* $ python mailer.py
* Dependencies: MySQL, MySQLdb, smtplib