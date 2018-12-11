# 42__Fillit--SpaceOptimizationAlgorithm @42

given input(Tetriminos) like this
```
$> cat sample.fillit | cat -e
....$
##..$
.#..$
.#..$
$
....$
####$
....$
....$
$
#...$
###.$
....$
....$
$
....$
##..$
.##.$
....$
```
produce ouput
```
$> ./fillit sample.fillit | cat -e
DDAA$
CDDA$
CCCA$
BBBB$
$>
```
using some very stupid backtracking algorithm.
Did not do any optimization on the algorithm, however, it runs fast.
Only two files.
