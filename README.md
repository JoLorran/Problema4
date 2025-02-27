using System;

class Program
{
    static void Main()
    {
        // Lendo os quatro valores inteiros
        Console.Write("Digite o valor de A: ");
        int A = int.Parse(Console.ReadLine());

        Console.Write("Digite o valor de B: ");
        int B = int.Parse(Console.ReadLine());

        Console.Write("Digite o valor de C: ");
        int C = int.Parse(Console.ReadLine());

        Console.Write("Digite o valor de D: ");
        int D = int.Parse(Console.ReadLine());

        // Calculando a diferença conforme a fórmula
        int DIFERENCA = (A * B - C * D);

        // Exibindo o resultado
        Console.WriteLine($"DIFERENCA = {DIFERENCA}");
    }
}
