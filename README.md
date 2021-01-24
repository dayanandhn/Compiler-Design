# Compiler-Design
steps in designing a compiler
# Symbol Table
Symbol table is an important data structure created and maintained by compilers in order to store information about the occurrence of various entities such as variable names, function names, objects, classes, interfaces, etc. Symbol table is used by both the analysis and the synthesis parts of a compiler.
* A symbol table may serve the following purposes depending upon the language in hand:
  * To store the names of all entities in a structured form at one place.
  * To verify if a variable has been declared.
  * To implement type checking, by verifying assignments and expressions in the source code are semantically correct.
  * To determine the scope of a name (scope resolution).
A symbol table is simply a table which can be either linear or a hash table. It maintains an entry for each name in the following format:
*<symbol name,  type,  attribute>
