# dio-trilha-java-basico
import java.util.Scanner;

public class ContaTerminal {
    public static void main(String[] args) {
        Scanner scanner = new Scanner(System.in);

        System.out.println("Por favor, digite o número da Agência:");
        String agencia = scanner.nextLine();

        System.out.println("Por favor, digite o número da Conta:");
        int numero = scanner.nextInt();
        scanner.nextLine(); // Limpa o buffer

        System.out.println("Por favor, digite o nome do Cliente:");
        String nomeCliente = scanner.nextLine();

        System.out.println("Por favor, digite o saldo:");
        double saldo = scanner.nextDouble();

        System.out.println("Olá " + nomeCliente + ", obrigado por criar uma conta em nosso banco, sua agência é " + agencia +
                ", conta " + numero + " e seu saldo " + saldo + " já está disponível para saque.");



                Aqui está uma breve explicação do código:

Importamos a classe Scanner para facilitar a entrada de dados via terminal.
Criamos um objeto Scanner chamado scanner para ler os dados do terminal.
Solicitamos ao usuário que insira o número da agência, número da conta, nome do cliente e saldo, respectivamente.
Utilizamos os métodos nextLine() e nextInt() do Scanner para ler os dados do usuário.
Após a leitura de cada dado, armazenamos esses dados em variáveis correspondentes.
Por fim, exibimos a mensagem final utilizando os dados inseridos pelo usuário.

        scanner.close();
    }
}
