# A-Star-8-puzzle-Python

```
python3 astar8number.py --startrow 1 2 3 8 0 5 7 4 6 --goalrow 1 6 2 8 4 3 0 5 7
```

Code takes input of form `three elements of row 1` `three elements of row 2` `three elements of row 3` for both startrow and endrow

For example the above code solves using the algorithm for the follwing start and end states:

### Start location

| |col1|col2|col3|
|-| - | - | - |
|**row1**| 1 | 2 | 3 |
|**row2**| 8 |   | 5 |
|**row3**| 7 | 4 | 6 |

### Final State

| |col1|col2|col3|
|-| - | - | - |
|**row1**| 1 | 6 | 2 |
|**row2**| 8 | 4 | 3 |
|**row3**|  | 5 | 7 |

**The code uses msiplaced tiles as heuristic function and distance from start as g function.**
