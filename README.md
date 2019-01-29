## ProgrammingKnowledge

# What's the difference between i++ and ++i?
* i++ will increment the value by 1, but it will return the original value that i held before being incremented.
  * int i = 0; arr[i++] = 'test'; 
  * above code will add 'test' into arr[0] instead of arr[1]
* ++i will increment the value by 1 and return the incremented value
  * int i = 0; arr[++i] = 'test';
  * above code will add 'test' into arr[1] because it's being incremented first
* It will be easier to see the difference if i++ or ++i contains on a single statement
