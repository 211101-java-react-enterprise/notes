# Functional Programming

In **functional programming**, programs are executed by evaluating expressions, in contrast with [imperative programming](./imperative-programming.md) where programs are composed of statements which change global state when executed. Functional programming typically avoids using mutable state.

Functional programming requires that functions are *first-class*, which means that they are treated like any other values and can be passed as arguments to other functions or be returned as a result of a function. Being first-class also means that it is possible to define and manipulate functions from within other functions. Special attention needs to be given to functions that reference local variables from their scope. If such a function escapes their block after being returned from it, the local variables must be retained in memory, as they might be needed later when the function is called. Often it is difficult to determine when those resources can be released, so it is necessary to use *automatic memory management*.

### References

*Functional programming.* HaskellWiki. (n.d.). Retrieved from https://wiki.haskell.org/Functional_programming. 
