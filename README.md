# Arquitetura de Computadores - Ficha 1

## Informação do aluno

    Nome: Luis Fernando Zaninetti 11Q1

Escreve as respostas dentro dos blocos correspondentes.
Substitui as reticências pelo que é pedido em cada pergunta.
Não desformates o documento.

### P1. Identifica e descreve os principais componentes de um processador. Fornece uma breve explicação da função de cada componente

- Lista os componentes principais de um processador.
- Para cada componente, descreve o seu papel e função no processador.
- Considera componentes como unidade lógica aritmética (ALU), unidade de controlo (UC), registos internos, memória e interfaces de entrada/saída (I/O).

P1 - Resposta:

    Unidade de controlo- A unidade de controle gerencia o processamento de instruções e coordena o fluxo de dados dentro da CPU e entre outros componentes do computador. Ela tem um componente decodificador de instruções que interpreta as instruções obtidas da memória e as converte em micro-operações que a CPU pode executar. A unidade de controle direciona outros componentes da CPU para executar as operações necessárias.
   
    Registos internos- Os registos internos são pequenos locais de armazenamento de memória de alta velocidade dentro da CPU. Eles mantêm os dados nos quais a CPU está trabalhando no momento e facilitam o acesso rápido aos dados. As CPUs têm vários tipos de registradores, como estes:

    ALU (unidade lógica aritmética)- A unidade lógica aritmética realiza operações aritméticas básicas (adição, subtração, multiplicação e divisão) e operações lógicas (AND, OR e NOT) nos dados. Ela recebe dados de registradores dentro da CPU, processa-os com base nas instruções da unidade de controle e produz o resultado.

    Memória- Dependendo da arquitetura da CPU, pode haver uma unidade de interface de barramento separada ou uma unidade de gerenciamento de memória. Esses componentes lidam com tarefas relacionadas à memória, como o gerenciamento da interação entre a CPU e a RAM. A unidade também lida com a memória do cache, uma unidade de memória pequena e rápida que está localizada dentro da CPU, e a memória virtual que a CPU requer para o processamento de dados.

    Interfaces de entrada/saída- é um termo utilizado quase que exclusivamente no ramo da computação (ou informática), indicando entrada (inserção) de dados por meio de algum código ou programa, para algum outro programa ou hardware, bem como a sua saída (obtenção de dados) ou retorno de dados, como resultado de alguma operação de algum programa, consequentemente resultado de alguma entrada.

    Relógio- A CPU depende de um sinal de relógio para sincronizar suas operações internas. O relógio gera um pulso constante em uma frequência específica e esses ciclos de relógio coordenam as operações da CPU. A velocidade do relógio é medida em hertz (Hz) e determina quantas instruções a CPU pode executar por segundo. As CPUs modernas têm velocidades de relógio variáveis, que se ajustam com base na workload para equilibrar a performance e o consumo de energia.

### P2. Compara as arquiteturas de Von Neumann e Harvard em termos de características e principais diferenças

- Lista as principais características da arquitetura Von Neumann.
- Lista as principais características da arquitetura de Harvard.
- Explica as principais diferenças entre as duas arquiteturas, particularmente na organização da memória, busca de instruções e separação de dados.
- Fornece exemplos de sistemas de computação que usam cada arquitetura.

P2 - Resposta:

    Características da Arquitetura de Von Neumann:
    Proposta nos anos 40;
    Computadores ainda baseados em válvulas de vácuo;
    Funções específicas, impróprios para resolução de problemas gerais;
    Contribuiu significativamente para o desenvolvimento dos computadores;
    Introduziu a utilização da memória, com programas nela residentes;
    Utiliza a linguagem binária e realiza processos com operações bit a bit;
    Minimiza os recursos necessários;


    Características da Arquitetura de Harvard:
    Apareceu pela primeira vez no computador Mark I, completado em ;
    Possui duas memórias diferentes e independentes em termos de barramento;
    Acede à memória de dados separadamente da memória de um programa;
    Usada em processadores de sinal digital // DSP (Digital Signal Processor);



    

### P3. Descreve o ciclo *fetch-decode-execute* num processador, detalhando cada etapa e explicando a sua importância na execução de programas de computador

- Fornece uma explicação detalhada da fase de busca de instrução, incluindo o que ela envolve e por que é importante na operação do processador.
- Explica a fase de descodificação e o seu papel na interpretação das instruções de execução.
- Descreve a fase de execução, destacando a execução propriamente dita das instruções e quaisquer interações com dados.
- Conclui explicando a ordem destas fases e como elas garantem a execução adequada dos programas de computador.
- Usa um diagrama para ilustrar o ciclo.

P3 - Resposta:

        Fetch (Buscar): Nesta etapa, a CPU busca a próxima instrução na memória. Isso geralmente envolve a leitura da instrução da memória principal (RAM) ou da memória cache para a CPU. A localização da próxima instrução é determinada pelo contador de programa, que mantém o endereço da próxima instrução a ser executada.
    
    Decode (Decodificar): Após a instrução ser recuperada, a CPU a decodifica. Isso envolve a interpretação da instrução para determinar qual operação deve ser realizada e quais operandos (dados) estão envolvidos. O decodificador converte a instrução em sinais que controlam outras partes da CPU para executar a operação desejada.
    
    Execute (Executar): Com a instrução decodificada, a CPU realiza a operação especificada. Isso pode envolver a manipulação de dados, a transferência de informações entre registradores ou até mesmo o desvio do fluxo de controle do programa, dependendo da natureza da instrução. A execução efetiva da instrução é o cerne do processamento de dados.
    
        Essas etapas se repetem continuamente na seguinte ordem, Fetch--> Decode--> Execute, com a CPU buscando, decodificando e executando instruções sequencialmente. Esse ciclo é crucial para a execução de programas de computador, pois cada instrução é uma parte do código do programa que, quando combinada com outras, realiza tarefas complexas.

 ![imagem](https://i.ytimg.com/vi/xs5oq-i_rTc/maxresdefault.jpg)

    

    

