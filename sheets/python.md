# Python

#### Importation

<pre>
import module
import module as alias # importation with an alias
from module import * # wildcard import
from module import property # import specific thing from module
</pre>

#### Types

<pre>
int, float, str, chr, tuple, list, dict, set
</pre>

#### Assignment

<pre>
variable_name = value
# OR
variable_name: variable_type = value
</pre>

#### Basics

Input/output

<pre>
print("Print something to terminal")
input("Take input from user")
</pre>

If/else

<pre>
if condition1:
    # do something
elif condition2:
    # do something else
else:
    # otherwise
</pre>

Math

<pre>
3 + 4       # 7
12 - 5      # 7
6 * 7       # 42
9 / 3       # 3
10 // 3     # for a truncated result: 3
(6 + 8) / 2 # 7
</pre>

Loops

<pre>
for i in range(100): # for each i in 100
    print(i)

t = True
i = 0
while t:
    if i == 10:
        t = False
    i += 1
</pre>

Functions

<pre>
def function_name(param1, param2):
    # ...
    return # whatever you want to return

def add(num1: int, num2: int) -> int:
    # the `: int` is optional; it enforces strict types
    return num1 + num2

add(5, 6) # 11
</pre>
    
