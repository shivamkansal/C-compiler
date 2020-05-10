# C-compiler

Lexical Analysis <br>
lex prog.l   <br>
cc lex.yy.c -ll   <br>
./a.out   <br>
cat output_file.txt  <br>
<br><br>
Syntax & Semantic Analysis  <br>
lex prog.l  <br>
yacc prog.y  <br>
cc y.tab.c -ll -ly  <br>
./a.out < test1.c   <br>
cat output.txt     <br>
