In TestIterator.java, using an ArrayList resulted in a runtime of 6ms. When changed to a LinkedList
the runtime went up to 8ms. In the case of the TestIterator class, using an ArrayList was faster
than using the LinkedList.

In TestIterator.java, when using list.remove(Integer.valueOf(77) the test fails.

In TestList.java, using an ArrayList resulted in a runtime of 8ms. When changed to a LinkedList,
the runtime went down to 7ms. In the case of the TestList class, using a LinkedList was faster than
using the ArrayList.

The method list.remove(5), removes index 5 in the list. In the case of testRemoveObject, it would
remove 77.

The method list.remove(Integer.valueOf(5)); removes values within the list that are equal to 5.

Results of changing the SIZE and REPS in TestPerformance.java:
Size 10 = 9ms
Size 100 = 9ms
Size 1000 = 7ms
Size 10000 = 7ms
REPS 10 = 6ms
REPS 100 = 7ms
REPS 1000 = 7ms
REPS 10000 = 7ms

According to the results above, it seems that increasing the size reduces the runtime,
but increasing the reps increases the runtime.