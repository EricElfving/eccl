# eccl

* const by default
* `mut` to modify
* Declare variable by auto / var / let ?
* Nullable types - `opt<foo>`
  * `nil` is empty (nullopt)
  * member or 
  ``` 
       var i : opt<foo>;
       var b = i.or(23); 
  ```
  
* _ ignored
* Pipes
    * `foo | bar(4)` => `bar(foo, 4)`
    * lazy
    * null stops that pipeline, continue with next value 
* Traits instead of inheritance?
* Operator overloading
* literals:
  * integers. Decimal by default, `0b`, `0o`, `0x` prefix for others
  * char/str 
    * no difference between '' and "". 
    * Triple quote keeps whitespace
    * `r""` expands special characters (raw string)
    * `f""` formats string with variables in scope (see python)
* Pattern matching
* Lambdas
* Slices
  * Indexing 
    * like python? `[begin:end:step]` (including negative indices)
    * rust / ada? `[start..end]`
* Built-ins
  * range(start, end, step): `for x in range(2,5) { ... }`
  * types
    * array, tuple, list/vector, map
* Modules
  * file or directory (like rust)
  * public / external / internal ?
  * package management?
* Namespaces
* Binding
* RAII
  * Move by default
  * specific init / destroy methods?
* Tests?
  * Test for non-compile??
* Max recursion?
* Command-line arguments?