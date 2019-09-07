# About

A Tetriminos is a 4-blocks geometric ﬁgure that most of you might knows thanks to the popular game Tetris.
The goal of this project is to arrange the Tetriminos among themselves to make the smallest possible square.
The Tetriminos are ordered as they appear in the input file. Among the different solutions possible to make the smallest square, only the solution where Tetriminos is placed on
their most upper-left position, will be accepted.

# Usage

Run `make` to compile an executable called `fillit`. Then run the program with your input file: `./fillit [file]`.

# Example 
```
$> cat sample.fillit | cat -e
...#$
...#$
...#$
...#$
$
....$
....$
....$
####$
$
.###$
...#$
....$
....$
$
....$
..##$
.##.$
....$
$
....$
.##.$
.##.$
....$
$
....$
....$
##..$
.##.$
$
##..$
.#..$
.#..$
....$
$
....$
###.$
.#..$
....$

$> ./fillit sample.fillit | cat -e
ABBBB.$
ACCCEE$
AFFCEE$
A.FFGG$
HHHDDG$
.HDD.G$
```
