--------------
wasteland_sort
--------------


.. py:function:: wasteland_sort(landmarks: list, reverse: bool) -> list

    O(n + m) time, O(max(n, m)) space integer sorting algorithm

    :param landmarks: list of integers to be sorted
    :param reverse: boolean representing whether or not to sort in reverse order

    :returns: None. Array is sorted pseudo in-place. Original integers are overwritten


.. py:function:: find_extremes(landmarks: list) -> Union(int, int)

    Helper function to find the maximum and minimum elements of a list ins O(n) time

    :param landmarks: list of integers to be searched

    :returns: minimum and maximum values of the array, in that order