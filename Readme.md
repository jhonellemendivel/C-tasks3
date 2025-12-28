    using System;

    class Task3
    {
    static void Main(string[] args)
    {
        // Initialize the array
        int[] numbers = { 3, 7, 12, 19, 21, 25, 30 };

        // Prompt user for input
        Console.Write("Enter a number to search for: ");
        int target = int.Parse(Console.ReadLine());

        // Search using for loop
        bool isFound = false;
        for (int i = 0; i < numbers.Length; i++)
        {
            if (numbers[i] == target)
            {
                Console.WriteLine($"Number found at position {i}!");
                isFound = true;
                break; // Exit loop immediately
            }
        }

        // Message if number not found
        if (!isFound)
        {
            Console.WriteLine("Number not found in the list.");
        }
    }
    }
