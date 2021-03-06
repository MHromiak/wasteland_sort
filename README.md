# Wasteland-sort


Wasteland sort is an O(m + n) running time sorting algorithm developed with the intention of creating a general purpose O(n) sorting algorithm.

To run the algorithm, call wasteland_sort() and pass in your array to be sorted. The sort is pseudo in-place but unstable. Any element in the array will be replaced. Currently, Wasteland sort only sorts integers, so integer representations of objects can also be sorted, though it won't be very helpful if their hashes aren't unique.

If you have questions about the algorithm, feel free to open an issue and I'll get in contact.

----------------------------------------------------------------------------------------------

To import the module, you can use the statement `import wasteland`. To directly access the file where wasteland_sort lives, use `from wasteland import wasteland_sort`.


## Example usage

```
from wasteland import wasteland_sort as ws
from typing import List, Tuple

x : List[int] = [645,111234,78,4,72,9,3344,1]
y : List[int] = [645,111234,78,4,72,9,3344,1]

#Calling the wasteland find_extremes() method
least, most = ws.find_extremes(x)

#Calling the wasteland sorting algorithm
ws.sort(x, True)
ws.sort(y, False)

# y = [1, 4, 9, 72, 78, 645, 3344, 111234]
# x = [111234, 3344, 645, 78, 72, 9, 4, 1]
# least = 1
# most = 111234
```



