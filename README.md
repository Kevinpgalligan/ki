### ka(lculator)
A calculator language.

### TODO
* Use Python's built-in numerical type hierarchy, if possible. So that not everything needs to be wrapped. Will probably require quite a bit of refactoring.
* Fix bug: C(4,2) returns 6/1, something fucky going on with the type system there.
* Refactor: use ParseNode label only for appearance, store actual data as its value.
* Integrate quantities into type system, quantity arithmetic / functions.
* Bug: can't use symbol name of degrees Celcius, probably a unicode issue.
* Fix CLI so it doesn't interpret leading negative unary operator as a flag: <https://docs.python.org/3/library/argparse.html#arguments-containing>
* Refactor ugly divide(), leverage dispatch.
* Handle runtime errors (e.g. incompatible units, division by 0, overflow, and the like; overflow can happen during parsing!).
* Accept more number input formats. 
* Investigate precision when values are large.
* Documentation (features / interesting things; usage; the grammar, example files + ability to execute files; DISPATCH TABLE (functions))
* Put it on PyPI.
* An interpreter! Including special commands for showing the environment, clearing the environment, etc.
* Lazy combinatorics type.
