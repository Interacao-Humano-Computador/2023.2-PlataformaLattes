<p align="justify">
A Análise de Tarefas é utilizada para ser um entendimento sobre qual o trabalho dos usuários, como eles realizam e por quê. Nessa análise o trabalho é definido em termos de objetivos que os usuários precisam antingir.
</p>

<p align="justify">
Diaper (2003) define a análise de tarefas como uma abordagem na ergonomia e Interação Humano-Computador (IHC) que envolve coletar, classificar e interpretar dados sobre o desempenho de sistemas que incluem pelo menos uma pessoa como componente.
</p>

Essa análise pode ser usada em três atividades principais: 

- Analisar a situação atual, 
- Redesenhar sistemas computacionais 
- Avaliar intervenções que envolvem sistemas computacionais. 

<p align="justify">
O processo de análise de tarefas começa com a identificação de um conjunto de objetivos dos usuários, estes, definidos em termos psicológicos . Para cada objetivo, são listadas as ações realizadas pelos agentes, incluindo interações físicas e com sistemas computacionais. Se houver vários agentes, suas ações são representadas em colunas separadas.
</p>

<p align="justify">
É importante observar que, independentemente da forma como os dados são coletados, a análise de tarefas oferece apenas uma simulação das tarefas reais. Existem inúmeras tarefas realizadas por diferentes pessoas, mas apenas algumas são selecionadas para análise. Além disso, apenas uma pequena parte do trabalho pode ser observada, tornando os dados sempre incompletos.
</p>

O grupo decidiu fazer o uso de dois métodos para a análise de tarefas, sendo eles:

- Análise Hierárquica de Tarefas (HTA);
- ConcurTask Tree (CTT).

## HTA - Análise Hierárquica de Tarefa
A metodologia consiste em quebrar as tarefas em sub-tarefas, e estas por sua vez em sub-sub-tarefas e assim por diante.

A análise hierárquica de tarefas possui os seguintes elementos:

- **Tarefa:** Uma parte específica de um trabalho a ser realizada.

- **Objetivo:** Um estado final desejado, que pode ser definido por eventos ou valores fisicamente observáveis.

- **Sub-objetivo:** Um objetivo de alto nível que é dividido em subobjetivos menores. Por exemplo, o objetivo "iniciar uma partida de xadrez" pode ser dividido em subobjetivos, como "definir o tipo de oponente", "escolher a modalidade de jogo" e "configurar o incremento".

- **Plano:** Um conjunto organizado de subobjetivos que precisam ser alcançados para atingir um objetivo maior. Um plano é composto por subobjetivos e suas relações.

- **Operação:** As operações envolvem as circunstâncias de ativação do objetivo (entrada), as atividades ou ações necessárias para alcançá-lo e as condições que indicam que o objetivo foi alcançado (feedback).

Esta análise pode ser implementada em formato de tabela, ou por um diagrama conforme a notação a seguir:




<div align="center">
    <img src="https://raw.githubusercontent.com/Interacao-Humano-Computador/2023.2-PlataformaLattes/main/docs/An%C3%A1lise%20de%20Requisitos/assets/elementos_hta.png" style="width:60vw"/>
    <p> Figura 1 - Elementos HTA - Faixa etária. Fonte: Autores </p> 
</div>

## Análise de Tarefas

Para a resolução das análises de tarefas hierárquicas foi selecionado a ação de Buscar currículo presente no site

## Buscar currículo

Nessa tarefa o usuário tem o objetivo de buscar currículo conforme dados selecionados para busca.


| Objetivos/Operações | Problemas/Recomendações |
|--------------------|------------------------|
| 0.0 Buscar currículo | **Input:** Acesso à opção "Buscar currículo" na tela inicial do site <br> **Feedback:** Tela de busca com informações e campos em branco <br> **Plano:** Definir como a busca por currículo pode ser aprimorada |
| 1.0 Busca Normal  | plano: definir tipo de busca  |
| 2.0 Busca avançada  | plano: definir tipo de busca  |
| 1.1 Busca nome |   |
| 1.2 Busca assunto |   |
| 2.1 Construir consulta   |              |
| 2.2 Aplicar filtros   |    |
| 1.3 Aplicar filtros/referências  |   |

Tabela 1: Tabela da análise hierárquica de tarefas para o objetivo "Buscar currículo" (Fonte: Caio Lucas)


<div align="center">
    <img src="https://raw.githubusercontent.com/Interacao-Humano-Computador/2023.2-PlataformaLattes/main/docs/An%C3%A1lise%20de%20Requisitos/assets/buscar_curriculo.jpg">
    <p> Figura 3: Diagrama da análise hierárquica de tarefas para o objetivo "Buscar currículo" (Fonte: Caio Lucas) </p> 
</div>
    

## **Bibliografia**

> [1] Barbosa, Simone Diniz Junqueira Interação humano-computador / Simone Diniz Junqueira Barbosa, Bruno Santana da Silva. – Rio de Janeiro: Elsevier, 2010. Disponível em:  https://www.amazon.com.br/Intera%C3%A7%C3%A3o-Humano-Computador-Simone-Junqueira-Barbosa/dp/8535234187 


| Versão | Data       |       Descrição      | Autor | Revisor |
|:------:|:----------:|----------------------|-------|---------|
| 1.0    | 16/10/2023 | Criação Análise de tarefas | Caio Lelis| - |
| 1.0    | 16/10/2023 | Análise hierárquica de tarefas | Caio Lelis e Joel | - |