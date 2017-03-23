## Sort Algorithms

If you think about it, a lot of what we ask computers to do involves placing items in the correct order.  For example, if you have a recommendation system like Netflix, these recommendations have should be delivered in the correct order.  But something more basic like displaying apartment listings from their highest to lowest price also involves sorting.  

### Benefits of Sorting

In previous lessons on algorithms, we discussed certain problems become easier when our collection is sorted.  For example, if we would like to see if an array includes the number two, and our array is sorted, we know that after guessing that the number two may be at a specific index and checking, we can then determine if we need to look higher or lower.  We called this technique **binary search**.  This makes our problem easier than guessing with an unsorted array, where we have only ruled out one location where the number cannot be.

```javascript
  let sortedArray = [-1, 1, 3, 5, 6]
  array[2]
  // 3
  // so know need to look lower
  // only need to look at indices 0 and 1

  let unsortedArray = [5, 6 -1, 1, 3]
  array[2]
  // -1
  // so guess again
```

There are other operations, in addition to checking for inclusion, that become easier with a sorted array.

  * Finding the minimum of an array
  * Finding a maxiumum of an array
  * Finding the median of an array

So, now that we know some of the benefits, let's consider how we do it.

