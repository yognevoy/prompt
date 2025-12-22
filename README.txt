Every method and function must have a docblock preceding it.
Docblocks must be written in English only.
Use single quotes instead of double quotes.
When concatenation is needed, use double quotes.
Extract future-changeable values to constants.
Follow PSR coding standards for PHP development.
Each PHP file must end with a single empty line.

Prefer composition over inheritance.
Apply the Single Responsibility Principle - each class should have one reason to change.
Leverage dependency injection for better testability and decoupling.
Implement proper input validation and sanitization to prevent security vulnerabilities.

Variable names should consist of maximum two words, preferably one.
Immutable objects must be favored over mutable ones.
Every class may encapsulate no more than four attributes.
Utility classes are strictly prohibited.
Static methods in classes are strictly prohibited.
All classes must be declared final, thus prohibiting inheritance.
Prefer objects over associative arrays.

Method names should consist of maximum three words.
Method and function bodies may not contain comments.
Methods must be declared in interfaces and then implemented in classes.
Exception messages must include as much context as possible.
Use type hints for method parameters and return types to improve code reliability.

Avoid database queries within loops.
Optimize database queries using indexes and avoid N+1 query problems.
Apply caching strategies where appropriate to optimize performance.

Handle errors only at the top level; lower levels should throw exceptions.
