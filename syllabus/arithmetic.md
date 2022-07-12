## Arithmetic in Common Lisp
> uses _prefix-notation_ instead of _infix-notation_
```lisp
;; Infix-notation (non-lisp languages)
1 + 2 + 3 + 4 + 5 ; => 15
;; Prefix-notation (lisp languages)
(+ 1 2 3 4 5)     ; => 15
```
* follows this rule &rarr; (operator operand operand)
* basic math &rarr; +, -, *, /
* remainder of division &rarr; **mod** for modulo &rarr; number and divisor as arguments
```lisp
(mod 4 2)  ; => 0
(mod 2 4)  ; => 2
(mod 10 3) ; => 1
```
### Comparing numbers
* **equal**: =
* **not equal**: /= 
* **return values**: true: T & false: NIL
```lisp
(= 1 1) ; T
(> 0 1) ; NIL
```