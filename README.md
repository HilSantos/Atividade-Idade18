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

int idade;

  Console.Write("Digite a idade (idade negativa para encerrar): ");
            idade = int.Parse(Console.ReadLine());

  while (idade >= 0)
            {
                if (idade < 18)
                    Console.WriteLine("Menor de idade.");
                else
                    Console.WriteLine("Maior de idade.");

  Console.Write("Digite a idade (idade negativa para encerrar): ");
                idade = int.Parse(Console.ReadLine());
            }
            Console.WriteLine("Programa encerrado.");
            Console.ReadKey();
        }
    }
}

