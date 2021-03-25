# js-iterators

Ruby style iterators in JS

```js

[...1.._10];              // [1, 2, 3, 4, 5, 6, 7, 8, 9]
[...1.._-10];             // [1, 0, -1, -2, ..., -9]
[...Math.PI..9];          // [3.141592653589793, 4.141592653589793, 5.141592653589793, 6.141592653589793, 7.141592653589793, 8.141592653589793]
[...(-1e3)._1e3];         // [-1000, -999, ..., 998, 999]
[...1e3._2e3];            // [1000, 1001, ..., 1999]
[...1..$10];              // [1, 2, 3, 4, 5, 6, 7, 8, 9, 10]
[...1..__1_213e3];        // [1, 0, -1, ..., -1213]
[...1..__1_213e_3];       // [1, 0]

for( let i of 1.._10 ) {
  console.log(i+1);       // 2, 3, 4, ..., 10
}

Array.from(1..$10);       // [1, 2, 3, 4, 5, 6, 7, 8, 9, 10]

[...(-10)._$10];          // [-10, -9, ..., 9, 10]
[...4..times];            // [0, 1, 2, 3]
[...5.upto(10)];          // [5, 6, 7, 8, 9, 10]
[...10.downto(5)];        // [10, 9, 8, 7, 6, 5]
[...4.step(10,2)];        // [4, 6, 8, 10]

```

# get

```console
$ npm i --save js-iterators@latest
```

# contribute

PRs only thanks! :)

# why not just use Ruby?

I'm on web

# why not use this other library?

Syntax

# why this?

Cool
