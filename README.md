using System;
using System.Collections.Generic;
using System.Linq;
using System.Text;
using System.Threading.Tasks;

namespace User_inputs
{
    class Program
    {
        static void Main(string[] args)
        {
            // asking the user for inut
            Console.Write("please enter a number 1: ");
            //converting string to int 
            int x = Convert.ToInt32(Console.ReadLine());
            Console.Write("please enter a number 2: ");
            int y = Convert.ToInt32(Console.ReadLine());
            Console.Write("please enter a number 3: ");
            int z = Convert.ToInt32(Console.ReadLine());
            // multiples numbers given by the user and out puts results 
            int a = x * y * z;

            Console.WriteLine("{0} times {1} times {2} equals:{3} ", x, y, z, a);
            Console.ReadLine();
        }
    }
}

