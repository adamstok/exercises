Write a program that accepts a sentence and calculate the number of upper case letters and lower case letters.

Suppose the following input is supplied to the program:

Hello world!
Then, the output should be:

UPPER CASE 1
LOWER CASE 9

```
def countlu():
    sentence = input()
    u = sum([1 for x in sentence if x.isupper() == True])
    l = sum([1 for x in sentence if x.islower() == True])
    print(f'UPPER CASE {u} LOWER CASE {l}')

```