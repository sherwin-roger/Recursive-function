# Recursive-function

##Aim: To write a C# program to reverse a number using recursive function.

##Algorithm:
1)create a class and then declare a main function
2)Inside the class declare a recursive function to find the reverse of a number
3)Pass the number and execute it until it is less than 1
4)if the number is less than 1 then it will stop executing itself again and again
5) Until then print the passed number.

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
