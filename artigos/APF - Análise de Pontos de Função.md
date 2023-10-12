# APF - Análise de Pontos de Função - Exemplo Prático

*Por Rubens Lyra, Professor, Pesquisador e Entusiasta da Tecnologia e da Música*

**LinkedIn:** [@rubenslyra](https://www.linkedin.com/in/rubenslyra)  
**GitHub:** [@rubenslyra](https://github.com/rubenslyra)  
**YouTube:** [@devresolve](https://www.youtube.com/c/devresolve)

A análise de pontos de função (APF) é uma metodologia amplamente reconhecida para medir o tamanho e a funcionalidade de um software. A APF é especialmente útil quando se trata de medir o software com base em sua funcionalidade e nos dados de entrada e saída. Neste artigo, abordaremos o conceito de APF e forneceremos um exemplo prático de como aplicá-lo.

## Introdução à Análise de Pontos de Função (APF)

A Análise de Pontos de Função é uma técnica de medição que se concentra na funcionalidade entregue pelo software, independentemente de como ela é implementada ou quais tecnologias são utilizadas. Em vez de medir o software em termos de linhas de código ou horas de trabalho, a APF avalia a funcionalidade do software com base nas interações do usuário e nos requisitos funcionais.

O principal objetivo da APF é fornecer uma medida padronizada e objetiva do tamanho do software, o que é essencial para estimar o esforço necessário, planejar prazos e recursos e gerenciar custos.

## Componentes da Métrica APF

A métrica de APF considera dois componentes principais:

1. **Funções de Dados (Fator I)**: As Funções de Dados representam a funcionalidade do software relacionada à manutenção dos dados. Elas são divididas em:

   - **Arquivos Lógicos Internos (ALI)**: Representam conjuntos de dados mantidos internamente pelo sistema.
   - **Arquivos de Interface Externa (AIE)**: Representam conjuntos de dados mantidos externamente, mas referenciados pelo sistema.

   Cada ALI e AIE é pontuado com base em critérios como o número de tipos de dados, o número de registros, o número de campos, entre outros.

2. **Funções de Transação (Fator II)**: As Funções de Transação representam a funcionalidade do software relacionada à entrada e saída de dados. Elas são divididas em:

   - **Entradas Externas (EE)**: Representam processos nos quais os dados são lidos e atualizados.
   - **Saídas Externas (SE)**: Representam processos nos quais os dados são exibidos para os usuários.
   - **Consultas Externas (CE)**: Representam processos de consulta que não atualizam os dados.

   Cada EE, SE e CE é pontuado com base em critérios como o número de itens de dados referenciados e a complexidade do processamento.

## Exemplo Prático

Vamos ilustrar a aplicação da Análise de Pontos de Função com um exemplo prático. Suponhamos que estamos desenvolvendo um sistema de gerenciamento de tarefas.

1. **Funções de Dados (Fator I)**

   - **Arquivos Lógicos Internos (ALI)**:
     - Lista de Tarefas: 2 pontos (baseado no número de campos, registros, etc.)
     - Histórico de Tarefas: 3 pontos

   - **Arquivos de Interface Externa (AIE)**:
     - Usuários Externos: 2 pontos
     - Categorias de Tarefas: 3 pontos

   Total Fator I (Funções de Dados): 10 pontos

2. **Funções de Transação (Fator II)**

   - **Entradas Externas (EE)**:
     - Criação de Tarefa: 4 pontos
     - Atualização de Tarefa: 5 pontos

   - **Saídas Externas (SE)**:
     - Visualização de Tarefas: 3 pontos

   - **Consultas Externas (CE)**:
     - Busca de Tarefas: 3 pontos

   Total Fator II (Funções de Transação): 15 pontos

3. **Total de Pontos de Função**

   O total de pontos de função é a soma dos pontos de Fator I e Fator II:

   Total de Pontos de Função = Fator I + Fator II
   Total de Pontos de Função = 10 pontos + 15 pontos
   Total de Pontos de Função = 25 pontos

## Cálculo do Esforço

Com o total de pontos de função (25 pontos) em mãos, podemos utilizar uma fórmula para calcular o esforço necessário para o projeto. A fórmula pode variar de acordo com os padrões e práticas da organização, mas geralmente envolve a conversão dos pontos de função em horas de trabalho com base em uma taxa de produtividade média da equipe.

*Nota: A fórmula exata e a taxa de produtividade devem ser fornecidas pela organização ou pelo padrão que está sendo seguido.*

## Conclusão

A Análise de Pontos de Função (APF) é uma técnica valiosa para medir o tamanho e a funcionalidade de um software de forma padronizada e objetiva. Ela fornece uma base sólida para estimativas de esforço, planejamento de recursos e custos. Ao aplicar a APF, os desenvolvedores e gerentes de projeto podem tomar decisões informadas e melhorar a eficiência no desenvolvimento de software.

*Nota: Este artigo apresenta uma introdução simplificada à Análise de Pontos de Função. Para uma aplicação completa e detalhada, consulte as referências e recursos adicionais.*

**Referências:**

- [International Function Point Users Group (IFPUG)](https://www.ifpug.org/)
- [ISO/IEC 20926:2009 - Software and Systems Engineering -- Software Measurement -- IFPUG Functional Size Measurement Method](https://www.iso.org/standard/45133.html)
