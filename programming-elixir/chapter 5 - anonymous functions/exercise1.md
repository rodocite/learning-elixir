# Create and run functions that do the following: 

1. list_concat.([:a, :b], [:c, :d]) #=> [:a, :b, :c, :d]
2. sum.(1,2,3) #=> 6
3. pair_tuple_to_list.({1234, 5678}) #=> [1234, 5678]

Solutions

1.
  ```
  list_concat = fn (a, b) -> a ++ b end
  ```
  
2. 
  ```
  sum = fn (a, b, c) -> a + b + c end
  ```

3.
  ```
  pair_tuple_to_list = fn ({a, b}) -> [a, b] end
  ```