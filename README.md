# Refcount-Compiler
A custom compiler that translates custom code called 'RefCount' into C.

## Components
- Lexer: Tokenizes RefCount source code into a stream of lexical tokens.
- Parser: Transforms token streams into an abstract syntax tree for RefCount code.
- TypeChecker: Validates RefCount program semantics and ensures type safety before code generation.
- Code Generator: Transforms RefCount abstract syntax trees into equivalent C source code.
