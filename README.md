# [Patika.dev](https://www.patika.dev/) Binary Search Tree Project

**[7,5,1,8,3,6,0,9,4,2]**

Write the steps of the array given above according to the **binary search tree**.

*Step 1* : First, root is determined. For this array, root is 7.
>       7

*Step 2* : Then, read the next element; if it is less than the root, insert it to the left of the root. If it's not, insert it to the right of the root and move on to the next element. **5<7**. So, 5 should be to the left of 7.
>       7 
>      / 
>     5

*Step 3* : **1<7**, **1<5**. 1 should be to the left of 7 and 5.
>         7
>        /
>       5
>      /
>     1

*Step 4* : **8>7**. 8 should be to the right of 7.
>         7
>        / \
>       5   8
>      /
>     1

*Step 5* : **3<7**, **3<5**, **3>1**. 3 should be to the left of 7 and 5 but to the right of 1.
>         7
>        / \
>       5   8
>      /
>     1
>      \
>       3

*Step 6* : **6<7**, **6>5**. 6 should be to the left of 7 but to the right of 5.
>         7
>        / \
>       5   8
>      / \
>     1   6
>      \
>       3

*Step 7* : **0<7**, **0<5**, **0<1**. 0 should be to the left of 7, 5 and 1.
>           7
>          / \
>         5   8
>        / \
>       1   6
>      / \
>     0   3

*Step 8* : **9>7**, **9>8**. 9 should be to the right of 7 and 8.
>           7
>          / \
>         5   8
>        / \   \
>       1   6   9
>      / \
>     0   3

*Step 9* : **4<7**, **4<5**, **4>1**, **4>3**. 4 should be to the left of 7 and 5 but to right of 1 and 3.
>           7
>          / \
>         5   8
>        / \   \
>       1   6   9
>      / \
>     0   3
>          \
>           4

*Step 10*: **2<7**, **2<5**, **2>1**, **2<3**. 2 should be to the left of 7, 5 and 3 but to the right of 1. Now, the creation of binary search tree is completed.
>           7
>          / \
>         5   8
>        / \   \
>       1   6   9
>      / \
>     0   3
>        / \
>       2   4

