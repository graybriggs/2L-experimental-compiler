# 2nd Language Compiler (Experimental)

An ongoing extension to the language and compiler presented in the respository "optimizing-compiler"

Lanaguage extensions

A full static typing system

	- Int an_int;
	- Real a_real;
	- String a_string;
	- Bool a_bool;

String implementation
	
	- String str = "This is a string";

String operations

	- str = str ~ " with another string concatenated using the tidle concatenation operator."

A print to output method to view variable values at the user console.
	
	- Print(str);

Ability to abstract data types using a record keyword
	
	- rectord Rectangle {
	-   Int x;
	-   Int y;
	-   Int w;
	-   Int h;
	- }


# Garbage Collection
	
All local primitive types are allocated onto the stack. All global primitives and  global and local records are heap allocated. This heap allocation requres a memory manager. The implementation of a garbage collector is the basis for this management.

