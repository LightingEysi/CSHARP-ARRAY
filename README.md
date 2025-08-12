using System;

class Program
{
    static void Main()
    {
        // Create an integer array
        int[] numbers = { 10, 20, 30, 40, 50 };

        // Print all numbers
        Console.WriteLine("Numbers in the array:");
        foreach (int num in numbers)
        {
            Console.WriteLine(num);
        }

        // Access specific element
        Console.WriteLine("\nFirst number: " + numbers[0]);
        Console.WriteLine("Last number: " + numbers[numbers.Length - 1]);

        // Change a value
        numbers[2] = 99;
        Console.WriteLine("\nAfter changing third number to 99:");
        foreach (int num in numbers)
        {
            Console.WriteLine(num);
        }
    }
}
