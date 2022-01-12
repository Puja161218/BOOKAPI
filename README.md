# BOOKAPI

Python: Python3
Operating System: Ubuntu 16.04 LTS

Setting up environment:
Run below command as root
$ apt update
$ apt install python3-pip
$ apt install mysql-server
$ pip3 install flask
$ pip3 install pymysql

Download the code: https://github.com/hackaholic/mstakx.git

$ cd mstakx
$ mysql -u root -p < book.sql
$ python3 book_api.py
