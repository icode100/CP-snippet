# CP-snippet
This is my vscode snippet for competitve programming. This consist of support for both c++ as well as python languages. Here are the keywords and their applications in vscode.

### for python
* `cp`: This pastes the basic competitve programming snippet that includes all the declaration along with fast i/o.
* `sieve`: This is the snippet for sieve of Eratosthenes algorithm
* `tree`: This keyword is for using the code for tree that consist of node definition as well as the traversals.
### for C++
* `cp`: This pastes the basic template for competitve prgramming similar to that for python. It includes all the defintion and declarations including the macros and operator overloader for taking input of vectors and sets using `std::cin`. The following are some common macros.
    * `loop(i,m,n)` => `for(int i=m;i<n;i++)`
    * `loop_r(i,m,n)` => `for(int i=m;i>n;i--)`
    * `range(v)` => `v.begin(),v.end()`
    * `range_r(v)` => `v.end(),v.begin()`
    * `IN_SEQ(container,element)` => `(find(container.begin(), container.end(), element) != container.end())` this is for checking if element is present in sequential containers like vectors and queues.
    * `IN(container,element)` => `((container).find(element) != (container).end())` this is for checking if the element is present in hash based non-sequential containers like map and set.
* `tree`: This is same as the tree keyword for python.
* `linkedlist`: This is the snippet for using linked list.
* `heapq`: Generally we have to write long line of code using max-heap in C++ hence the code snippet for min-heap and max-heap can be accesses using `MinHeap<T> myheap;` or `MaxHeap<T> myheap` replace the `T` with appropriate datatype.
* `sieve`: this is the code for Sieve of Eratosthenes but in C++.
