# SudokuSolver
Insert 0 as a placeholder.

### Easy
      5 2 |     6 |                       3 5 2 | 4 7 6 | 1 8 9
    1 6   | 9     |     4                 1 6 8 | 9 5 2 | 7 3 4
      4 9 | 8   3 | 6 2                   7 4 9 | 8 1 3 | 6 2 5
    ---------------------                 ---------------------
    4     |       | 8                     4 2 5 | 6 9 7 | 8 1 3
      8 3 | 2   1 | 5 9        -------->  6 8 3 | 2 4 1 | 5 9 7
        1 |       |     2                 9 7 1 | 5 3 8 | 4 6 2
    ---------------------                 ---------------------
      9 7 | 3   5 | 2 4                   8 9 7 | 3 6 5 | 2 4 1
    2     |     9 |   5 6                 2 1 4 | 7 8 9 | 3 5 6
          | 1     | 9 7                   5 3 6 | 1 2 4 | 9 7 8
Insert it as:

    052006000
    160900004
    049803620
    400000800
    083201590
    001000002
    097305240
    200009056
    000100970

### Medium
        7 | 8 6 1 |                       9 4 7 | 8 6 1 | 2 5 3
        8 |     3 |                       2 1 8 | 4 5 3 | 6 7 9
    5 6   |   9   |   1                   5 6 3 | 7 9 2 | 8 1 4
    ---------------------                 ---------------------
    1     |   7   |   8 5                 1 9 4 | 2 7 6 | 3 8 5
          | 3 4 5 |            -------->  7 8 2 | 3 4 5 | 9 6 1
    6 3   |   1   |     7                 6 3 5 | 9 1 8 | 4 2 7
    ---------------------                 ---------------------
      5   |   2   |   9 8                 3 5 6 | 1 2 4 | 7 9 8
          | 6     | 5                     4 7 1 | 6 8 9 | 5 3 2
          | 5 3 7 | 1                     8 2 9 | 5 3 7 | 1 4 6
Insert it as:

    007861000
    008003000
    560090010
    100070085
    000345000
    630010007
    050020098
    000600500
    000537100

### Hard
          | 8   1 |                       2 3 7 | 8 4 1 | 5 6 9
          |       |   4 3                 1 8 6 | 7 9 5 | 2 4 3
    5     |       |                       5 9 4 | 3 2 6 | 7 1 8
    ---------------------                 ---------------------
          |   7   | 8                     3 1 5 | 6 7 4 | 8 9 2
          |       | 1          -------->  4 6 9 | 5 8 2 | 1 3 7
      2   |   3   |                       7 2 8 | 1 3 9 | 4 5 6
    ---------------------                 ---------------------
    6     |       |   7 5                 6 4 2 | 9 1 8 | 3 7 5
        3 | 4     |                       8 5 3 | 4 6 7 | 9 2 1
          | 2     | 6                     9 7 1 | 2 5 3 | 6 8 4
Insert it as:

    000801000
    000000043
    500000000
    000070800
    000000100
    020030000
    600000075
    003400000
    000200600
