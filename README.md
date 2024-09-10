\\Professor: FABRICIO GERALDO VALADARES.
\\Aluno: MARCO PAULO SOARES RODRIGUES.
\\ CiÊncai da computação/UNA/2º período.

\\Projeto01:
import java.util.Scanner;
class Main {
  public static void main(String[] args) {
    
    Scanner entrada = new Scanner(System.in);
    
    Float numero1;
    Float numero2;
   
    Float resto;
    
    System.out.println("Digite o primeiro número: ");
    numero1 = entrada.nextFloat();
    
    System.out.println("digite o segundo número: ");
    numero2 = entrada.nextFloat();
    
    resto = numero1%numero2;
    
    System.out.println("O resto da divisão foi: " + resto );
    resto = entrada.nextFloat();   
    
  }
}

\\Projeto02

import java.util.Scanner;
class Main {
  public static void main(String[] args) {
    
    Scanner entrada = new Scanner(System.in);
    
    Double real;
    Double dolar;
    
    System.out.println("Digite o valor: ");
    real = entrada.nextDouble();
    
    dolar = real * 5.51;
    
    System.out.println("Em dolar: " + dolar);
    
  }
}  

\\Projeto03

import java.util.Scanner;
class Main {
  public static void main(String[] args) {
    
    Scanner entrada = new Scanner(System.in);
    
    Double area;
    Double raio;
    
    
    System.out.println("Coloque o raio do círculo: ");
    raio = entrada.nextDouble();
    
    area = 3.14 * raio * raio; 
    
    System.out.println("A área do círculo é: " + area);
     
    
  }
}

\\Projeto04

import java.util.Scanner;
class Main {
  public static void main(String[] args) {
    
    Scanner entrada = new Scanner(System.in);
    
    Double numero1;
    Double numero2;
    Double numero3;
    Double media;
    
    System.out.println("Digite o primeiro valor: ");
    numero1 = entrada.nextDouble();
    
    System.out.println("Digite o segundo valor: ");
    numero2 = entrada.nextDouble();
    
    System.out.println("Digita o terceiro valor: ");
    numero3 = entrada.nextDouble();
    
    media = numero1 + numero2 + numero3/3;
    System.out.println("A média é: " + media);
  
      
    
  }
}

\\Projeto05

import java.util.Scanner;
class Main {
  public static void main(String[] args) {
    
    Scanner entrada = new Scanner(System.in);
    
    Double valorHora;
    Double hora;
    Double salario;
    Double dias;
    
    System.out.println("O valor da hora trabalhada: ");
    valorHora = entrada.nextDouble();
    
    System.out.println("Horas Trabalhadas: ");
    hora = entrada.nextDouble();
    
    System.out.println("Quantos dias ao mês você trabalha: ");
    dias = entrada.nextDouble();
    
    salario = (valorHora * hora) * dias; 
    
    
    if(salario == 1412) {
      salario = salario / (7.5/100);
    }
    
    if (1412 < salario && salario > 2666) {
     salario = salario / (9/100);
    }
    
    if (2666 < salario && salario > 4000) {
     salario = salario / (12/100);
    }
    
    if (4000 < salario && salario > 7786) {
      salario = salario / (14/100);
    }
    
    System.out.println("Seu salário bruto é: " + "R$" + salario);
    salario =entrada.nextDouble();
  }
}

\\Projeto06

import java.util.Scanner;

class Main {
  public static void main(String[] args) {
    
  Scanner entrada = new Scanner(System.in);
  
  Double valorA;
  Double valorB;
  Double inverso;
    
  System.out.print("Digite o primeiro valor de A: ");
  valorA = entrada.nextDouble();
    
  System.out.print("Digite o valor de B: ");
  valorB = entrada.nextDouble();
    
  inverso = valorA; //inverso armazena o valor de A
  valorA = valorB; //A recebe o valor de B
  valorB = inverso; //B recebe o valor armazenado em inverso
  
    
  System.out.println("Trocando...");
  System.out.println("A: " + valorA);
  System.out.println("B: " + valorB);  
    
  
    

  
     
   
  }
}

Projeto07

import java.util.Scanner;
class Main {
  public static void main(String[] args) {
    
    Scanner entrada = new Scanner(System.in);
    
    Double x;
    
     System.out.print("Informe um número de 0 a 10: ");
     x = entrada.nextDouble();
    System.out.print("O quadrado de seu número é: "+x*x+" "+"e o cubo de seu número: "+x*x*x);
        
    
    
    
  }
}

\\Projeto08

import java.util.Scanner;

class Main {
  public static void main(String[] args) {
    
   Scanner entrada = new Scanner(System.in);
    
    Double valorF;
    Double valorC;
   
    
    System.out.println("Digite o valor em Fahrenheit: ");
    valorF = entrada.nextDouble();
    
    valorC=(valorF-32)*5/9;
    
    System.out.println("Valor em Celcius: " + valorC);
    valorC = entrada.nextDouble();
    
  }
}

