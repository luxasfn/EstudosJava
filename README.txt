- Variáveis e Tipos de Dados
    
    Compreender o conceito de variáveis e os dados que elas armazenam.
    
    Pensando em uma rua com casas, a rua representaria a memoria e as casas são as variáveis.
    
- Classe String
    
    Reconhecer o tipo String e sua distinção com os demais tipos de dados.
    
    Obtendo o comprimento = length() “comprimento”
    
    Juntando duas String = concat() “concatenar”
    
    Comparando duas strings = equals() “é igual a”
    
    Extraindo substring = substring() 
    
    Verificar se uma string está em outra string = contains() “contém”
    
    Substituir string = replace() “substituir”
    
    ```java
    class Main {
      public static void main(String[] args) {
        String texto = "descomplica - Java";
    		
    											//verifica se a variável texto contém "Java"
        System.out.println(texto.contains("Java"));
    											//conta o comprimento da variável texto
        System.out.println(texto.length());
      }
    }
    ```
    
- Entrada e Saída
    
    Compreender as operações de entrada e saída de dados.
    
    System = pertence a biblioteca de JAVA 
    
    out = Saida
    
    print = mostrar na tela
    
    System.out.println() ln = line o conteúdo será apresentado na tela com quebra de linha
    
    System.out.print() não irá pular linha
    
    System.out.printf() também não tem quebra de texto
    
    class main = arquivo principal
    
    public static void main = método principal
    
    ```java
    import java.util.Scanner;
    
    class Main {
      public static void main(String[] args) {
        System.out.println("Salve, Mundo!");
        System.out.print("Informe seu nome:");
    
        String palavra;
    		//input
        Scanner entrada = new Scanner(System.in);
        palavra = entrada.next();
    
        System.out.println("Palavra: " + palavra);
        
        
      }
    }
    ```
    
- Operadores Aritméticos
    
    Conhecer os operadores aritméticos e como podem ser empregados em um algoritmo.
    
    | Operador | Significado | Exemplo |
    | --- | --- | --- |
    | + | Some dois operandos | x + y + 2 |
    | - | Subtraia o operando direito do esquerdo | x - y - 2 |
    | * | Multiplique dois operandos | x * y |
    | / | Divida o operando esquerdo pelo direito (Sempre resulta em flutuante) | x / y |
    | % | Módulo - resto da divisão do operando esquerdo pelo direito | x% y (resto de x / y) |
    
    Double = tipo de variável que recebe dados numéricos, valores decimais e dados do tipo float
    
    ```java
    class Main {
      public static void main(String[] args) {
        double numA, numB, total1, total2, total3;
        numA = 8;
        numB = 3;
        
    
        total1 = numA + numB;
        total2 = numA * numB;
        total3 = numA % 2;
        
        System.out.println("Operadores Aritméticos");
        System.out.println(total1);
        System.out.println(total2);
        System.out.println(total3);
            
      }
    }
    ```
    
     
    
- Estrutura Sequencial
    
    Entender os conceitos do paradigma imperativo e sua estrutura sequencial de programação.
    
    O código em Java precisa seguir uma sequência de declarações 
    
    Bibliotecas = import x
    
    arquivo = class main {}
    
    método = public static void
    
    variáveis e declaração de tipo
    
    valor 
    
    funções
    
    ```java
    //bliotecas usadas
    //arquivo 
    class Main {
      //método principal
      public static void main(String[] args) {
        //declaração das variáveis
        double base, altura, area;
        //valor das variáveis
        base = 10;
        altura = 8;
    
        //calculo da area
        area = base * altura / 2;
        //método
        System.out.println(area);
      }
    }
    ```
    