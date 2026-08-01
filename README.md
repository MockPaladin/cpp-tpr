# cpp-tpr
A transpiler from a (currently) unknown language to C++, written in Rust.
#### Current goal:
Create the following:
[ Source Code ] -> ( Lexer & Parser ) -> [ Source AST ] -> ( Transformer ) -> [ Target AST ] -> ( Code Generator ) -> [ C++ Code ]