# Heapsort

* `O(nlogn)` time.
* `O(1)` space (done in-place with no extra space).

```
heapsort(A):
    buildMaxHeap(A);
    for i = A.heap_size - 1 to 1:
        swap(A, 0, i);
        A.heap_size -= 1;
        maxHeapify(A, 0);
```
