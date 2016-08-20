# Short information

	Container for mysql client

# Description

	Sometime we need mysql client to connect to mysql server but not want to install it on our system.

	You have docker already in your system.

	This container will give you a solution without install mysql client.

	From Alpine, this container come with tiny size.

# How to run:

	docker run -t -i thanhhungqb/mysql-client

	add -v /path/to:/db and you will have directory /db to work (useful when you need import, export database)

# Available tools:
	
	mysql
	
	mysqldump

Github link: https://github.com/thanhhungqb/mysql-client

