1. The bug is the values are treated as strings instead of ints, since both are stored as strings. This makes results be a concatenation of 2 strings instead of an int.
2. I would parse both strings into an int, so result adds both of the numbers properly.
