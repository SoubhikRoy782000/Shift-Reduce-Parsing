# Shift-Reduce-Parsing

Aim -

To implement Shift Reduce Parsing.

Algorithm –

Step 1 – Initialize the required variables. 
Step 2 – Enter the input symbol. 
Step 3 – Perform the following: 
for top-of-stack symbol, s, and next input symbol, a 
Shift x: (x is a STATE number) 
Push a, then x on the top of the stack 
Advance ip to point to the next input symbol. 
Reduce y: (y is a PRODUCTION number) 
Assume that the production is of the form A→ß 
Pop 2 * |ß| symbols of the stack. 
At this point the top of the stack should be a state number, say s’. 
Push A, then goto of T[s’,A] (a state number) on the top of the stack. Output the production A→ß. 
Step 4 – Print if string is accepted or not.
