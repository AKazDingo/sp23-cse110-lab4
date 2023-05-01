# Part 3

1. The bug is that because num1 and num2 are being input to calculateSum as strings, the '+' symbol is concatenating them, returning a result that is just the numbers as a string combined.

2. Can fix it by adding parseInt() to the declaration of num1 and num2. See fix in fix.png
