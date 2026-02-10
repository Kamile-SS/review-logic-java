# Entrada e Saída de dados (I/O) em Java

Basicamente é a forma como seu programa recebe informações **(entrada)** e como ele mostra informações **(saída)**.

---

1) Saída 

    O objetivo **System.out** representa saída padrão, permitindo exibir dados no console quando executamos uma aplicação em Java. O system.out possui diversos métodos para gerar saídas, sendo os mais utilizados os métodos **println**, **printf** e **print**. 

   
    ## ✅ Métodos println()

    O método system.out.println() gera uma string de texto, cria uma nova linha abaixo da atual então posiciona o cursor nesta linha.

    **Exemplos:**

    ```
    System.out.println("Kamile e Duda lindonas");
    system.out.println("Saudade lu e soph vei podi")
    ```

    ## ✅ Métodos printf()

    O método system.out.printf() mostra os dados na saída formatados. Um especificados de formato se inicia com o simbolo %, seguido por um caractere que representa um tipo de dado.

    **Exemplos:**

    ```
    Double numDecima = 23.8954;
    int minhaIdade = 18;
    String meuNome = "DUda e mile";
    char gremio = 'G';

     System.out.printf("Numero = %.2f%n", numDecimal);
     System.out.printf("MinhaIdade = %.2f%n", minhaIdade);
     System.out.printf("Meu Nome = %.2f%n", meuNome);
     System.out.printf("Primeira Letra = %.2f%n", gremio);

     ```