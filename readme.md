<h1 align="center"><a href="https://cmcarey.github.io/S-Algol/">S-Algol Compiler</a></h1>

A compiler for the S-Algol programming language.

Built for my [BSc thesis](./report.pdf).

- Grammar was converted to LL-1 context free form, and a parser generated was built to take this form and create a fully typed Typescript parser
- Analysis is performed according to S-Algol type rules
- Code generation targets Javascript
- A web IDE is provided replete with syntax highlighting editor and REPL environment for running S-Algol programs and viewing text and vector output

<a href="https://cmcarey.github.io/S-Algol/"><img src="./assets/screenshot.png" /></a>