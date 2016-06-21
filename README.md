# KmnDrawings
Dedicated to Zarankiewicz's conjecture

I prepare a publication about some progress in Zarankiewicz's conjecture.
This project is intended to support the publication by sourcecodes, Windows binaries, datasets, and documentation.


## KmnDrawings #
The program KmnDrawings takes a drawing of K(m, n) and generates drawings of K(m+1, n) by adding a node. The area to place the new node, its cyclic ordering and the maximum number of additional crossings must be specified.

The program works interactively. It takes some commands from `stdin` and gives it output on `stdout`. But using it manually is quite cumbersome. A Python unit *Drawings* is available for a convenient use in Python scripts.

## ZC7
The program ZC7 is used to enumerate (m,7)-sets in canonical order, where the size m and the maximum antisum is given. In the current version, all parameters must be changed in the source ZC7.c and then the program must be recompiled. Some compiler switches are prepared to control the program behaviour.
