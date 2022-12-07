# Advent Of Code 2022

* [Day 1](Day01.ipynb). File reading and simple list manipulation.

* [Day 2](Day02.ipynb). Dictionaries for a Rock-Paper-Scissor game.

* [Day 3](Day03.ipynb). String manipulation and search. Initially using `Counter` and `&` of dictionaries for efficient search of common items, then moved to `set`'s since they are the most natural tool for intersection search.

* [Day 4](Day04.ipynb). Interval overlaps. Quick solution checking extremes.

* [Day 5](Day05.ipynb). The hardest part was parsing the input (done in a very not elegant way :-) I could do much better if I only knew how to really use `regex`). Solutions were variations of list chopping and reassembling.

* [Day 6](Day06.ipynb). String chopping and sets.

* [Day 7](Day07.ipynb). First day presenting some challenge. Parsing the commands to browse the filesystem was not too complicated, structure saved in dictionary of dictionaries (for directories) and integers (for file sizes). Part 1 solved with recursion, Part 2 was quite easy since I was already saving the sizes of all directories.
