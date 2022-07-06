## Common Lisp objects:
1. **atoms** &rarr; (single, indivisible values)
2. **conses** &rarr; (built by the construct function "cons")

## Parts of _cons_
1. **car** &rarr; the first element &rarr; represents the _function_ being called
2. **cdr** &rarr; rest of the elements &rarr; represent the _arguments_ to that function

```lisp
(<function> <arg1> <arg2> ... <argN>)
; ^ car ^  |        ^ cdr ^
```
