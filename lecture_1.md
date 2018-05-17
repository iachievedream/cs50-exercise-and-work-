cs50-exercise-and-work-
===

Website : http://cs50.tv/2017/fall/

int.c
~~~
#include <cs50.h>
#include <stdio.h>

int main(void)
{
   int i = get_int("interger:");
   printf("hello,%i\n", i);
}
~~~

terminal：

<code>make int</code> //編譯執行檔>>出現int檔案

<code>./int</code> //執行執行檔int

輸入interger:

***

one exercise complete

hello.c
~~~
#include <stdio.h>
#include <cs50.h>

void hellotime(int times,string str){
    for (int i=1;i<=times;i++){
        printf("%s\n",str);
    }
}

int main(void){
    hellotime(3,"Hello");

    return 0;
}
~~~

terminal：
