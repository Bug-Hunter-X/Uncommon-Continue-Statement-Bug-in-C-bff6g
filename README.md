# Uncommon Continue Statement Bug in C
This repository demonstrates a subtle bug related to the `continue` statement in a C `while` loop. The code appears to iterate correctly, but it unexpectedly omits the number 5 from the output.

## Bug Description
The `continue` statement is used to skip the rest of the current iteration and proceed to the next iteration of the loop. However, in this case, it demonstrates an unexpected behavior when combined with loop condition and `printf` statement.