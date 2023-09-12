# Pattern

## Aim:
To write a C# program for a pascal's triangle.

## Equipment Required:
1.Hardware : pc

2.software : Visual Studio.

## Algorithm:
 Step 1: Start the program.

 Step 2: Create a class and declare two variables rows,Val using integer datatype.

 Step 3: Using nested for loop create a pascal's triangle.

 Step 4: Stop the execution.
 
## Program:
Name : G.Tejaswini

Reg no: 212222230157
```python

using System;
public class pattern
{
    public static void Main()
    {
        int rows, c = 1, a, i, j;

        Console.Write("rows: ");
        rows = Convert.ToInt32(Console.ReadLine());
        for (i = 0; i < rows; i++)
        {
            for (a = 1; a <= rows - i; a++)
            {
                Console.Write(" ");
            }
            for (j = 0; j <= i; j++)
            {
                if (j == 0 || i == 0)
                {
                    c = 1;
                }
                else
                {
                    c = c * (i - j + 1) / j;
                }
                Console.Write("{0} ", c);
            }
            Console.Write("\n");
        }
    }
}
```
## Output:

## Result:
Thus the c# code for a pascal's traingle was executed successfully.


