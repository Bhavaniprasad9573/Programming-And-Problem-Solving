
# Problem Solvig And Programming

### 5th Day
 
### 8th May 2019

### Day Objectives
1. Objective 1
2. Objective 2
3. Objective 3



### Problem 1 :
#### Problem Statement
For a given number, define a function to check it it is divisible by 2 and 3 but not 4
#### Constraints

#### Test Cases
* Check Divisibility(6) --> True
* Check Divisibity(16) --> False
* Check Divisibility(20) -->False


```python
def checkdivisibility(n):
    if(n % 2 == 0 and n % 3 ==0 and n % 4 != 0):
        return True
    else:
        return False
checkdivisibility(6)

```




    True




```python

```
