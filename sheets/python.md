<h1>Python</h1>

<h4>Standard I/O</h4>
<pre>
print # output
input # take input

print("Hello, World!") # prints Hello, World!
input("What's your favorite number?") # reads from stdin with the prompt given
</pre>

<h4>Types</h4>
<pre>
int
float
str
bool
chr
</pre>

<h4>Assignment</h4>
Declaring variables
<pre>
var_name = var_value
# OR
var_name: var_type = var_value
</pre>

<h4>Lists/tuples/dicts</h4>

<pre>
cars = ['mazda', 'honda', 'subaru', 'chevy', 'ford'] # lists are mutable
fruits = ('apple', 'orange', 'banana', 'pear') # tuples are immutable

fav_colors = {
    "Amanda": "Purple",
    "Joe":    "Green",
    "Bob":    "Blue",
    "Emily":  "Pink",
    "John":   "Red"
}
</pre>

<h4>Math</h4>
<pre>
1 + 3   # 4
7 * 9   # 63
11 / 2  # 5.5 
10 / 5  # 2.0 division always returns a float
5 % 2   # 1
63 - 54 # 9
(1 * (2 - 3)) # -1
</pre>

<h4>Control flow</h4>
<pre>
if &lt;condition&gt;:
    # do something
elif &lt;condition2&gt;:
    # do something else
else:
    # do something else
</pre>

<h4>Loops</h4>
<pre>
for i in range(10):
    print(i, end=',')

#=> 1,2,3,4,5,6,7,8,9,

i = 4
while True:
    print(i)
    i += 1
    if i > 100:
        break # exit the loop if i > 100
#=> 4
#=> 5
#=> 6
#=> ...
#=> 100
</pre>

<h4>Functions</h4>
<pre>
def &lt;function_name&gt;(&lt;params&gt;):
    # do stuff
    return return_value

def say_hello(name):
    print("Hello, " + name + "!")

def add(x, y):
    return a + b

# Calling a function
say_hello("Julia")
n = add(6, 7)
print("6+7 =", n)
</pre>

<h4>Classes</h4>
<pre>
class Thing:
    def __init__(self, name):
        self.name = name
    def get_name(self):
        return self.name
</pre>

<h4>More info</h4>
- https://inventwithpython.com/
- https://python.org/
- https://docs.python.org/3/
