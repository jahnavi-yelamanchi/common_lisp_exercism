## Expressions
> all lisp code is **Symbolic Expressions** (S-Expressions) &rarr; _sexprs_

* Sexpr &rarr; either an _atom_ or a _cons_
* During evaluation &rarr; sexpr &rarr; automatically return some **value** &rarr; takes the _place of the expression_

```lisp
;; Defining a new function
(defun gimme-foo () 'foo)
;; Calling the function as an S-Expression
(gimme-foo) ; => FOO
```

> defining own functions (using _defun_) &rarr; last value within the body of the _defun_ is automatically returned
