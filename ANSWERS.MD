### Why does FixedArrayQueue require an explicit constructor?

Because FixedArrayQueue has a fixed size. Unlike the past lab that used linkedStacks with this lab we have a capacity.

### What happens when you offer an item to a full FixedArrayQueue?

We can't add another item, once it is full because the Queue has reached its capacity, in this lab its capacity is 5.

### What happens when you poll an empty FixedArrayQueue?

It will throw java.util.NoSuchElementException. Because the Queue is at zero.

### What is the time and (extra) space complexity of each of the FixedArrayQueue methods?

- offer : O(1) as we are accessing the index in an array and array access is always O(1).
- poll : O(1) same reason as above.
- peek : O(1) same reason as above.
- isEmpty : O(1) same reason as above.
- size : O (1) same reason as above.
- asList : O(n) as iterating through each element and adding that to the list.

