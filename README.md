using System.ComponentModel;
using System.Net.Http.Headers;

namespace phellowrld;

class Program
{
    static void Main(string[] args)
    {
        Console.WriteLine("Qual a nota da primeira prova realizada?");
        var nota1 = Console.ReadLine();
        Console.WriteLine("E qual a nota da segunda prova realizada?");
        var nota2 = Console.ReadLine();

        var media = (int.Parse(nota1) + int.Parse(nota2))/2;

        {
        if (media >= 7) 
            Console.WriteLine("Aprovado! Sua média é:" + media);
            else if (media > 5)
                Console.WriteLine("Recuperação! Sua média foi: " + media);
            else
                Console.WriteLine("Reprovado! Sua média foi: " + media);
        }
    }
}
