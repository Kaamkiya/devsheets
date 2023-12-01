# Contributing

### Making an issue

Please browse open issues and do not create duplicates. 

Make sure to use the appropriate issue template!

### Making a Pull Request

If you are planning on adding a new language to the repo, please...

1. Make sure there is no open PR aiming to do what you are doing
   Please double-check that none of the open PRs is adding the same language as you are
2. Double-check all names, types, programs, etc
3. Follow the style guide

### Styleguide

Use only HTML tags, and only the following:

* `<h1>`
* `<h4>`
* `<pre>`

Please avoid using Markdown, but do put your code in a `.md` file. 

##### Structure

Your explanation should look something like the following:

> [!NOTE]
> I use many different languages thoughout this sample. Please don't do the same.

```
<h1>Language Name</h1>

<h4>If every program must start with something specific (i.e. `package main`), put it here</h4>

<h4>Import statements (if applicable)</h4>

<pre>
import numpy
</pre>

<h4>Types</h4>

<pre>
Here, you put a list of all of the types the language has. Rust, for example, would be:

u8      i8             bool    str    char
u16     i16
u32     i32     f32
u64     i64     f64
u128    i128
</pre>

Please do put it in a table format.

<h4>Assignment</h4>

Here, you put how to assign variables

<pre>
<datatype> <varName> = <value> // **always** give a templated version

float64 pi = 3.1415926535 // and then a normal example

</pre>

<h4>Basics</h4>

Here goes an explanation of the entry point (if applicable) (i.e., func main)

<pre>
fn main() {
}
</pre>

Input/output

Here, you explain how input and output work. For example:

<pre>
print("Explanation of output\n");
input("Explanation of input")
<pre>

Math

How does math work? Example:

<pre>
(+ 3 4)       ; 7
(- 10 4)      ; 6
(/ 7 63)      ; 9
(* 4 6)       ; 24
(+ 7 (- 6 3)) ; 13
<pre>

If/else

How does control flow work? Use an example of if/else-if/else.

<pre>
if (condition1) {
  std::cout << "Condition 1 is true.\n";
} else if (condition2) {
  // ...
} else {
  // ...
}
</pre>

Loops

How does looping work?

<pre>
for (let i = 0; i < 100; i++) {
  console.log(i);
}

let t = true;
let j = 0;
while (t) {
  console.log(j);

  if (j == 10) {
    break;
  }
}
</pre>

Functions

A short explanation of functions goes here

<pre>
def factorial(n)
  if n < 2
    return 1
  end
  return n * factorial(n - 1)
end
<pre>
```

And that's it for the style guide. 
