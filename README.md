## Summary

* An example that I use for experimentation, esp. re: concurrency.
* Given that `10! = 7! x 6!`, find other integers, `a,b,c` such that:
    - `a! = b! x c!`
    - Note there are trivial cases, which are not interesting but good sanity checks:
        - if `a = c!`, then `a! = (a-1)! x c!`
        - e.g. `24! = 23! x 4!`
* I typically avoid using `BigInt` or other assists.
    - That said, the data structures and algorithms are faily simplistic. 
