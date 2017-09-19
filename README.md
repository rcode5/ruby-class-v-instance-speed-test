* Klass - uses purely class methods
* Instance - pass data to initializer then call the function on those instance variables
* Instance (with one new) - builds the instance once and repeats the method N times
* InstanceAsClass - class method calls new(*args).method

```	       
        user     system      total        real
Klass  0.130000   0.000000   0.130000 (  0.129784)
Instance  0.640000   0.000000   0.640000 (  0.641423)
Instance (with one new)  0.170000   0.000000   0.170000 (  0.172088)
InstanceAsClass  0.970000   0.000000   0.970000 (  0.971717)
```
