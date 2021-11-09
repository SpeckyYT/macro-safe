# Macro-safe

A safe way to handle macros parameters.

```spwn
import macrosafe

unsafe_macro = (a,b,c){
    $.print("{} {} {}".fmt([a,b,c]))
}

safe_macro = unsafe_macro.safe()

safe_macro(1,58,6,23,13,58,47,621,35,476,1,3,687,6,541,312)
```

Special thanks for Camila for trusting in this project already from the beginning.
