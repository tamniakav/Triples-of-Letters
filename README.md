# Triples-of-Letters
Just another repository
using System;
using System.Collections.Generic;
using System.Linq;
using System.Text;
using System.Threading.Tasks;

namespace Triples_of_Latin_Letters
{
    class Program
    {
        static void Main(string[] args)
        {
            int n = int.Parse(Console.ReadLine());

            for (char i = 'a'; i <= 'a' + (n -1); i++)
            {
                for (char j = 'a'; j <= 'a' + (n - 1); j++)
                {
                    for (char k = 'a'; k <= 'a' + (n - 1); k++)
                    {
                        Console.WriteLine($"{i}{j}{k}");
                    }
                }
            }
        }
    }
}
