CFLAGS="-O3 -march=native -funroll-loops -fomg-optimize -pipe -fno-plt"
Sortong algorithms comparison
|             | Quicksort   | Selection sort                      |
| :---        |    :----:   |          ---:                       |
| Worst-case  | $O(n^2)$    | $O(n^2)$ comparisons, $O(n)$ swaps  |
| Best-case   | $O(nlog(n))$| $O(n^2)$ comparisons, $O(1)$ swaps  |
| Avarage-case| $O(nlog(n))$| $O(n^2)$ comparisons, $O(n)$ swaps  |
