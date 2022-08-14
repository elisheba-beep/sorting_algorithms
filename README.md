# sorting algorithms and big O in C

## Big O Notation
The big O notation simply represents or describes the speed or complexity of an algorithm. 
#### Some examples are:
- O(n) => Simple search
- O(n2) => Selection sort
- O(log n) => Binary search
- O(n * log n) => Quick sort
- O(n!) => Travelling salesman

### How to Select a Sorting Algorithm
- Few items => Insertion sort
- Almost completely sorted => Insertion sort
- Worst-case scenarios => Heap sort
- Average-case scenarios => Quick sort
- Dense environment items => Bucket sort
- Little code => Insertion sort

### Sorting Algorithm Stability
A sorting algorithm is stable when 2 objects with the same keys appear in the same order in the sorted output as the appear in the unsorted input array.


## Project Attributes
- Allowed editors: vi, vim, emacs
- All files are compiled on Ubuntu 20.04 LTS using gcc, using the options -Wall -Werror -Wextra -pedantic -std=gnu89
- All files end with a new line
- The code uses the Betty style. It can be checked using betty-style.pl and betty-doc.pl
- The prototypes of all the functions are included in the header file called sort.h
- All header files are include guarded
- A list/array is not sorted if its size is less than 2.