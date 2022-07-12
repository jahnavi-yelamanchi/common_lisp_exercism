## Lists in Common Lisp
> items themselves do not have to be the same type
### creating Lists
1. type in a quoted list like this: 
```lisp'(1 two "III")
```
and that will cause a list to be created and evaluated
2. functions
   1.  **list**
       1.  takes zero or more arguments
       2.  evaluates to a list created with those values
       ```lisp 
       (list 1 'two "III") ; => (1 two "III")
       ```
    2. **cons**
       1. takes two items &rarr; creates a list
       2. has as its car the first item and as its cdr the second item
       ```lisp
       (cons 1 2)            ; => (1 . 2) ;; (a list without `nil` as its `cdr` is printed in this way.)
       (cons 1 nil)          ; => (1)
       (cons 1 (cons 2 nil)) ; => (1 2)
       ```
    * **car** and **cdr** can be used to access the _car_ and _cdr__ respectively.
    * _first_ and _rest_ are synonyms of car &rarr; cdr and work exactly the same