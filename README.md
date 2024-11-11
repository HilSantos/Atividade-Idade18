# Atividade-Idade18
Solicite que o usuário insira uma idade. Se a idade for menor que 18, exiba “Menor de idade”; caso contrário, exiba “Maior de idade”. Continue pedindo até que o usuário digite uma idade negativa.

using System;
using System.Collections.Generic;
using System.Linq;
using System.Text;
using System.Threading.Tasks;

namespace Ativ.Idade18
{
    public class Program
    {
        static void Main(string[] args)
        {
            string idade;
            int i = 1;

            Console.WriteLine("Informe a idade: ");
            idade = Console.ReadLine();

            while (i <= 18)
            {
                Console.WriteLine("Menor de idade")
            }

            Console.ReadKey();
        }
    }
}
