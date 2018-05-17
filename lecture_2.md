C-language_code
====
function and void.
---
~~~~
#include <stdio.h>

void add(int a,int b){
    printf("a&b=%i %i\n",a,b);
    int c;
    c=a+b;
    printf("totle=%i\n",c);
}

int main(int argc, const char * argv[]) {
    add(4 , 8);
    return 0;
}
~~~~
note:void add(int a,int b)

> void不需要return，它的功用顯示在printf上面，
  
> 如果是以int為主的型態，則是還多return的回傳值特性可以應用。
 
 * 以下為另一個的簡易範例：
~~~
#include <stdio.h>

int add(int a,int b){
    printf("a&b=%i and %i\n",a,b);
    return a+b;
}

int main(int argc, const char * argv[]) {
    int c;
    c=add(4 , 8);
    printf("totle=%i\n",c);
    return 0;
}

~~~
