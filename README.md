## ProgrammingKnowledge

# What's the difference between i++ and ++i?
* i++ will increment the value by 1, but it will return the original value that i held before being incremented.
  * int i = 0; arr[i++] = 'test'; 
  * above code will add 'test' into arr[0] instead of arr[1]
* ++i will increment the value by 1 and return the incremented value
  * int i = 0; arr[++i] = 'test';
  * above code will add 'test' into arr[1] because it's being incremented first
* It will be easier to see the difference if i++ or ++i contains on a single statement

# What are the things to consider before using Android Library?
* *Maintenance*. Android is evolving. So, make sure to choose a library that can keep evolving within time. We need to also check who's doing the maintenance? Is it a single individual who may have lost interest with that library OR a dedicated company that's maintaining high-quality product for a long period of time, like Google or Square?
* *64K Method*. Android app will crash if it has 65,536 methods. It can only contains less than 64K methods in a single Dalvik Executable (DEX) file that translates Java into Android Package Kit (APK) file.
* *Known Issues*. Many libraries has issues on their Github page. Check the issues. Is it gonna affect your app?
* *Choose a library with the smallest size but effective for your app*
* *License*. Failure to provide a license, our app will get rejected from Play Store. Check the license section on each library that you use
