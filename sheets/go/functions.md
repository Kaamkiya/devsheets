<h1>Function in Go</h1>

<h4>Creating a function</h4>

The generic syntax is like the following:
<pre>
func functionName(arg1 arg1Type, arg2 arg2Type, arg3 arg2Type) returnType {
    function body
}
</pre>

Here are some examples:
<pre>
func sayHello(name string) {
    fmt.Println("Hello, " + name);
}

// we only write int once because both parameters are of that type
func add(a, b int) int {
    return a + b
}

func sumAndProduct(a int, b int) (sum int, product int) {
    sum := a + b
    product := a * b
    return sum, product
}
</pre>

<h4>Calling a function</h4>
We call a function like the following:
<pre>
add(10, 9)
sumAndProduct(9, 4)
&lt;functionName&gt;(&lt;parameters&gt;)
</pre>