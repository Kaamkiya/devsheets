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

<h4>Standard i/o</h4>
<pre>
fmt.Println("To be printed") // must import "fmt"

var t string
fmt.Scan(&t)
</pre>

<h4>Types</h4>

<pre>
uint      int                 bool    string    rune
uint8     int8
uint16    int16
uint32    int32    float32
uint64    int64    float64
</pre>

<h4>Assignment</h4>

<pre>
&lt;type&gt; &lt;variable&gt; = &lt;value&gt;

float64 pi = 3.14159265

// type inference
tau := 6.282
</pre>

<h4>Math</h4> 
<pre>
3 * 3       // 9
4 % 2       // 0
6 + 8 / 2   // 10
(9 + 8) * 2 // 34
</pre>

<h4>If/else:</h4>
<pre>
if condition {
  // do something
} else if condition2 {
  // do something else
} else {
  // otherwise
}
</pre>

<h4>Loops:</h4>
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

<h4>Functions:</h4>
<pre>
func functionName(param1 param1type, param2, param2type) returnType {
  // ...

  return // whatever
}
</pre>
