# GET NEXT LINE

Project that introduced to me static variables 🦾

## About

```
This is a function that takes fd to the file as an input and outputs the line of text till '\n' or '\0' character.

If there are no such characters left, it returns NULL.

In case of error it also returns NULL.
```

## Bonus

It's a developed version of the same thing. 

Using this version you are able to read from a different fd per call without losing the reading thread of each file descriptor or returning a line from another fd.

## USAGE

`make` to compile mandatory part

`make bonus` to compile bonus version

`make clean` to remove object files

`make fclean` to remove *.o + 
