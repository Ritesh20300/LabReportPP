[Home of Lab Report](../lab.html)

# Program Ex 01: Change it

## Source file/s

```
src/.
└── main.c

0 directories, 1 file
```

---


# src/main.c

```

#include <stdio.h>
int main()
{
int i, number;
int fact=1;
printf("ME B1, Roll no= 2030075\n");
printf("Enter the value of integer: \n");
scanf("%d", &number);
for(i=1;i<=number; i++)
{
fact=fact*i;
}
printf("Factorial of %d is:%d", number , fact);
return 0;
}


```

---

## Compilation

```
xmake

[ 50%]: ccache compiling.release src/main.c
[ 75%]: linking.release Ex13
[100%]: build ok!

```

## Execution
```
xmake run

ME B1, Roll no= 2030075
Enter the value of integer: 
Factorial of 32766 is:0
```

### Known Bugs and/or Errors:

List all the known limitations / bugs and / or errors of your program.

After extensively testing your program, you should be aware of (nearly) every issue it has. How does your program handle bad input? How does your program handle edge cases? This section is a space for full-disclosure; what's wrong with your program?

### Lessons Learned:

1. What went well
1. What you would do differently next time
1. How the exercise might be revised to make it clearer/more satisfying
1. What the faculty members might have done differently to promote learning
