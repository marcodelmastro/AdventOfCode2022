# Advent Of Code 2022

* [Day 1](Day01.ipynb). File reading and simple list manipulation.

* [Day 2](Day02.ipynb). Dictionaries for a Rock-Paper-Scissor game.

* [Day 3](Day03.ipynb). String manipulation and search. Initially using `Counter` and `&` of dictionaries for efficient search of common items, then moved to `set`'s since they are the most natural tool for intersection search.

* [Day 4](Day04.ipynb). Interval overlaps. Quick solution checking extremes.

* [Day 5](Day05.ipynb). The hardest part was parsing the input (done in a very not elegant way :-) I could do much better if I only knew how to really use `regex`). Solutions were variations of list chopping and reassembling.

* [Day 6](Day06.ipynb). String chopping and sets.

* [Day 7](Day07.ipynb). First day presenting some challenge. Parsing the commands to browse the filesystem was not too complicated, structure saved in dictionary of dictionaries (for directories) and integers (for file sizes). Part 1 solved with recursion, Part 2 was quite easy since I was already saving the sizes of all directories.

* [Day 8](Day08.ipynb). `numpy` array slicing and manipulation.

* [Day 9](Day09.ipynb). Coordinate tracking and relative movement. Part 1 was fast, Part 2 more complicated by the fact that my initial implementation of a the head-tail relative movement was not accounting for all possibilities that can show up in a longer rope.

* [Day 10](Day10.ipynb). Another programming language! Careful cycle counts and screen drawing...

* [Day 11](Day11.ipynb). First use of a `class`. Part 2 required to use a mathematical trick not to let the worry level to explode...

* [Day 12](Day12.ipynb). Path finding on a oriented graph. Caching of already-explored paths needed to speed-up second part

* [Day 13](Day13.ipynb). Recursion for Part 1 to implement `compare` function. `functools.cmp_to_key` to use Part 1 `compare` function in standard sorting algorithm for Part 2. After initial solution, also added simple bubble sort implementation.

* [Day 14](Day14.ipynb). Sand dropping in a cave until if flows forever or it fills the hole! Representing cave walls and sand in dictionary avoids having to use large arrays of potentially unknown size (especially for Part 2)

* [Day 15](Day15.ipynb). 2D areas with Manhattan distance, with overlap and intercepts to be calculated. Using `set` works fast enouhg for Part 1, bus as expected this does not scael for Part 2, where handling overlpas in term of ranges is needed.
