#Kaleidoscope Language#

Following along with two different tutorials 
- OCaml
- Haskell

##Example of the Language##

[fibonacci.k](https://github.com/mrecachinas/Kaleidoscope-Language/fibonacci.k)
```
# compute nth fibonacci number
def fib(x)
    if x < 3 then
        1
    else
        fib(x-1) + fib(x-2)
# compute nth fibonacci
fib(5)
fib(6)
fib(20)
```
