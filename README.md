1. Start the program.
2. Initialize the required variables.
3. Enter the input symbol.
4. Perform the following:
for top-of-stack symbol, s, and next input symbol, a
Shift x: (x is a STATE number)
Push a, then x on the top of the stack
Advance ip to point to the next input symbol.
Reduce y: (y is a PRODUCTION number)
Assume that the production is of the form A→ß
Pop 2 * |ß| symbols of the stack.
At this point the top of the stack should be a state number, say s’.
Push A, then goto of T[s’,A] (a state number) on the top of the stack.
Output the production A→ß.
5. Print if string is accepted or not.
6. Stop the program.
