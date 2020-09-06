Write a program to compute:

f(n)=f(n-1)+100 when n>0
and f(0)=0
with a given n input by console (n>0).

Example: If the following n is given as input to the program:

5
Then, the output of the program should be:

500
In case of input data being supplied to the question, it should be assumed to be a console input.

Hints
We can define recursive function in Python.

```
def fun(n):
    if n == 0:
        return 0
    else:
        return fun(n-1)+100
```

---

The Fibonacci Sequence is computed based on the following formula:

f(n)=0 if n=0
f(n)=1 if n=1
f(n)=f(n-1)+f(n-2) if n>1
Please write a program to compute the value of f(n) with a given n input by console.

Example: If the following n is given as input to the program:

7
Then, the output of the program should be:

13
In case of input data being supplied to the question, it should be assumed to be a console input.

Hints
We can define recursive function in Python.

```
def fibo(n):
    if n == 0:
        return 0
    elif n == 1:
        return 1
    else:
        return fibo(n-1) + fibo(n-2)
```

---

The Fibonacci Sequence is computed based on the following formula:

f(n)=0 if n=0
f(n)=1 if n=1
f(n)=f(n-1)+f(n-2) if n>1
Please write a program to compute the value of f(n) with a given n input by console.

Example: If the following n is given as input to the program:

7
Then, the output of the program should be:

0,1,1,2,3,5,8,13
In case of input data being supplied to the question, it should be assumed to be a console input.

Hints
We can define recursive function in Python. Use list comprehension to generate a list from an existing list. Use string.join() to join a list of strings.

```
def fibo(n):
    if n == 0:
        return 0
    elif n == 1:
        return 1
    else:
        return fibo(n-1) + fibo(n-2)

n = int(input())+1
print(','.join([str(fibo(x)) for x in range(0,n]))

```
---

