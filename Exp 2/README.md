# Experiment 2 — Lexical Analyzer

## Terminal session
```
sit-lab2-pc30@sit-lab2-pc30-OptiPlex-3280-AIO:~$ vim analyzer1248.l
sit-lab2-pc30@sit-lab2-pc30-OptiPlex-3280-AIO:~$ vim input1248.c
sit-lab2-pc30@sit-lab2-pc30-OptiPlex-3280-AIO:~$ lex analyzer1248.l
sit-lab2-pc30@sit-lab2-pc30-OptiPlex-3280-AIO:~$ gcc lex.yy.c -o analyzer1248
sit-lab2-pc30@sit-lab2-pc30-OptiPlex-3280-AIO:~$ ./analyzer1248 input1248.c
=== Lexical Analysis Results ===
Lines:        8
Spaces:       13
Words:        12
Keywords:     4
Identifiers: 5
Comments:     0
sit-lab2-pc30@sit-lab2-pc30-OptiPlex-3280-AIO:~$
```
