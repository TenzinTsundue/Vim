# Vim
Here I try to learn Vim commands and tips to make vim more capable for daily use

```
# to open vim
>>vim file.txt
```

*Quitting vim*
```
:q quit
:wq save quit
:q! quit and don’t save
```
*Navigation*
```
j down
k up
h left
l right
G end of page
gg beginning of page
} go down a block of code
{ go up a block of code
20j combination of 20 line down, can also be use with h k l
```
```
w take to the next word
W take to next space
b take to the previous word
B take to the previous space
:30 take to line 30
0 beginning of the line
^ beginning of the line with letter( same to 0w)
% take you to the closing symbol 
zz center the work space
*toggle between all the instance used 
t/ take your cursor to before /
f/ take your cursor to /
```

*Edit*
```
i insert
a insert one letter after
A inset end of the line
x deleter letter, you can use 10x to delta 10 letter
dd delete line
dt/ delete till /
u undo
^r redo
yy copy
p paste below
^p paste above
o insert a line below and put in insert mode
O insert above
c change the word ie. cw 
ct/ change till /
. previous command

V visual mode(selection) and we can add with any movement
```
```
~ swap case
r replace
```

