using System;
using System.Globalization;

namespace Uri1002
{
    class Program
    {
        static void Main(string[] args)
        {
            double area, n, raio;

            raio = double.Parse(Console.ReadLine(), CultureInfo.InvariantCulture);
    
            n = 3.14159;
            raio = Math.Pow(raio, 2);
            area = n * raio;
    
            Console.WriteLine("A=" + area.ToString("F4", CultureInfo.InvariantCulture));


​            
        }
    }
}