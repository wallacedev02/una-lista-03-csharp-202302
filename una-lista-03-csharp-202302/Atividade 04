internal class Atividade03_04
{
    private static void Main(string[] args)
    {
        int operacao;
        double raio, resultado = 0;

        Console.WriteLine("Selecione a opção desejada: \n1- Calcular e imprimir o perímetro do circulo. \n2- Calcular e imprimir a área do círculo. \n3- Calcular e imprimir o volume da esfera.");
        operacao = Convert.ToInt32(Console.ReadLine());

        while (operacao > 3 || operacao < 1)
        {
            Console.WriteLine("OPERAÇÃO INVÁLIDA!! \n\nSelecione a opção desejada: \n1- Calcular e imprimir o perímetro do circulo. \n2- Calcular e imprimir a área do círculo. \n3- Calcular e imprimir o volume da esfera.");
            operacao = Convert.ToInt32(Console.ReadLine());
        }

        Console.WriteLine("Digite o valor do raio: ");
        raio = Convert.ToDouble(Console.ReadLine());

        switch (operacao)
        {
            case 1:
                resultado = 2 * Math.PI * raio;
                Console.WriteLine("O perímetro do círculo é: " + resultado.ToString("F"));
                break;

            case 2:
                resultado = Math.PI * Math.Pow(raio, 2);
                Console.WriteLine("A área do círculo é: " + resultado.ToString("F"));
                break;

            case 3:
                resultado = (4 / 3) * Math.PI * Math.Pow(raio, 3);
                Console.WriteLine("O volume da esfera é: " + resultado.ToString("F"));
                break;

            default:
                break;
        }
        Console.ReadLine();
    }
}
