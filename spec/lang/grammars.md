# Chapter 2. Grammars
This chapter describes the context-free grammars used in this spec to define the syntactical structure of an Alana program.

## 2.1. Context-Free Grammars
A context-free grammar is defined by a number of production rules, a set of non-terminals, a set of terminals (tokens) and the start non-terminal. 

Each production rule has a non-terminal on its left-side and a sequence of terminals and non-terminals on its right-side. They specify by what sequence a given non-terminal can be substituted for.

We say that string w belongs to the language given by the grammar G (L(G)) if and only if by starting with the initial symbol, we can use the production rules to generate w.

Context-free grammars are important in programming languages because they allow to define their syntax and, in consequence, check which programs are syntactically valid ones and which ones are not. 

## 2.2. Attribute grammars
An attribute grammar is a formal way to add semantic information to a context-free grammar by inserting attributes in non-terminals and tokens and semantic rules to the production rules.

Attribute grammars are important in programming languages because they allow to define their semantics and, in consequence, check which programs are semantically valid ones and which ones are not.

## 2.3. Lexical structure 
The lexical structure for the Alana programming language is given in <<>>. This specification has as its terminal symbols the Unicode characters. It defines a set of productions, starting from the goal symbol Input, that describe how sequences of Unicode characters are translated into a sequence of tokens.

The tokens don't include white space and comments, which are discarded for not being used in the Alana programming language. These tokens are the identifiers, the keywords, the literals, the separators and the operators of the Alana programming language. 

## 2.4. Syntactical structure
The syntactical structure for the Alana programming language is given in <<>>. This specification is written in Extended Backus-Naur Form (EBNF). It defines the sequence of tokens that form syntactically correct Alana programs.  