# C - Sorting algorithms & Big O

## Helper Files
* print_array.c: C function that prints an array of integers. Provided by Holberton School.
* print_list.c: C function that prints a listint_t doubly-linked list. Provided by Holberton School.
## Header Files 📁
* sort.h: Header file containing definitions and prototypes for all types and functions written for the project.
Data Structure:
```
typedef struct listint_s
{
	const int n;
	struct listint_s *prev;
	struct listint_s *next;
} listint_t;
```

Tasks 📃
0. Bubble sort

* 0-bubble_sort.c: C function that sorts an array of integers in ascending order using the Bubble Sort algorithm.
Prints the array after each swap.
* 0-O: Text file containing the best, average, and worst case time complexities of the Bubble Sort algorithm, one per line.
1. Insertion sort

* 1-insertion_sort_list.c: C function that sorts a listint_t doubly-linked list of integers in ascending order using the Insertion Sort algorithm.
* Prints the list after each swap.
* 1-O: Text file containing the best, average, and worst case time complexities of the Insertion Sort algorithm, one per line.
2. Selection sort

* 2-selection_sort.c: C function that sorts an array of integers in ascending order using the Selection Sort algorithm.
* Prints the array after each swap.
* 2-O: Text file containing the best, average, and worst case time complexities of the Selection Sort algorithm, one per line.
3. Quick sort

* 3-quick_sort.c: C function that sorts an array of integers in ascending order using the Quick Sort algorithm.
* Implements the Lomuto partition scheme.
* Always uses the last element of the partition being sorted as the pivot.
* Prints the array after each swap.
* 3-O: Text file containing the best, average, and worst case time complexities of the Quick Sort Lomuto Partition scheme algorithm, one per line.

## Authors
![GitHub Contributors Image](https://contrib.rocks/image?repo=anacardona0220/holbertonschool-higher_level_programming) Ana Maria Cardona Botero - <a href="https://github.com/anacardona0220" target="_blank"> @anacardona0220</a> :genie_woman:![Your Repository's Stats](https://github-readme-stats.vercel.app/api?username=anacardona0220&show_icons=true)
