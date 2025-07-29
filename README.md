# Assignment-6-Medians-and-Order-Statistics-Elementary-Data-Structures

## Running Instructions

The source files need to be run in an environment using Python 3. Every implementation file will be independent and will have a test block that shows how the algorithm works or how the data structure works. Executing single files produces expected results that confirm insertions, removal, access and selection. Management of the directory in which the source files can be found and then executing each file using a command-line interface can be used to observe functionality on deterministic and randomized selection, array based and linked data structures.

## Summary of Findings

Theoretical as well as empirical efficiency was tested among selection algorithms. The median-of-medians-based, deterministic variant is fast even under worst-case input: strategic pivot choice makes it linear. Although the average performance of the randomized method is lower, variable runtime as a function of pivot distribution causes it to be quadratic in some cases. Elementary data structures such as an array, matrix, stack, queue, linked list, and tree were coded bottom up. This was found out to be true with the following analysis, that arrays are fast but offer little fluidity and that the linked structures have advantages in the aspect of dynamic growth but certain trade-offs therein exist with the speed of access. Both forms are beneficial to both stacks and queues depending on whether priority is made to the speed of access or the structural flexibility. Useful applications include scheduling and memory management, and file structures and navigation systems.
