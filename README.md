# Sudoku-Validator
Validates a given set of arrays that represent a sudoku board as accurate or inaccurate

Created a sudoku validator in JS.

What is Sudoku? https://en.wikipedia.org/wiki/Sudoku

Goal of this project was to solve an algorithm problem using multiple helper functions. 

Summary: this sudoku validator takes an input (see below for sample inputs) and outputs whether the proposed input represents a valid sudoku board. Ultimately, the project needed to be broken up into several pieces to pull the sudoku boards rows, columns, and 3x3 areas. For each of these sections, they would be evaluated to see if they met the requirements of the rules of sudoku (numbers 1-9, no repeated numbers, no missing elements, all rows/columns/3x3 areas accounted for).

This project was focused on helping me improve my basics of JS by using for loops, nested loops, accurate indexing of elements within arrays, and helper functions.

let puzzle = [[ 8,9,5,   7,4,2,   1,3,6 ],
              [ 2,7,1,   9,6,3,   4,8,5 ],
              [ 4,6,3,   5,8,1,   7,9,2 ],
              [ 9,3,4,   6,1,7,   2,5,8 ],
              [ 5,1,7,   2,3,8,   9,6,4 ],
              [ 6,8,2,   4,5,9,   3,7,1 ],
              [ 1,5,9,   8,7,4,   6,2,3 ],
              [ 7,4,6,   3,2,5,   8,1,9 ],
              [ 3,2,8,   1,9,6,   5,4,7 ]];

let p8zzle = [[ 8,9,5,  7,4,2,   1,3,6 ],
              [ 8,7,1,  9,6,3,   4,8,5 ],
              [ 4,6,3,  5,8,1,   7,9,2 ],
              [ 9,3,4,  6,1,7,   2,5,8 ],
              [ 5,1,7,  2,3,8,   9,6,4 ],
              [ 6,8,2,  4,5,9,   3,7,1 ],
              [ 1,5,9,  8,7,4,   6,2,3 ],
              [ 7,4,6,  3,2,5,   8,1,9 ],
              [ 3,2,8,  1,9,6,   5,4,7 ]];
