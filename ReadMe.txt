Sort without sorting (one million elements in 3(!) seconds).

This Sort-Class can be used to retrieve the elements in a one-dimensional table of strings in either ascending or descending sequence. The table itself is not altered in any way by this process, rather pointers into the table are returned which point to the elements in the table in the requested order.

Tests on a 1800 MHz Athlon processor have shown that the Sort is in fact the fastest I know, sorting 100,000 elements on a five byte random sort key in under 0.3 seconds. The speed varies only very slightly with the number of elements to be sorted, so one million elements take about three seconds to sort. Any special presorting has no measurable effect on speed (Quicksort by contrast is almost killed by a presorted sequence).




