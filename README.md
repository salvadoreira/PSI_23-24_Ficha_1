# Ficha de Programação e Sistemas de Informação - Classes

Faz *fork* do repositório para teres a tua cópia.
Faz clone da tua cópia do repositório para o teu PC.
Preenche o README localmente e seguidamente faz push das atualizações.

Escreve as respostas dentro dos blocos correspondentes. Substitui as reticências pelo que é pedido em cada pergunta. Não desformates o documento.

## Informação do aluno

    Nome: Salvador Eira

## E1 - Responde às seguintes questões (4v)

    1 - As classes são tipos de referência? 
        Sim
    2 - Classes definem o que algo pode fazer e guardar, enquanto uma
        instância é um objeto específico que contém o seu próprio estado 
        (Apaga a opção entre parênteses errada)
    3 - Indica três tipos de membros que podem pertencer a uma classe 
        ...
    4 - Se algo é static então é partilhado por todas as instâncias desse tipo específico? 
        ...
    5 - Como se chamam os métodos especiais que inicializam uma classe? 
       
    6 - De onde podes aceder a algo private? 
        Membro apenas acessível dentro da classe

    7 - De onde podes aceder a algo public? 
        Membro acessível a partir de qualquer sítio

    8 - De onde podes aceder a algo internal? 
        Membro acessível dentro do mesmo projeto

## E2 - Explica por palavras tuas o significado dos seguintes termos (4v)

    1 - Classe
        Sao categorias gerais de objetos
    2 - Objeto / instância
        São casos específicos de objetos
    3 - Método
        Permitem que código externo manipule instâncias
    4 - Construtor
        Inicializam estado de novas instâncias

    5 - Variável de instância
        Definem estado de cada instância da classe

    6 - Variável local
        Variável local “oculta” variável de instância

    7 - Overloading
        Múltiplos métodos com o mesmo nome

    8 - Encapsulação
        Objetos devem manter controlo e integridade dos seus dados / estado, classe deve manter o seu estado privado.


## E3 - Cria o seguinte programa de consola (12v)

- Nome do projeto: **BolasColoridas**
  - Cria a classe **Cor** com:
    - Estado representado pelos valores **red, green, blue, alpha**
    - Construtor que aceita todos os parâmetros necessários para inicializar o estado de uma cor
    - Construtor que aceita **red, green, blue,** e coloca **alpha** a 255
    - Métodos *getter* e *setter* para os componentes **red, green, blue e alpha**
    - Método *getter* para obter o grau de cinzento da cor, igual à média dos valores **red, green e blue**
  - Cria a classe **Bola** com:
    - Estado representado pelos valores de **cor, raio e o nº de vezes que a bola foi atirada**
    - Construtores apropriados
    - Método **Pop()** que fura a bola (coloca o seu raio a zero)
    - Método **Atirar()** que incrementa o nº de vezes que a bola foi atirada (apenas se a bola não estiver furada)
    - Método que retorna o nº de vezes que a bola foi atirada
  - Na classe **Program**, método **Main**, escreve código para:
    - Criar algumas bolas
    - Atirar as bolas várias vezes
    - Rebentar algumas das bolas
    - Imprimir no ecrã o estado de cada uma (incluindo cor)
  - Faz vários *commits* ao longo do desenvolvimento e no fim faz *push* para o repositório remoto
