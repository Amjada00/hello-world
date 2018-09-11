# hello-world
using System;

namespace Les_3
{

    class Leeuw
    {
        public String Naam { get; set; }

        public void Brullen()
        {
            Console.WriteLine($"{Naam} brult er op los");
        }
    }
    class Program
    {
        static void Main(string[] args)
        {
            for (int i = 0; i < 100; i++)
            {
                Console.WriteLine(i);
            }
            Leeuw leeuw = new Leeuw();
            leeuw.Naam = "Lukie";

            leeuw.Brullen();
        }
    }
}

