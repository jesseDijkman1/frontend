# You Don't Know JS: Scope & Closures

## Chapter 1: What is Scope?

Most programming languages have the ability to store values in variables and retrieve those values. This gives the program state 

> A program is described as stateful if it is designed to remember preceding events or user interactions 
> 
> - https://en.wikipedia.org/wiki/State_(computer_science)

Javascript is a compiled language. 

Traditional compiled-language will undergo **three** steps before it is executed: 

  1. **Tokenizing/Lexing**
   Breaking up a string of characters into meaningful chunks, called **tokens**.  ``` var a = 2;``` becomes ``` var```, ``` a```, ``` =```, ``` 2```, ``` ;```.

> The difference between tokenizing and lexing is subtle and academic, but it centers on whether or not these tokens are identified in a stateless or stateful way. 

  2. **Parsing** 
   
