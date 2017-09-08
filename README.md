🥚 egg
===

egg is a stack-based programming language for code golf, not unlike cjam and pyth.

Properties
----------

* Programs are represented as a sequence of tokens and are evaluated left-to-right.
* Literals are pushed directly to the stack.
* Primitive types include integers (bigints) `-123`, floating-point values `3.141`, strings `"hello"`, and character literals `'a`.
* Operators pop the number of arguments they need from the top of the stack and can push output values.
* Whitespace is optional except to disambiguate token delineation.
* __TODO__: Implicit coercion between types in the number hierarchy.

Check it out [here](https://forestbelton.github.io/egg/www/).
