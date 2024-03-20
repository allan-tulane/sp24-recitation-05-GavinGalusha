**Name:**Isaac Ratzan and Gavin Galusha


Place all written answers from `recitation-05.md` here for easier grading.


- **1b.**  
Quick sort (fixed pivot):Work = O(n^2) Span = O(nlogn)
Quick sort (random pivot): Work = O(nlogn) Span = O((logn)^2)
Tim sort: Work = O(nlogn) Span = O((logn)^2) 

- **1c.**
|    n |   qsort-fixed-pivot |   qsort-random-pivot |   tim_sort |
|------|---------------------|----------------------|------------|
|  100 |               2.014 |                0.335 |      0.005 |
|  200 |               3.041 |                0.619 |      0.005 |
|  300 |              29.732 |                1.780 |      0.014 |
|  400 |              63.996 |                3.124 |      0.010 |
|  500 |              40.055 |                1.880 |      0.010 |
|  600 |              63.984 |                2.881 |      0.011 |
|  700 |             101.320 |                3.042 |      0.013 |
|  800 |             114.145 |                8.909 |      0.031 |
|  900 |             170.877 |                3.963 |      0.028 |
| 1000 |             270.030 |                8.762 |      0.026 |
