<h1>JavaScript</h1>

<h4>Importation</h4>
<pre>
import defaultExport from "module-name";
import * as name from "module-name";
import { export1 } from "module-name";
import { export1 as alias1 } from "module-name";
import { default as alias } from "module-name";
import { export1, export2 } from "module-name";
import { export1, export2 as alias2, /* … */ } from "module-name";
import { "string name" as alias } from "module-name";
import defaultExport, { export1, /* … */ } from "module-name";
import defaultExport, * as name from "module-name";
</pre>

<h4>Types</h4>

JavaScript does not enforce strict types. All variables are of dynamic types.
<pre>
number    string    object
</pre>

<h4>Assignment</h4>
<pre>
let varName = value; // good, can be changed
const varName = value; // best, constants
var varName = value; // less recommended
varName = value; // bad

let x = 4;
const y = 6;
</pre>

<h4>Basics</h4>

Input/output
<pre>
const name = prompt("What's your name?");
alert("Hello, " + name + "!");
</pre>

Math
<pre>
3 * 6             // 18
5 / 2             // 2.5
9 ** 2            // 81
6 - 4             // 2
2 + 3             // 5
(9 + 17) * 6 / 2  // 78
</pre>

Arrays
<pre>
const arr = [value1, value2];
let things = [3, "pig", {on: true}];
</pre>

If/else
<pre>
if (condition) {
  // do something
} else if (condition2) {
  // do something else
} else {
  // do something else
}
</pre>

Loops
<pre>
for (let i = 0; i < 100; i++) {
  console.log(i);
}

let t = true;
let j = 0;
while (t) {
  console.log(j);

  if (j == 10) {
    t = false;
  }
  j++
}
</pre>

