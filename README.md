# ZEBLog
## A ham radio logger written in python

## What is a log?
Logs should have the following elements at a minimum

1. Call sign
2. Date/Time in UTC of contact
..1. Time QSO starts
..2. Time QSO ends
3. Signal Report
4. Band Used
5. Mode Used
6. QTH - location
7. QSL
..1. Sent?
..2. Received?


## Ideas:

1. put the whole thing in docker
2. use mariadb for data persistence
3. use [ncurses](https://docs.python.org/3/howto/curses.html) for a tui
4. actually make this all work
5. write this in python
6. inspiration: [yfklog](https://fkurz.net/ham/yfklog.html)
7. link to [LOTW](https://lotw.arrl.org/lotwuser/default)
8. use grig to get Band & Mode from transceiver
   [grig](https://aur.archlinux.org/packages/grig/)

