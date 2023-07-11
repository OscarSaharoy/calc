# calc

This is a simple script that you can put somewhere on your path; 
it allows you to evaluate quick maths expressions from the
command line.

It is a wrapper around python and imports the contents of the
`math` module so you can use everything in there easily.

Here are some example uses:

```
$ calc 2 + 2
4
$ calc 7 % 3
1
$ calc "3 ** 4"
81
$ calc "sin( pi/2 )"
1.0
$ calc "1j * 2j"
(-2+0j)
```

The only condition is that you need to quote your mathematical 
expression if it includes special characters like `*`, `(` or `/`
(or you can escape them eg `calc 7 \* 7`).

