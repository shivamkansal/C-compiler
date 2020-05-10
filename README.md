# C-compiler

Lexical Analysis
lex prog.l
cc lex.yy.c -ll
./a.out
cat output_file.txt

Syntax & Semantic Analysis
lex prog.l
yacc prog.y
cc y.tab.c -ll -ly
./a.out < test1.c
cat output.txt