\\Projeto 09

import java.util.Scanner;
class Main {
  public static void main(String[] args) {
    
   Scanner entrada = new Scanner(System.in);
    
    Double canetaQuantidade;
    Double pagamento;
    Double troco;
    Double preçoCaneta;
    
    System.out.println("Quantas canetas: ");
    canetaQuantidade = entrada.nextDouble();
    
    System.out.println("Valor da nota usada para o pagamento: ");
    pagamento = entrada.nextDouble();
    
    System.out.println("valor do troco: ");
    troco = entrada.nextDouble();
    
    preçoCaneta = (pagamento-troco)/canetaQuantidade;
    
    System.out.println("Preço da caneta: " + preçoCaneta);
   
      
    
  }
}

\\Projeto10

import java.util.Scanner;

class Main {
  public static void main(String[] args) {
    
    Scanner entrada = new Scanner(System.in);
    
    
    System.out.print("Informe a hora (HH:MM): ");
        String hora = entrada.nextLine();

        String[] partes = hora.split(":");
        int horas = Integer.parseInt(partes[0]);
        int minutos = Integer.parseInt(partes[1]);

        int minutosPassados = (horas * 60) + minutos;

        System.out.println("Minutos passados desde o início do dia: " + minutosPassados);
       
    
    
  }
}

\\Projeto11

import java.util.Scanner;
class Main {
  public static void main(String[] args) {
    
    Scanner entrada = new Scanner(System.in);
    
    Double etanol;
    Double gasolina;
   
    System.out.println("Qual o preço da gasolina? ");
    etanol = entrada.nextDouble();
    System.out.println("Qual o preço do etenol? ");
    gasolina = entrada.nextDouble();
    if((etanol*70/100)>gasolina){System.out.println("Abasteça com etnaol!");}else{System.out.println("Abasteça com gasonila!");}
    
  }
}

\\Projeto12

import java.util.Scanner;
class Main {
  public static void main(String[] args) {
    
   Scanner entrada = new Scanner(System.in);
   
    Double largura;
    Double comprimento;
    Double valor;
    Integer arredondamento;
     
    System.out.println("Informe a largura a ser revestida em metros: ");
    largura = entrada.nextDouble();
    System.out.println("Informe o comprimento a ser resvestido em metros: ");
    comprimento = entrada.nextDouble();
    System.out.print("Informe o valor do metro da cerâmica: ");
    valor = entrada.nextDouble();
    Double resultado = largura*comprimento*valor;
    System.out.println("O valor é: R$"+resultado*10/100);
  }
}

\\Projeto13

import java.util.Scanner;
class Main {
  public static void main(String[] args) {
    
    Scanner entrada = new Scanner(System.in);
    
    Double a;
    Double b;
    
    System.out.print("Informe o valor de A: ");
    a = entrada.nextDouble();
    System.out.print("Informe o valor de B: ");
    b = entrada.nextDouble();
    Double piaba = a;
    a = b;
    b = piaba;
    System.out.println("O valor de A é: "+a+"e o valor de B é: "+b);
  }
}


\\Projeto14

import java.util.Scanner;

class Main {
  public static void main(String[] args) {
    
    
    Scanner entrada = new Scanner(System.in);
    
    Double peso;
    
    System.out.println("informe o seu peso:");
    peso = entrada.nextDouble();
    System.out.println("A quantida ideal de água ser consumida será: "+peso*35/1000+"Litros");

    
  }
}

\\Projeto15

import java.util.Scanner;

class Main {
  public static void main(String[] args) {
    
    Scanner entrada = new Scanner(System.in);
    
  
    
        System.out.print("Digite o valor de x1: ");
        Double x1 = entrada.nextDouble();
        
        System.out.print("Digite o valor de y1: ");
        Double y1 = entrada.nextDouble();
        
        System.out.print("Digite o valor de x2: ");
        Double x2 = entrada.nextDouble();
        
        System.out.print("Digite o valor de y2: ");
        Double y2 = entrada.nextDouble();
        
        Double distancia = Math.sqrt(Math.pow((x1 - x2), 2) + Math.pow((y1 - y2), 2));
        
        System.out.println("A distância entre os pontos é: " + distancia);

  }
}

\\Projeto16


import java.util.Scanner;

class Main {
  public static void main(String[] args) {
    
    Scanner entrada = new Scanner(System.in);
    
        Double x;
    Double y;
    Double z;
    
    System.out.println("Informe a sua nota na primeira avaliação:");
    x = entrada.nextDouble();
    System.out.println("Informe a sua nota na segunda avaliação:");
    y = entrada.nextDouble();
    System.out.println("Informe a sua nota na terceira avaliação:");
    z = entrada.nextDouble();
    Double media = x*y*z/3; 
    if (media>=7){System.out.print("Você foi aprovado!"+"e sua média foi de "+media);}else{System.out.print("Você é burro!"+"Sua média foi de apenas: "+media);}

    
  }
}

\\Projeto17

