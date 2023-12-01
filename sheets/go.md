<h1>Go</h1>

<h4>Every Go program starts with the following line:</h4>

<pre>package &lt;packageName&gt;</pre>

if it's the main file, then

<pre>package main</pre>

<h4>Import statements</h4>

<pre>
import (
  "package1"
  "package2"
)
</pre>

<h4>Types</h4>

<pre>
float32, float64
uint, uint8, uint16, uint32, uint64
int, int8, int16, int32, int64
string
rune
</pre>

<h4>Assignment</h4>

<pre>
&lt;type&gt; &lt;variable&gt; = &lt;value&gt;

float64 pi = 3.14159265

// type inference
tau := 6.282
</pre>

<h4>Basics</h4>

Program starts at the main function

<pre>
func main() {
  // ...
}
</pre>

Input/Output

<pre>
fmt.Println("To be printed") // must import "fmt"

var t string
fmt.Scan(&t)
</pre>

Math 

<pre>
3 * 3       // 9
4 % 2       // 0
6 + 8 / 2   // 10
(9 + 8) * 2 // 34
</pre>

If/else:

<pre>
if condition {
  // do something
} else if condition2 {
  // do something else
} else {
  // otherwise
}
</pre>

Loops:

<pre>
// Go has no while loops
for start; condition; post {
  // ...
}

for i := 0; i < 100; i++ {
  fmt.Println(i)
}

// this is the closest to a while loop
for condition {
  // ...
}
</pre>

Functions:

<pre>
func functionName(param1 param1type, param2, param2type) returnType {
  // ...

  return // whatever
}
</pre>
