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

See [sample.md](./sample.md) for a sample cheatsheet. 

Your structure should look something like the following:

```
your-lang
    |____/cheatsheet.md
    |____/functions.md
    |____/assignment.md
    |____/loops.md
    |____/resources.md
```

For example, the structure of the Go section is like this:

```
/sheets/go
    |____/cheatsheet.md
    |____/functions.md
    |____/assignment.md
    |____/loops.md
    |____/resources.md
```