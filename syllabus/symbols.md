## Symbols in Common Lisp
> special values that can point to other values
> keywords are denoted by a leading colon ( : )

_for keywords &rarr; point to themselves_
* When symbols are evaluated by Lisp &rarr; they are replaced with the values they point to
```Lisp
foo  ; => <whatever-foo-points-to>
:foo ; => :FOO (is a keyword)
```
### Quoting
* the addition of **'** before an S-expression &rarr; tells Lisp to not evaluate that expression
_if FOO has not been defined anywhere in our program:_
``` Lisp
foo  ; => <ERROR! Lisp doesn't know what foo points to!>
'foo ; => FOO
```
