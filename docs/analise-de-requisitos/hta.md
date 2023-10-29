<p align="justify">
&emsp;&emsp;A Análise de Tarefas é utilizada para ser um entendimento sobre qual o trabalho dos usuários, como eles realizam e por quê. Nessa análise o trabalho é definido em termos de objetivos que os usuários precisam antingir.
</p>

<p align="justify">
&emsp;&emsp;Diaper (2003) define a análise de tarefas como uma abordagem na ergonomia e Interação Humano-Computador (IHC) que envolve coletar, classificar e interpretar dados sobre o desempenho de sistemas que incluem pelo menos uma pessoa como componente.
</p>

Essa análise pode ser usada em três atividades principais: 

- Analisar a situação atual, 
- Redesenhar sistemas computacionais 
- Avaliar intervenções que envolvem sistemas computacionais. 

<p align="justify">
&emsp;&emsp;O processo de análise de tarefas começa com a identificação de um conjunto de objetivos dos usuários, estes, definidos em termos psicológicos . Para cada objetivo, são listadas as ações realizadas pelos agentes, incluindo interações físicas e com sistemas computacionais. Se houver vários agentes, suas ações são representadas em colunas separadas.
</p>

<p align="justify">
&emsp;&emsp;É importante observar que, independentemente da forma como os dados são coletados, a análise de tarefas oferece apenas uma simulação das tarefas reais. Existem inúmeras tarefas realizadas por diferentes pessoas, mas apenas algumas são selecionadas para análise. Além disso, apenas uma pequena parte do trabalho pode ser observada, tornando os dados sempre incompletos.
</p>

O grupo decidiu fazer o uso de dois métodos para a análise de tarefas, sendo eles:

- Análise Hierárquica de Tarefas (HTA);
- ConcurTask Tree (CTT).

## **HTA - Análise Hierárquica de Tarefa**
&emsp;&emsp;A metodologia consiste em quebrar as tarefas em sub-tarefas, e estas por sua vez em sub-sub-tarefas e assim por diante.

A análise hierárquica de tarefas possui os seguintes elementos:

- **Tarefa:** Uma parte específica de um trabalho a ser realizada.

- **Objetivo:** Um estado final desejado, que pode ser definido por eventos ou valores fisicamente observáveis.

- **Sub-objetivo:** Um objetivo de alto nível que é dividido em subobjetivos menores. Por exemplo, o objetivo "iniciar uma partida de xadrez" pode ser dividido em subobjetivos, como "definir o tipo de oponente", "escolher a modalidade de jogo" e "configurar o incremento".

- **Plano:** Um conjunto organizado de subobjetivos que precisam ser alcançados para atingir um objetivo maior. Um plano é composto por subobjetivos e suas relações.

- **Operação:** As operações envolvem as circunstâncias de ativação do objetivo (entrada), as atividades ou ações necessárias para alcançá-lo e as condições que indicam que o objetivo foi alcançado (feedback).

Esta análise pode ser implementada em formato de tabela, ou por um diagrama conforme a notação a seguir:

<div align="center">
    <img src="../assets/elementos_hta.png" style="width:60vw"/>
    <p> Figura 1 - Elementos HTA - Faixa etária. Fonte: Autores </p> 
</div>


### **Buscar currículo**

Nessa tarefa o usuário tem o objetivo de buscar currículo conforme dados selecionados para busca.


| Objetivos/Operações | Problemas/Recomendações |
|--------------------|------------------------|
| 0.0 Buscar currículo | **Input:** Acesso à opção "Buscar currículo" na tela inicial do site <br> **Feedback:** Tela de busca com informações e campos em branco <br> **Plano:** Definir como a busca por currículo pode ser aprimorada |
| 1.0 Busca Normal  | plano: definir tipo de busca  |
| 2.0 Busca avançada  | plano: definir tipo de busca  |
| 1.1 Busca nome | plano: buscar curriculo pelo nome  |
| 1.2 Busca assunto | plano: buscar curriculo pelo nome  |
| 2.1 Construir consulta   |              |
| 2.2 Aplicar filtros   |    |
| 1.3 Aplicar filtros/referências  |   |

Tabela 1: Tabela da análise hierárquica de tarefas para o objetivo "Buscar currículo" (Fonte: Caio Lucas)


<div align="center">
    <img src="../assets/buscar_curriculo.jpg">
    <p> Figura 3: Diagrama da análise hierárquica de tarefas para o objetivo "Buscar currículo" (Fonte: Caio Lucas) </p> 
</div>
    
