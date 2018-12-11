# 42__Fillit--SpaceOptimizationAlgorithm @42
if the stupid 42 filecheck says this failed one case, dont trust it, it passed, that's a valid map man.

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
