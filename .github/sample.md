<h1>Lanaguage Name</h1>

<h4>STDIO</h4>

Explain how to print and take input. For example:
<pre>
print("Hello!")
input("What's your name?")
</pre>

<h4>Types</h4>

List all available built in types here, and explain what the are below. For example, in Rust:
<pre>
i8    u8           bool   char   str
i16   u16
i32   u32   f32
i64   u64   f64
i128  u128
</pre>

i&lt;size&gt;: 8, 16, 32, 64, 128. &lt;size&gt;-bit integer
u&lt;size&gt;: 8, 16, 32, 64, 128. &lt;size&gt;-bit unsigned integer
f&lt;size&gt;: 32, 64. &lt;size&gt;-bit floating-point number

bool: true, false
char: A single unicode character
str: string

<h4>Assignment</h4>
Explain assignment here
<pre>
int fav_number = 57;
</pre>

<h4>Lists/arrays/key-value maps</h4>
Explain arrays and key to value mapping in the language. In Go:
<pre>
var fruits = []string{"apple", "orange", "pineapple"} // maps
var englishToFrench = map[string]string {
    "hello": "bonjour",
    "bye"  : "au revoir",
    "song" : "chanson",
    "dog"  : "chien",
    "cat"  : "chat",
}
</pre>

<h4>Math</h4>
Show how math works. In Clojure:
<pre>
(- 3 4)          ; -1
(+ 6 7)          ; 13
(* 8 7)          ; 56
(/ 10 2)         ; 5
(- 100 (/ 10 2)) ; 95
</pre>

<h4>Control Flow</h4>
Explain how if/else-if/else works. In Java:

<pre>
if (condition) {
    // do something
} else if (condition2) {
    // do something else
} else {
    // do something else
}
</pre>


<h4>Loops</h4>
Explain how loops work. In JavaScript:
<pre>
for (let i = 0; i < 100; i++) {
    console.log(i);
}

let j = 0;
do {
    console.log(j);
    j++;
} while (j < 10)

const fruits = ['apple', 'pear', 'banana', 'orange'];
for (let fruit of fruits) {
    console.log(fruit)
}

let k = 10;
while (k > 0) {
    k--;
    console.log(k);
}

while (true) {
    break // also explain continue
}
</pre>

<h4>Functions</h4>
Explain functions here. In C++:
<pre>
&lt;return_type&gt; &lt;function_name&gt;(&lt;type&gt; param1, ...) {
    return // explain here
}

long factorial(int n) {
    if (n < 2) return 1;
    return factorial(n - 1)*n
}
</pre>

<h4>Classes</h4>
In Python
<pre>
class Thing:
    def __init__(self, name):
        self.name = name
    def get_name(self):
        return self.name
</pre>


<h4>More Info</h4>
A list of websites (give the full URL) with more info.

- https://devdocs.io/c/
- ...