<br>

### **Buscar instituição**

Nessa tarefa o usuário tem o objetivo de buscar uma instituição conforme dados selecionados para busca.


| Objetivos/Operações | Problemas/Recomendações |
|--------------------|------------------------|
| 0.0 Buscar instituição | **Input:** Acesso à opção "Buscar instituição" na tela inicial do site <br> **Feedback:** Tela de Diretório de instituições <br> **Plano:** Definir como a busca por instituição pode ser aprimorada |
| 1.0 Página inicial  | **Plano:** apresentar a página "Diretório de Instituições" para o usuário  |
| 2.0 Busca  | **Plano:** definir tipo de busca  |
| 2.1 Busca pelo nome e/ou sigla | **Plano:** instituição pelo nome e/ou sigla cadastrado  |
| 2.2 Busca CNPJ | **Plano:** buscar instituição pelo CNPJ |
| 3.0 Demonstração dos resultados   | **Plano:** Demonstrar uma lista de resultados para o usuário, aonde poderá selecionar a instituição que desejar para obter mais informações             |

Tabela 2: Tabela da análise hierárquica de tarefas para o objetivo "Buscar instituição" (Fonte: Joel Soares)

### **Depositar dados de pesquisa**

Nessa tarefa o usuário tem o objetivo de depositar uma pesquisa.

| Objetivos/Operações | Problemas/Recomendações |
|--------------------|------------------------|
| 0.0 Depositar pesquisa | **Input:** Acesso à opção "Depositar pesquisa" na tela inicial do site <br> **Feedback:** Tela de depósito de pesquisa com informações e campo em branco <br> **Plano:** Definir como o depósito de pesquisa pode ser aprimorado |
| 1.0 Página inicial | **Plano:** apresentar a página de cadastro de pesquisa para o usuário |
| 2.0 Dados da pesquisa | **Plano:** Coletar informações relevantes sobre a pesquisa a ser cadastrada |
| 2.1 Título da pesquisa | **Plano:** Solicitar ao usuário que insira o título da pesquisa |
| 2.2 Resumo da pesquisa | **Plano:** Solicitar ao usuário que insira um resumo conciso da pesquisa |
| 3.0 Duração da pesquisa| **Plano:** Solicitar ao usuário que especifique o período de realização da pesquisa |
| 4.0 Anexos | **Plano:** Permitir ao usuário anexar arquivos à pesquisa, como artigos, resumos, apresentações, etc |
| 5.0 Avaliação | **Plano:** Solicitar ao usuário que avalie a relevância da pesquisa |

Tabela 3: Tabela da análise hierárquica de tarefas para o objetivo "Depositar dados de pesquisa" (Fonte: Guilherme Basilio) 

### **Buscar dados de pesquisa**

Nessa tarefa o usuário tem o objetivo de buscar dados de pesquisa conforme dados selecionados para busca.


| Objetivos/Operações | Problemas/Recomendações |
|--------------------|------------------------|
| 0.0 Buscar instituição | **Input:** Acesso à opção "Buscar dados de pesquisa" na tela inicial do site <br> **Feedback:** Tela de consulta de pesquisas <br> **Plano:** Definir como a busca por dados de pesquisa pode seer melhorada |
| 1.0 Página inicial  | **Plano:** apresentar a página "Consulta de pesquisas" para o usuário  |
| 2.0 Busca  | **Plano:** definir tipo de busca |
| 2.1 Busca pelo nome/palavra-chave | **Plano:**  buscar a pesquisa pelo nome ou palavra-chave |
| 2.2 Busca pelo autor | **Plano:** buscar pesquisa pelo autor |
| 3.0 Demonstração dos resultados   | **Plano:** Demonstrar uma lista de resultados para o usuário, aonde poderá selecionar os dados de pesquisa para obter mais informações sobre a mesma  |

Tabela 4: Tabela da análise hierárquica de tarefas para o objetivo "Buscar dados de pesquisa" (Fonte: Miguel de Frias)


### **Buscar dados de pesquisa**

Nessa tarefa o usuário tem o objetivo de buscar dados de pesquisa conforme dados selecionados para busca.


