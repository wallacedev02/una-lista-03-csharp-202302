internal class Atividade03_02
{
    private static void Main(string[] args)
    {
        double valorCompra, valorPago;

        Console.WriteLine("Informe o valor da compra: ");
        valorCompra = Convert.ToDouble(Console.ReadLine());

        Console.WriteLine("Informe o valor pago: ");
        valorPago = Convert.ToDouble(Console.ReadLine());

        while (valorPago < valorCompra)
        {
            Console.WriteLine("O VALOR PAGO É MENOR QUE O VALOR DA COMPRA!! \n\n Selecione a opção abaixo: \n 1- Alterar valor pago \n 2- Alterar valor da compra");
            int opcao = Convert.ToInt32(Console.ReadLine());

            switch (opcao)
            {
                case 1:
                    Console.WriteLine("Informe o valor pago: ");
                    valorPago = Convert.ToDouble(Console.ReadLine());
                    break;
                case 2:
                    Console.WriteLine("Informe o valor da compra: ");
                    valorCompra = Convert.ToDouble(Console.ReadLine());
                    break;
                default:
                    break;
            }

            while (opcao != 1 && opcao != 2)
            {
                Console.WriteLine("OPÇÃO INVÁLIDA!! \n\nSelecione uma opção abaixo: \n 1- Alterar valor pago \n 2- Alterar valor da compra");
                opcao = Convert.ToInt32(Console.ReadLine());

                switch (opcao)
                {
                    case 1:
                        Console.WriteLine("Informe o valor pago: ");
                        valorPago = Convert.ToDouble(Console.ReadLine());
                        break;
                    case 2:
                        Console.WriteLine("Informe o valor da compra: ");
                        valorCompra = Convert.ToDouble(Console.ReadLine());
                        break;
                    default:
                        break;
                }
            }
        }

        double troco = valorPago - valorCompra;

        Console.WriteLine("\nValor da compra: " + valorCompra);
        Console.WriteLine("Valor pago: " + valorPago);
        Console.WriteLine("O troco é de R$ " + troco.ToString("F"));

        int n50, n20, n10, n5, n2, n1;

        n50 = Convert.ToInt32(troco) / 50;
        troco %= 50;
        n20 = Convert.ToInt32(troco) / 20;
        troco %= 20;
        n10 = Convert.ToInt32(troco) / 10;
        troco %= 10;
        n5 = Convert.ToInt32(troco) / 5;
        troco %= 5;
        n2 = Convert.ToInt32(troco) / 2;
        troco %= 2;
        n1 = Convert.ToInt32(troco);


        Console.WriteLine("\nNotas de R$ 50,00: " + n50);
        Console.WriteLine("Notas de R$ 20,00: " + n20);
        Console.WriteLine("Notas de R$ 10,00: " + n10);
        Console.WriteLine("Notas de R$ 5,00: " + n5);
        Console.WriteLine("Notas de R$ 2,00: " + n2);
        Console.WriteLine("Notas de R$ 1,00: " + n1);

        Console.ReadLine();
    }
}
