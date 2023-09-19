internal class Atividade03_01
{
    private static void Main(string[] args)
    {
        double num1, num2, num3, media, maior = 0, menor = 0;

        Console.WriteLine("Digite o primeiro número:");
        num1 = Convert.ToDouble(Console.ReadLine());

        Console.WriteLine("Digite o segundo número:");
        num2 = Convert.ToDouble(Console.ReadLine());

        Console.WriteLine("Digite o terceiro número:");
        num3 = Convert.ToDouble(Console.ReadLine());

        media = (num1 + num2 + num3) / 3;

        maior = num1;
        menor = num1;

        if (num2 > maior)
        {
            maior = num2;
        }
        if (num2 < menor)
        {
            menor = num2;
        }

        if (num3 > maior)
        {
            maior = num3;
        }
        if (num3 < menor)
        {
            menor = num3;
        }

        Console.WriteLine("1 - O maior número: " + maior);
        Console.WriteLine("2 - O menor número: " + menor);
        Console.WriteLine("A média aritmética dos três números: " + media.ToString("F"));

        Console.ReadLine();
    }
}