| Objetivos/Operações | Problemas/Recomendações |
|--------------------|------------------------|
| 0.0 Buscar instituição | **Input:** Acesso à opção "Buscar dados de pesquisa" na tela inicial do site <br> **Feedback:** Tela de consulta de pesquisas <br> **Plano:** Definir como a busca por dados de pesquisa pode seer melhorada |
| 1.0 Página inicial  | **Plano:** apresentar a página "Consulta de pesquisas" para o usuário  |
| 2.0 Busca  | **Plano:** definir tipo de busca |
| 2.1 Busca pelo nome/palavra-chave | **Plano:**  buscar a pesquisa pelo nome ou palavra-chave |
| 2.2 Busca pelo autor | **Plano:** buscar pesquisa pelo autor |
| 3.0 Demonstração dos resultados   | **Plano:** Demonstrar uma lista de resultados para o usuário, aonde poderá selecionar os dados de pesquisa para obter mais informações sobre a mesma  |

Tabela 4: Tabela da análise hierárquica de tarefas para o objetivo "Buscar dados de pesquisa" (Fonte: Miguel de Frias)


### **Acessar Painel Lattes**

Nessa tarefa o usuário tem o objetivo de acessar o Painel Lattes para buscar dados estatísticos sobre a plataforma.


| Objetivos/Operações | Problemas/Recomendações |
|--------------------|------------------------|
| 0.0 Acessar Painel Lattes | **Input:** Acesso à opção "Acessar Painel Lattes" na tela inicial do site <br> **Feedback:** Tela de painel de dados da Plataforma Lattes<br> **Plano:** Definir como o painel de dados estatísticos pode ser melhorado |
| 1.0 Página inicial  | **Plano:** apresentar a página "Painel Lattes" para o usuário  |
| 2.0 Filtrar  | **Plano:** definir filtro para afunilar os resultados  |
| 2.1 Filtrar por região | **Plano:** filtra o grau de escolaridade e área de estudo por região (Centro-Oeste, Sudeste, etc) |
| 2.2 Filtrar por estado | **Plano:** filtra o grau de escolaridade e área de estudo por estado (DF, GO, MG, SP, etc) |
| 2.3 Filtrar por escolaridade | **Plano:** filtra o painel pelo grau de escolaridade (Ensino Fundamental, Médio, Superior, etc) |
| 2.4 Filtrar por sexo | **Plano:** filtrar o painel pelo sexo (Masculino ou Feminino) |
| 2.5 Filtrar por faixa etária | **Plano:** filtrar o painel pela faixa etária |
| 2.6 Filtrar por grande área | **Plano:** filtrar o painel pela área de estudo (ex: Ciências Humanas e Sociais) |
| 2.7 Filtrar por setor econômico | **Plano:** filtrar o painel pela grande área do grau de escolaridade (ex: Ensino Superior Público ou Privado, Ensino Técnico, etc) |
| 3.0 Demonstração dos resultados   | **Plano:** demonstrar uma lista de resultados para o usuário, aonde poderá selecionar os dados de pesquisa para obter mais informações sobre ela |

Tabela 4: Tabela da análise hierárquica de tarefas para o objetivo "Acessar Painel Lattes" (Fonte: Caio Braga)


## **Bibliografia**

> [1] Barbosa, Simone Diniz Junqueira Interação humano-computador / Simone Diniz Junqueira Barbosa, Bruno Santana da Silva. – Rio de Janeiro: Elsevier, 2010. Disponível em:  https://www.amazon.com.br/Intera%C3%A7%C3%A3o-Humano-Computador-Simone-Junqueira-Barbosa/dp/8535234187 


## **Histórico de Versões**

| Versão |          Descrição              |     Autor      |      Data      |   Revisor     |    Data de revisão    |  
|:------:|:-------------------------------:|:--------------:|:--------------:|:-------------:|:---------------------:|
|  1.0   | Criação Análise de tarefas |   Caio Lelis   |   16/10/2023   | Caio Braga  |       16/10/2023      |
|  1.1   | Adição HTA |   Caio Lelis e Joel   |   16/10/2023   | Guilherme  |       16/10/2023      |
|  1.3   | Adicionando HTA de "Buscar Instituição" |   Joel Soares   |   22/10/2023   |  Miguel de Frias e Guilherme Basilio  |   23/10/2023      |
|  1.4   | Adicionando HTA de "Depositar Pesquisa" |   Guilherme Basilio  |   23/10/2023   |  Miguel de Frias e Guilherme Basilio  |  23/10/2023      |
|  1.5   | Adicionando HTA de "Buscar Pesquisa" |   Miguel de Frias |   23/10/2023   |  Miguel de Frias e Guilherme Basilio  |  23/10/2023      |
|  1.5   | Adicionando HTA de "Buscar Pesquisa" |   Miguel de Frias |   23/10/2023   |  Miguel de Frias e Guilherme Basilio  |  23/10/2023      |