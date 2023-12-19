# Advent_Of_Code_2023
https://adventofcode.com/2023

This is quite challenging and fun as it requires me to think and use tools & methods that I do not necessarily possess yet. Through the exercise I learn a lot and expanded my problem solving and python programming skills. Win-win!


Day 1: Trebuchet - COMPLETED

Day 2: Cube Conundrum - COMPLETED

Day 3: Gear Ratios - Not Started

Day 4: Scratchcards - COMPLETED

Day 5: If You Give A Seed A Fertilizer - Completed Part 1, Part 2 is off...

Day 6: Wait For It - COMPLETED
quadratic equation, no you don't need to go nuts over it, see the pattern and code for the pattern. Woah! Repeatable in Part 2!

Day 7: Camel Cards - Part 1 stuck = must write the sort for each card in the draw.

Day 8: Haunted Wasteland - COMPLETED
While I understand Part 1 problem, I do not know the tools for to keep on iterating:
from this, I learned to use itertools -> cycle
For Part 2: I need to use math -> lcm. lcm is only available after python 3.9 so must upgrade python.

Day 9: Mirage Maintenance - COMPLETED
Learned python all() and any().

Day 10: Pipe Maze

Day 11: Cosmic Expansion - Solved Part 1. Part 2 get right answer on sample data but wrong answer for actual data.. Why?
Learned a lot of numpy. It's really useful! Find the cheat sheet.
https://images.datacamp.com/image/upload/v1676302459/Marketing/Blog/Numpy_Cheat_Sheet.pdf


Day 12: Hot Springs

Day 13: Point of Incidence
Really learn about numpy
Learn about np.array_equal where a 2D array that has been converted to base 10 integers can be compared row by row or column by column.
use zip reverse

Day 14: Parabolic Reflector Dish

Day 15: Lens Library

Day 16: The Floor Will Be Lava



## My learning
I like using: for i in range(start, stop, step):
for index, value enumerate(xxxx):

convert complex number to real number to int: int(<var>.real)

find all the digits in a string and join them as one integer: <var> = int(''.join(filter(str.isdigit, lines[0])))
