# UCP - Use Case Points - Pontos de Casos de Uso - Exemplo Prático

*Por Rubens Lyra, Professor, Pesquisador e Entusiasta da Tecnologia e da Música*

**LinkedIn:** [@rubenslyra](https://www.linkedin.com/in/rubenslyra)  
**GitHub:** [@rubenslyra](https://github.com/rubenslyra)  
**YouTube:** [@devresolve](https://www.youtube.com/c/devresolve)

Quando se trata de desenvolvimento de software, a medição do esforço e custo envolvidos em um projeto é uma tarefa crítica. Entender a complexidade e os requisitos do projeto é essencial para a alocação de recursos e o planejamento adequado. Uma das abordagens mais eficazes para medir projetos orientados a objetos é o método de Gustav Karner, que introduziu o conceito de *Use Case Points* (Pontos de Casos de Uso - UCP). Neste artigo, exploraremos esse método e forneceremos um exemplo prático de como aplicá-lo.

## Método de Gustav Karner

O método de Gustav Karner é uma técnica amplamente utilizada para quantificar projetos de desenvolvimento de software orientados a objetos. Ele se concentra na avaliação da funcionalidade do software, com um foco especial nos casos de uso. O objetivo é traduzir a complexidade do software em uma métrica que pode ser usada para estimar o esforço necessário para o desenvolvimento e, consequentemente, seu custo.

O método de Karner se baseia em três principais componentes:

1. **APR (Atividades de Programação Reutilizáveis)** - Esse componente avalia a quantidade de código reutilizável no projeto. Quanto maior a reutilização, menor o esforço de desenvolvimento necessário.

2. **UCP (Use Case Points - Pontos de Casos de Uso)** - Este é o cerne do método e se concentra nos casos de uso do sistema. Os casos de uso são analisados para determinar seu peso em termos de complexidade e esforço de desenvolvimento.

3. **TCF (Technical Complexity Factors - Fatores de Complexidade Técnica)** e **EF (Environmental Factors - Fatores de Ambiente)** - Estes fatores levam em consideração a complexidade técnica do projeto, bem como o ambiente em que ele será desenvolvido.

## Objetivo: Medir Projetos Orientados a Objetos

O objetivo da aplicação do método UCP é medir e quantificar projetos orientados a objetos, a fim de estabelecer o custo do projeto. A métrica UCP é especialmente útil em ambientes de desenvolvimento de software em que os requisitos não estão totalmente definidos desde o início, uma vez que os casos de uso podem ser avaliados à medida que são identificados e elaborados.

## Componentes da Métrica UCP

### 1. UCP - Pontos de Casos de Uso

Os Casos de Uso são o cerne do método UCP. Cada caso de uso é avaliado em termos de três aspectos:

- **Complexidade Simples (CS)**: Casos de uso simples e diretos.
- **Complexidade Média (CM)**: Casos de uso moderadamente complexos.
- **Complexidade Complexa (CC)**: Casos de uso complexos e intrincados.

A pontuação é atribuída com base em critérios específicos, como o número de transações, tipos de operações e interfaces envolvidas em cada caso de uso. Cada nível de complexidade é atribuído a uma pontuação, por exemplo, CS = 5, CM = 10 e CC = 15.

### 2. TCF - Fatores de Complexidade Técnica

Os fatores de complexidade técnica levam em consideração aspectos técnicos do projeto que afetam o esforço de desenvolvimento. Esses fatores incluem:

- **Arquitetura de Software**
- **Desempenho**
- **Usabilidade**
- **Facilidade de Instalação**
- **Facilidade de Mudanças**
- **Integração com Outros Sistemas**

Cada fator é avaliado em uma escala de 0 a 5, onde 0 representa nenhuma influência e 5 representa uma influência muito alta.

### 3. EF - Fatores de Ambiente

Os fatores de ambiente levam em consideração aspectos externos ao projeto que afetam o desenvolvimento. Estes podem incluir:

- **Experiência da equipe**
- **Ferramentas e processos de desenvolvimento**
- **Pressão do cronograma**
- **Recursos disponíveis**

Cada fator é avaliado em uma escala de 0 a 5, onde 0 representa nenhuma influência e 5 representa uma influência muito alta.

## Exemplo Prático

Vamos ilustrar a aplicação do método UCP com um exemplo prático. Suponhamos que estamos desenvolvendo um sistema de gerenciamento de biblioteca.

1. **Pontos de Casos de Uso (UCP)**

   - Caso de Uso 1 (Cadastro de Livro) - Complexidade Média (CM) - Pontuação: 10
   - Caso de Uso 2 (Empréstimo de Livro) - Complexidade Média (CM) - Pontuação: 10
   - Caso de Uso 3 (Reserva de Livro) - Complexidade Simples (CS) - Pontuação: 5
   - Caso de Uso 4 (Consulta de Estoque) - Complexidade Simples (CS) - Pontuação: 5

   Total UCP: 30

2. **Fatores de Complexidade Técnica (TCF)**

   - Arquitetura de Software: 3
   - Desempenho: 2
   - Usabilidade: 4
   - Facilidade de Instalação: 2
   - Facilidade de Mudanças: 3
   - Integração com Outros Sistemas: 2

   Total TCF: 16

3. **Fatores de Ambiente (EF)**

   - Experiência da equipe: 4
   - Ferramentas e processos de desenvolvimento: 3
   - Pressão do cronograma: 2
   - Recursos disponíveis: 3

   Total EF: 12

A fórmula para calcular o esforço do projeto é a seguinte:

**Esforço (em horas) = UCP x (0,65 + 0,01 x TCF) x EF**

Substituindo os valores:

**Esforço (em horas) = 30 x (0,65

 + 0,01 x 16) x 12 = 302,4 horas**

Com essa estimativa de esforço, podemos agora planejar recursos, prazos e custos para o projeto de desenvolvimento do sistema de gerenciamento de biblioteca.

O método UCP é uma ferramenta valiosa para estimar o esforço e custo de projetos orientados a objetos. Ele permite uma abordagem estruturada para a análise de casos de uso, levando em consideração fatores técnicos e ambientais. Ao aplicar o método de Gustav Karner, os desenvolvedores e gerentes de projeto podem tomar decisões informadas e evitar surpresas desagradáveis no decorrer do projeto.

Em resumo, o UCP é uma técnica que combina a visão orientada a objetos com a realidade dos projetos de desenvolvimento de software, tornando a estimativa de esforço uma tarefa mais precisa e eficiente.

*Nota: Este artigo é uma introdução simplificada ao método UCP de Gustav Karner. Para uma aplicação completa e detalhada, consulte as referências e recursos adicionais.*

**Referências:**

- [Use Case Points (UCP) - An Introduction](https://www.tutorialspoint.com/use_case_points/index.htm)
- [Software Engineering Institute - Use Case Points](https://www.sei.cmu.edu/reports/90tr001.pdf)
- [Object Management Group - Use Case Points](https://www.omg.org/cgi-bin/doc?omg/05-07-04)