import java.util.Scanner;

class Main {
  public static void main(String[] args) {
    
    Scanner entrada = new Scanner(System.in);   
    
    Double eleitores;
    Double brancos;
    Double nulos;
    Double validos;
    
    System.out.println("Informe a quantidade de votos brancos:");
    brancos = entrada.nextDouble();
    System.out.println("Informe a quantidade de votos nulos:");
    nulos = entrada.nextDouble();
    System.out.println("Informe a quantidade de votos válidos:");
    validos = entrada.nextDouble();
    eleitores = brancos+nulos+validos;
    System.out.print("A votação contou com "+eleitores+" eleitores"+" tendo: "+(brancos*100/eleitores)+"% de votos brancos"+(nulos*100/eleitores)+"% de votos nulos"+(validos*100/eleitores)+"% de votos validos!");

    
  }
}

\\Projeto18

import java.util.Scanner;

class Main {
  public static void main(String[] args) {
    
    Scanner entrada = new Scanner(System.in);
    
    Integer idade;
    
    System.out.println("Informe a sua idade: ");
    idade = entrada.nextInt();
    if (idade>=16){System.out.println("Voto facultativo");}if(idade<16){System.out.println("Idade insuficiente para votar!");}if(idade>18){System.out.println("Voto obrigaatório!");}

  }
}

\\Projeto19

import java.util.Scanner;

class Main {
  public static void main(String[] args) {
    
    Scanner entrada = new Scanner(System.in);
    
        double saldo = 1000.00; 
        String extrato = "";

        while (true) {
            System.out.println("Bem-vindo ao Caixa Eletrônico");
            System.out.println("Escolha uma das opções abaixo:");
            System.out.println("1 - Exibir saldo");
            System.out.println("2 - Exibir extrato");
            System.out.println("3 - Realizar depósito");
            System.out.println("4 - Realizar saque");
            System.out.println("5 - Sair");
            System.out.print("Opção: ");

            int opcao = scanner.nextInt();

            switch (opcao) {
                case 1:
                    System.out.println("Seu saldo é: R$ " + saldo);
                    break;

                case 2:
                    if (extrato.isEmpty()) {
                        System.out.println("Não há transações para exibir.");
                    } else {
                        System.out.println("Extrato:");
                        System.out.println(extrato);
                    }
                    break;

                case 3:
                    System.out.print("Digite o valor para depósito: R$ ");
                    double deposito = scanner.nextDouble();
                    saldo += deposito;
                    extrato += "Depósito de: R$ " + deposito + "\n";
                    System.out.println("Depósito realizado com sucesso.");
                    break;

                case 4:
                    System.out.print("Digite o valor para saque: R$ ");
                    double saque = scanner.nextDouble();
                    if (saque > saldo) {
                        System.out.println("Saldo insuficiente para realizar o saque.");
                    } else {
                        saldo -= saque;
                        extrato += "Saque de: R$ " + saque + "\n";
                        System.out.println("Saque realizado com sucesso.");
                    }
                    break;

                case 5:
                    System.out.println("Obrigado por utilizar o Caixa Eletrônico. Até logo!");
                    System.exit(0);

                default:
                    System.out.println("Opção inválida. O programa será encerrado.");
                    System.exit(1);
            }

            System.out.println(); // Linha em branco para separar as operações

  }
  }

\\Projeto20
import java.util.Scanner;

class Main {
  public static void main(String[] args) {
    
    Scanner entrada = new Scanner(System.in);
    
        String produto = "";
        int quantidade;
        double preco = 0.0;

        System.out.println("Padaria do Jão:");
        System.out.println("Escolha um produto");
        System.out.println("1 - Pão");
        System.out.println("2 - Queijo");
        System.out.println("3 - Café");
        System.out.print("Opção: ");
        int opcao = entrada.nextInt();

        switch (opcao) {
            case 1:
                produto = "Pão";
                preco = 1.50;
                break;
            case 2:
                produto = "Queijo";
                preco = 20.00;
                break;
            case 3:
                produto = "Café";
                preco = 5.00;
                break;
            default:
                System.out.println("Opção inválida.");
                System.exit(1);
        }

        System.out.print("Digite a quantidade adquirida de " + produto + ": ");
        quantidade = entrada.nextInt();

        double total = quantidade * preco;
        double desconto = 0.0;

        if (quantidade <= 5) {
            desconto = total * 0.02;
        } else if (quantidade <= 10) {
            desconto = total * 0.03;
        } else if (quantidade < 30) {
            desconto = total * 0.05;
        } else {
            desconto = total * 0.10;
        }

        double totalAPagar = total - desconto;

        System.out.println("Produto: " + produto);
        System.out.println("Quantidade adquirida: " + quantidade);
        System.out.println("Preço unitário: R$ " + preco);
        System.out.println("Total: R$ " + total);
        System.out.println("Desconto: R$ " + desconto);
        System.out.println("Total a pagar: R$ " + totalAPagar);

    
  }
}



