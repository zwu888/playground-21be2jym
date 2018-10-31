# description: 
 Arrays can be implicity converted to pointers without casting -- 4.2.  There is no implicit conversion from pointers to arrays.
```C++ runnable
#include <iostream>

using namespace std;

int main()
{
     int a[54] = {};
 
     int b[54] = {};
 
     int* x = a;
 
    int* const y = a;
 
    b = x;
 
    b = y;
 
    return 0;
 } 
```

# Advanced usage

If you want a more complex example (external libraries, viewers...), use the [Advanced C++ template](https://tech.io/select-repo/598)
