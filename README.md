# evaluate-dnf

Evaluates a given DNF-query if it's satisfiable.

The DNF-query should be in the following form:

`A¬BCvBC¬BvA¬AB¬C` (satisfiable)

Constraints for input:

* OR: 'v'
* AND: (implicit; e.g. A AND B = AB)
* NOT: '¬'
* all variables are single chars (upper case)
* no spaces
