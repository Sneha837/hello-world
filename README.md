# hello-world
using System;
using System.Collections.Generic;
using System.Linq;
using System.Text;


namespace ConsoleApp1
{
    class Program
    {
        static void Main(string[] args)
        {
            int a, b, temp;
            Console.Write("\n Enter the number :");
            a = int.Parse(Console.ReadLine());

            Console.Write("\n Enter the number :");
            b = int.Parse(Console.ReadLine());

            temp = a;
            a = b;
            b = temp;

            Console.Write("\n After Swapping: ");
            Console.Write("\n First Number: " + a);
            Console.Write("\n Second Number: " + b);
            Console.Read();
      



        }
    }
}
