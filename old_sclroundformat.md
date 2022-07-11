# Scl, round, format

##  Scl 
```
$ pil
: *Scl
-> 0
: 123.45
-> 123
: 67.890
-> 68
: (setq *Scl 3)
-> 3
: 123.5678
-> 123568
: 123.4321
-> 123432
: 7
-> 7
: 500.7
-> 500700
: (setq y 567.78)
-> 567780
: (prin y)
567780-> 567780
: (prin (* y y))
322374128400-> 322374128400
```
## round and format functions
```
: (round 1234 3)
-> "1.234"
: (round 1234)
-> "1.234"
: (round 12345678 5)
-> "12,345.678"
: (format 123679)
-> "123679"
: (format 1236554 *Scl)
-> "1236.554"
: (format 4566343789 6)
-> "4566.343789"
```