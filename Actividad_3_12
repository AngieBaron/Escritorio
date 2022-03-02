using System;
using System.Linq;
using System.Text;
using System.Collections;
using System.Collections.Generic;

namespace Ejercicio12
{
    class program
    {
        static void Main(string[] args)
        {
            int num = 0;
            int i = 0;
            int suma1 = 0, suma2 = 0, suma3 = 0;
            
            int opcion;
            Console.WriteLine("digite una cantidad de votantes mayor a 20");
            num = int.Parse(System.Console.ReadLine());
           
            if (num<20)
            {
                Console.WriteLine("No es posible realizar la votacion, ya que no9 hay mas de 20 votantes");
            }
            else
            {
                while (i < num)
                {

                    Console.WriteLine("1: candidato1");
                    Console.WriteLine("2: candidato2");
                    Console.WriteLine("3: candidato3");
                    Console.WriteLine("Seleccione su candidato");
                    opcion = int.Parse(System.Console.ReadLine());

                    switch (opcion)
                    {
                        case 1:
                            Console.WriteLine();
                            suma1 = suma1 + 1;
                            break;

                        case 2:
                            Console.WriteLine();
                            suma2 = suma2 + 1;
                            break;
                        case 3:
                            Console.WriteLine();
                            suma3 = suma3 + 1;
                            break;
                    }

                    i++;
                }

                if (suma1 > suma2 && suma1 > suma3)
                {
                    Console.WriteLine(" El candidato con mayor votacion es: candidato 1");
                }
                if (suma2 > suma1 && suma2 > suma3)
                {
                    Console.WriteLine(" El candidato con mayor votacion es: candidato 2");
                }
                if (suma3 > suma1 && suma3 > suma2)
                {
                    Console.WriteLine(" El candidato con mayor votacion es: candidato 3");
                }

                Console.WriteLine(" La cantidad de votos por el candidato 1 son: {0}", suma1);
                Console.WriteLine(" La cantidad de votos por el candidato 2 son: {0}", suma2);
                Console.WriteLine(" La cantidad de votos por el candidato 3 son: {0}", suma3);
            }

        }
    }
}
