# Buso PL

Buso PL is a simple programming language interpreter. It reads code written in Buso PL and executes it. The code includes lexer and parser modules for lexical analysis and syntax analysis respectively. The code also includes an Abstract Syntax Tree (AST) module to store the parsed code in a tree-like structure.

## Getting Started

1. The program starts by including the necessary header files: "lexer.h", "parser.h" and "AST.h".
2. The lexer is initialized with a sample code written in Buso PL. The sample code assigns a string value "enes" to a variable named "isim" and prints the value of the variable.
3. The lexer reads the code and tokenizes it into a list of tokens. This process is called lexical analysis.
4. The parser then takes the list of tokens and constructs an Abstract Syntax Tree (AST) of the code. This process is called syntax analysis.
5. The program then prints the type and size of the root node of the AST.

## Requirements

This program requires C compiler to run. It also requires the lexer.h, parser.h and AST.h header files.

## Running

To run this program, you need to compile it with a C compiler. You can use the following command to compile it:

```bash
  gcc main.c -o BusoPL
```
Then you can run the compiled binary file, for example:

```bash
  ./BusoPL
```

## Contributors
- [mdenesfe](https://github.com/mdenesfe)

## Notes

- This program is just a simple interpreter for the Buso PL language and does not contain all the features of a real programming language

## Example

```bash
  var isim = "Enes";
  print(isim);

```
Output
```bash
    Enes
```