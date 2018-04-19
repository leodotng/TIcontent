# Constants




## ECMASCRIPT 6
```
const PI = 3.141593
PI > 3.0
```

## ECMASCRIPT 5

```
Object.defineProperty(typeof global === "object" ? global : window, "PI", {
    value:          3.141593,
    enumerable:     true,
    writable:       false,
    configurable:   false 

})
PI > 3.0;

```