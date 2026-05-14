# JavaScript Basics — Lecture 1 Practice

In Lecture 1, I learned that JavaScript is dynamically typed and relies heavily on type coercion, especially with operators like `+` and `==`. I also learned the importance of using strict equality (`===`) to avoid unexpected behavior.

### Key takeaways
- JavaScript has dynamic typing and performs type coercion
- `null` and `undefined` represent different kinds of "nothing"
- The REPL (run using `node`) is useful for testing expressions quickly
- Always prefer `===` over `==` to avoid coercion bugs
- Floating point arithmetic can produce precision errors like `0.1 + 0.2`

I used the Node.js REPL with `node` to experiment with JavaScript expressions involving coercion, numbers, and special values.

I tested the following expressions:

```javascript
typeof null
0.1 + 0.2
[] == false
5 / 0
0 / 0
`I ran ${1 + 3}`
```
```
"object"
0.30000000000000004
true
Infinity
NaN
"I ran 4"
```
