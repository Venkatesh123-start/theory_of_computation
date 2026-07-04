# Example PDA: balanced parentheses

Language: L = { w ∈ { ( , ) }* | parentheses in w are balanced }

Idea: push on '(' and pop on ')'. Accept by empty stack.

Informal PDA description:
- On input '(': push a symbol (e.g., X) onto the stack.
- On input ')': if top of stack is X, pop; otherwise reject.
- At end of input: accept if stack is empty.

This PDA can be formalized as a 7-tuple and converted to a CFG that generates the same language.
