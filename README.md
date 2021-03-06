# ZEBLog
## A ham radio logger written in python

## What is a log?
Logs should have the following elements at a minimum

1. Call sign
2. Date/Time in UTC of contact
   * Time QSO starts
   * Time QSO ends
3. Signal Report
4. Band Used
5. Mode Used
6. QTH - location
7. QSL
   * Sent?
   * Received?


## Ideas:

1. put the whole thing in docker
2. use mariadb,or posgresql for data persistence
3. write this as a flask app from the beginning.
4. actually make this all work
5. write this in python
6. inspiration: [yfklog](https://fkurz.net/ham/yfklog.html)
7. link to [LOTW](https://lotw.arrl.org/lotwuser/default)
8. use grig to get Band & Mode from transceiver
   [grig](https://aur.archlinux.org/packages/grig/)
9. Connect to QRZ.com API to pull station details

## Technologies:

1. Docker
2. Python
3. [Flask](https://flask.palletsprojects.com/en/1.1.x/)
4. [Flask-Bootstrap](https://pythonhosted.org/Flask-Bootstrap/)
5. [PeeWee3](http://docs.peewee-orm.com/en/latest/)
6. [poetry](https://python-poetry.org/)
7. [request](https://docs.python-requests.org/en/master/index.html)
8. [mariadb](https://mariadb.org/)
