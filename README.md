# Calculator by Parse Tree

The program parses the input into a parse tree, then prints the computed result. Wrong expressions are detected by and the location of the error is notified.

![Alt text](example.png?raw=true, "hey")

## Parenthesization

 Each '(' creates a new tree and is pushed onto top of the trees stack. Any digit read or operand read from that point on is appened to the tree at the top of the stack.

 At the end of the parse loop, trees are attached to one another to create one main tree.

## Operands
Currently these operands are computable
 * '+'
 * '-'
 * '/
 * '*'

## Syntax checking

parser is exited early before any trees are built if a syntax error is deteced by sysntaxcheck()
