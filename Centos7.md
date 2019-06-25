Usefull commands in Centos7

- - -
History - view history CLI commands

If you wish to view the history one page at a time, you can use the command below. Now, you can simply use the spacebar to view one page at a time or use the down arrow to view one line at a time:

history | less
To view just the last ten commands, you can use the following:

history | tail
To view the last 25 commands, just use the following:

history 25
Another tool you can use with history is Ctrl + R. This will output a search feature. Just begin typing a command and it will complete the command with the most recent match. If it is not the one you need, simply type a few more letters until you find the command you wanted. Once you find it, simply press the return key to run or press the right arrow key to edit it.

Another way to search history is with the following command (just be sure to replace "searchterm"):

history | grep -i searchterm | less
As you can see, the history command can be very useful in finding the last commands that have been used on your (mt) Media Temple service.
