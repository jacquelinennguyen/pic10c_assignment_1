# pic10c_assignment_1
Option A

Commit #2: Added README file

Commit #3: Added pic10b_vector.h file

Commit #4: Updated README file

Commit #5: Templatize vector class

Commit #6: Fixed minor syntax errors and tested on ints. Compiles, but output is right when run from terminal versus when run on Visual Studio

Commit #7: Overloaded several operators.

Commit 8: Looked up why += operator wasn't working properly. https://stackoverflow.com/questions/19697444/c-vector-operator-overloading. Tried to make operator += local instead of global. Essentially used code from operator[].

Commit 9: Removed some code from operator+= because it wasn't necessary.

Commit 10: Changed dot product (operator*) to print out correct output. I didn't know what the dot product was. Norm also works! Looked up how to add vectors here: https://mathisfun.com/algebra/vectors-dot-product.html.

Commit 11: operator> was not printing correct output. Turns out I was supposed to be comparing norms and not values in the vector, so I went in and changed operators <, <=, and >= also. Output is what it's supposed to be minus minor syntactic things.

Commit 12: Added assignment, copy, and destructor call messages to print to the console. Tested with driver 1 and 2. Works for both, although I'm not sure about the default destructor message appearing in certain places. To check for datatype, I used this website: https://stackoverflow.com/questions/4843173/how-to-check-if-type-variable-is-a-string.

Commit 13: Added minor syntactic details to print function. 

Commit 14: I think I kind of get how specialization for templates works now. I fixed the syntax of the declarations and definitions. Before I had two identical copies of the same function. Looked at this for debugging: https://www.codeproject.com/Questions/774102/is-not-a-specialization-of-a-function-template

Commit 15: Fixed some minor syntactic errors. Still does not print Name: First Last.

Commit 16: Return type was returning vector that was read in instead of the vector created in the method. Fixed that and now prints Name: First Last.

Commit 17: Merged branch string
