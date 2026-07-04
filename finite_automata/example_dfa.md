# Example DFA: strings over {0,1} that end with "01"

Alphabet: {0,1}

States: q0 (start), q1, q2 (accept)

Transition function (informal):
- q0 --0--> q1
- q0 --1--> q0
- q1 --0--> q1
- q1 --1--> q2
- q2 --0--> q1
- q2 --1--> q0

Accepting state: q2

Description: This DFA accepts any binary string whose last two symbols are 0 followed by 1. Use this as a template for building and testing small DFAs.
