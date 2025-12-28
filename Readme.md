    class Task3
    {
    static void Main()
    {
        int[] numbers = { 3, 7, 12, 19, 21, 25, 30 };
        Console.Write("Enter number: ");
        int t = int.Parse(Console.ReadLine());

        for (int i = 0; i < numbers.Length; i++)
            if (numbers[i] == t)
            {
                Console.WriteLine($"Found at {i}!");
                return;
            }
        Console.WriteLine("Not found.");
    }
}
