# installation-of-sql-map-
How to install sqlmap how to install sqlmap in termux how to install sqlmap tool in termux 

HomeEthical Hacking
How to install and use SQLMAP in Termux
IshantMay 10, 20203
How to install sqlmap in Termux

In this article, I am going to show you how to install and use SQLMAP in Termux. First of all, SQLMAP is an open-source tool that automatically detects and exploits SQL injection bugs. By doing a SQL injection attack, an attacker can take over and manipulate a database on a server.

So from that, we can steal or retrieve a database from a website that we want For example, we can retrieve website admin id and password from the database.

And if you are lucky, you can get a CC (Credit Card/credit card) for those who like carding, can dump cc here just joking ok. Don't do any illegal activity with SQLMAP.😂😂

Ok now let's get started

Things needed:
An android device with android version 5.0 or up.
Termux application: Download.
Good internet connection.
If you downloaded the Termux launch the Termux app.

First We are going to update the package list with the command:

$ apt update

Now we have to install Python with the following command:

$ apt install python python2

Wait until python is installed. After installing python we will install git. Git will help you to clone the package.


$ apt install git

After installing git we are going to clone the SQLMAP package into our directory with the help of the git command

$ git clone https://github.com/sqlmapproject/sqlmap

Wait for the process to be finished. As the process is finished now we need to enter the tool directory with the following command.

$ cd sqlmap

Now we need to give them permission to read-write and execute the SQLMAP python file by using the command:

$ chmod +x sqlmap.py

After that, you need to run the following command to run the SQLMAP

$ python2 sqlmap.py

Now SQLMAP is successfully installed on your Termux. 

If you want to run SQLMAP again next time then you need to launch the Termux then you need to enter the directory of SQLMAP by typing the following command cd sqlmap. And then you need to run the SQLMAP by using the following command python2 sqlmap.py.
