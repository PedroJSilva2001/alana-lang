# Specification
A programming language specification is a design artefact mainly used by programming language implementors (for compilers, interpreters and transpilers). The specification should include, rid of all ambiguity, what features to implement and how a given program in that language should behave.

Sometimes "normal" users use the specification as a reference in cases where the code behaviour might not be apparent. C++ suffers from this as it is perhaps the most complex language semantics-wise and syntax-wise. Its specification has a whopping 1151 pages and is not exactly user-friendly.

On the opposite side, Rust, a complex language like C++, rather than a specification, has a reference. The difference is that C++ has many implementations (MSVC, Clang, g++, IBM C++), and Rust only has one so far (rustc). C++ needs standardization to be able to support that many platforms. Rust, however, gets away with having a reference more aimed at users because the compiler is the language's specification and the reference complies with it.

Ultimately, there should be a middle-ground where we have resources for the language implementor and the user.