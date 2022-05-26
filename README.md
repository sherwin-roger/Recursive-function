# Recursive-function

##Aim: To write a C# program to reverse a number using recursive function.

##Algorithm:
1)create a class and then declarea main function
2)

##Program:
```
using System;
class example
{
    public static void fun(int n)
    {
        if(n < 1)
        {
            
            return;
        }
        else
        {
            Console.Write(n % 10);
            fun(n / 10);
        }
    }
    public static void Main()
    {
        int i;
        i = Convert.ToInt32(Console.ReadLine());
        fun(123);
        
    }
}


```

##Output:
![image](https://user-images.githubusercontent.com/75235128/170473821-d3d6713c-3ac6-4fc5-a365-5e7f08659bb0.png)

##Result:
Thus C# program to reverse a number using recursive function is written and executed sucessfully.
