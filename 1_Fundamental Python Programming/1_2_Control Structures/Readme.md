# Control Structures in HTML

## Conditional Statements

*There are only if-elif-else control structures in Python*

**Switch cases are not present in Python**

**Challenge: If you are reading this, try to create a module and a header file for Python that uses If-else statements to create a switch like statement.** :wink:

if-elif-else statement use **offside rule**
```
All keywords in Python use offside rule rather than braces {} for block of codes.
After keyword, use colon (:) and from next line write all statements indented by a tab for illustration of block of code
```

**Syntax:**
```python
if(<condition resulting in True/False boolean>):
	...
	...
	...
elif(<condition resulting in True/False boolean>):
	...
	...
	...
elif(<condition resulting in True/False boolean>):
	...
	...
	...
elif(<condition resulting in True/False boolean>):
	...
	...
	...
...
else:
	...
	...
	...
```

## Looping Statements
**In python, only entry controlled looping structures while and for loop are used.**

### For Loop
**Syntax:**
```python
for <iteration variable> in <string/tuple>:
	...
	...
	...
```
*For loop with range*
```python
for <iteration variable> in range (start(inclusive),end(exclusive),jump):
	...
	...
	...
```
### While loop
**Syntax:**
```python
while(condition):
	...
	...
	...
```

## Keywords used in looping

1. break
	* break keyword is used to get out of a looping structure if condition is met.
2. continue
	* continue keywod is used to get to the next increment and ignoring the current increment.
3. pass
	* pass keyword is used when a block of code is needed but it does not have any syntax currently.
