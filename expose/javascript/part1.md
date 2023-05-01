# Answers
<hr>

1. Line 9 will print: 
```
values added: 20
```
   
2. Upon first glance, I thought line 13 would return an error, since the variable ```result``` is out of scope, given that it was declared within the if-condition. However, since ```result``` is of type ```var```, it has function scope, meaning that it can be accessed anywhere in the function and therefore this line will print:
```
final result: 20
```
   
3. Line 9 will print: 
```
values added: 20
```

4. Like #2 alluded to, this will result in an error, since declaring a variable with the ```let``` keyword makes it block scope, so ```result``` is therefore out of scope and this will cause an error.

5. Line 9 will print an error since we are trying to assign a new value to a ```const```.

6. Line 13 would return ```final result: 0``` if not for line 7, but since there is an error before it, it will not return anything but the error.