# RANDOM

```basic
100 PRINT INT(RND(0)*50) : REM RANDOM NUMBER FROM 0 TO 49

100 X = INT(RND(1)*(MAX-MIN)+MIN) : REM RANDOM NUMBER BETWEEN MIN-MAX
```

# PROTECT A BASIC PROGRAM

List the program to make sure it's in memory and enter:

```basic
B=PEEK(43)+256*PEEK(44):PRINT B
```

Write down the number and then

```basic
PRINT PEEK(B), PEEK(B+1)
```

Write down the two numbers. Now enter:

```basic
POKE B,0:POKE B+1,0
```

And `LIST`

# SUPER BLOCK LIST BASIC

```basic
10 REM FIRST LINE
20 REM SECOND LINE
```

Now enter:

```basic
FL=PEEK(45)+256*PEEK(44):PRINT FL, PEEK(FL), PEEK(FL+1)
```

Now enter:

```basic
POKE FL, PEEK(43):POKE FL+1,PEEK(44)
```
