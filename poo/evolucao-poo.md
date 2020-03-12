# Evolução da OO

> **Abstração**: Transformção em objetos e criação de relações para representar o problema.

## Modelos de abstração

- **Programação Estruturada**: *top-down*

    -Decomposição funcional (decompor o problema em funções). 
    > Ex: cadastrar()

    - Vantagens
      - Intuitivo
    
    - Desvantagens
      - Descreve apenas a solução, não o problema
      - Entendimento da solução
      - Manutenção
      - Reutilização
      - Quanto maior, mais difícil
      - Dispersão de dados e funções
      - Dados podem ser lidos e modificados por qualquer função(desordenado)
      - Construção mais confusa
    
    - Decomposição de um problema
      - Funcionalidades
        - Criar disciplinas
        - Matricula
        - Notas
        - Calculos com notas
        - Faltas
      - Funções acessam dados

- **Programção Orientada a Objetos**

    - Tentar simular o mundo real e o mundo virtual.

    - Primeiro se tenta modelar os objetos para depois pensar em como se relacionam.
    > **Objetos**: pequena parte do problema, com informações específicas(dados), estados e operações a serem executadas.

    - O código fica menos acoplado.

    - **Exemplo de problema**: *gestão acadêmica*

        - Componentes do problema
            - Disciplinas
            - Alunos
            - Matrículas

        - Comunicação entre componentes
            - Mensagens
    
    - Vantagens
        - Mais intuitivo: Bom para o cliente e bom para o analista e desenvolvedor.
        - Mais fácil de manter e atualizar.
        - Mais coesa.
        - Maneira mais fácil de pensar
        - *Caixa Preta*: onde eu vou guardar a definição dos procedimentos.
        - Dados e funcionalidades encapsuladas:
            - Controle de acesso dos objetos.
            - Quem exerga quem. *(global, local, public e private)*.
        - Independência de código.
        - **Reutilização de código!!!!!!!!.**
            

## Programa em Linguagem O.O

> **Definição**: Conjunto de objetos dizendo uns parta os outros o que fazer através do envio de mensagens.

- Cada objeto possui:
    - Um **tipo**: isto é, pertencem a uma classe.

- Cada objeto possui:
    - Identidade
    - Estado
    - Comportamento

- Transferência de reponsabilidade do procedimento para o própio dado *(objeto)*

## Programação Tradicional X O.O ##

- Programação Tradicional
  - Dados e programa: entidades diferentes e separadas
  - Duas partes: dados e funções

- OO
  - Dados e procedimentos: parte de um só elemento básico *(objeto)*
  - Duas partes (dados e funções) em um só objeto


> Ex: {atributos: ..., métodos: ...}

- **Código Enxuto**
  - Sistemas o.o, não precisa pensar em loops ou desvios, mas sim em eventos
  - Alterações funcionam de maneira mais simples