Which of the following will match?

1. a = [1, 2, 3]
2. a = 4
3. 4 = a
4. [a, b] = [1, 2, 3] --> This is the only one that won't match
5. a = [[1, 2, 3]]
6. [a] = [[1,2,3]]
7. [[a]] = [[1, 2, 3]]

Which of the following will match?

1. [a, b, a] = [1, 2, 3]
2. [a, b, a] = [1, 1, 2]
3. [a, b, a] = [1, 2, 1] --> This will match

The variable is bound to the value 2, which of the following will match?

1. [a, b, a] = [1, 2, 3]
2. [a, b, a] = [1, 1, 2]
3. a = 1 --> This will match; a will be re-assigned the value 1
4. ^a = 2 --> This will match
5. ^a = 1
6. ^a = 2 - a --> The reason these will not match is because ^ overrides re-assignment and forces matching for the left side. Normally these would "match" due to re-assignment.