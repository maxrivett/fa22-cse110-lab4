# Answers
<hr>

1. The problem was that the data type of `num1` and `num2` was string, so they were being concatenated rather than added.

2. I would fix it by changing the types of `num1` and `num2` to int using the `parseInt()` function. This can be seen in `fix.png`.