using System.Net.Http.Headers;

namespace phellowrld;

class Program
{
    static void Main(string[] args)
    {
        int nota1 = 9;
        int nota2 = 8;
        int media = (nota1 + nota2)/2;
        if (media > 7)
            Console.WriteLine("Aprovado!");
        else if (media < 7)
            Console.WriteLine("Reprovado!");
    }
}
