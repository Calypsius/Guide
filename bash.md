> the syntax of positional argument - take note of double comma and curly braces - this is called a paramether expansion , and it will allows to ignore upper and lower cases when comparing the two values

```
${1,,} 
```
> EOF - end of file

```bash
#!/bin/bash

echo  What is your frst name?
read FIRST_NAME
echo What is your last name?
read LAST_NAME

echo Hello $FIRST_NAME $LAST_NAME
```