ORDER OF EXECUTION
To find the source of an error, it helps to know how scripts are processed.
The order in which statements are executed can be complex; some tasks
cannot complete until another statement or function has been run

EXECUTION CONTEXTS
The JavaScript interpreter uses the concept of execution contexts.
There is one global execution context; plus, each function creates a new
new execution context. They correspond to variable scope. 

UNDERSTANDING
SCOPE
In the interpreter, each execution context has its own va ri ables object.
It holds the variables, functions, and parameters available within it.
Each execution context can also access its parent's v a ri ables object.
Functions in JavaScript are said to have lexical scope.
They are linked to the object they were defined within.
So, for each execution context, the scope is the
current execution context's variables object, plus the
variables object for each parent execution context
Imagine that each function is a nesting doll.
The children can ask the parents for information in
their variables. But the parents cannot get variables
from their children. Each child will get the same
answer from the same parent

UNDERSTANDING ERRORS
If a JavaScript statement generates an error, then it throws an exception.
At that point, the interpreter stops and looks for exception-handl ing code
