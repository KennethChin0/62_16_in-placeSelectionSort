# in-place selection sort

Rearrange
an unordered `ArrayList<Integer>`
and use it as the data in an `OrderedList_inArraySlots`.

The re-use is probably contrary to Java's conventions
for its built-in classes. But as a pedagogical tool,
it has the advantage of allowing
the User program to check that the sort
is done in-place.

## count the cost

0. If the number of the elements in the input triples,
the time required to run the reigning champ algorithm
will grow by 3 times. ChampIndex will have to run for 
each element and there are 3 times more elemtns.

[Justify, in about 2 sentences.]

0. If the number of the elements in the input triples,
the number of times that the reigning champ algorithm
will be invoked 
will grow by 3 times. For each element in the ArrayList,
you have to invoke the champ algorithm. So if u increase
the number of elements by 3, the number of times you run
the algorithm will increase by a factor of 3.
[Justify, in about 2 sentences.]

0. If the number of the elements in the input triples,
the time required for the selection sort
will grow by 9 times. The number of times required 
to run the champ algorithm times the number of times
the reigning champ algorithm will be run.
[Justify, in about 2 sentences.]
