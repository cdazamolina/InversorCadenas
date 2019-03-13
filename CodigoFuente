using System;
using System.Collections.Generic;
using System.Linq;
using System.Text;
using System.Threading.Tasks;

namespace PruebaLaboral
{
    class Program
    {
        static void Main(string[] args)
        {
            Invert Invertir = new Invert();
            Console.WriteLine("ALGORITMO DE INVERSIÓN DE CADENAS DE TEXTO");
            Console.WriteLine("Ingrese la cadena que desea invertir:");
            Invertir.InvertirCadenas(Console.ReadLine());
            Console.ReadKey();    
        }
    }

    class Invert
    {
        public void InvertirCadenas(string Cadena)
        {
            char[] CadenaChar = Cadena.ToCharArray();
            Array.Reverse(CadenaChar);
            new String(CadenaChar);
            Console.WriteLine("La cadena invetida es:");
            Console.WriteLine(CadenaChar);
        }
    }
}
