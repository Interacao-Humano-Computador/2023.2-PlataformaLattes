## **Árvore de Tarefas Concorrentes**

A ConcurTask Tree, abreviada como CTT, é uma técnica utilizada no campo da Interação Humano-Computador (IHC) para modelar e analisar tarefas que os usuários realizam em sistemas computacionais. Essa abordagem é particularmente útil para entender como os usuários interagem com sistemas complexos e identificar possíveis problemas de usabilidade.

### **Nomenclaturas utilizadas**

A nomenclatura dos diagramas separa-se, basicamente, em dois conceitos importantes para efetuar corretamente a leitura do diagrama: *especificação de tarefas* e *especificação de relações entre tarefas*

#### *Especificação de Tarefas*

Existem 4 tipo de tarefas

- Tarefa do usuário: são tarefas realizadas fora do sistema
- Tarefa do sistema: são processamentos que o sistema faz sem interagir com o usuário
- Tarefa interativas: são tarefas que acontecem através da interação entre o sistema e o usuário
- Tarefa abstratas: São a representação da composição de tarefas que dá auxilio a decomposição

#### **Especificação de relações entre tarefas**

Segundo Barbosa e Diniz (2021), existem 8 tipos de relações entre tarefas no diagrama CTT, contudo, no trabalho nos limitamos a utilizar apenas 4 tipos de relações, que são:

• *Ativação*:	T1	>>	T2	significa	que	a	segunda	tarefa	(T2)	só	pode	iniciar	
após	a	primeira	tarefa	(T1)	terminar

• *Ativação	com	passagem	de	informação*:	T1	[	]	>>	T2	especifica	que,	
além	de	T2	só	poder	ser	iniciada	após	T1,	a	informação	produzida	
por	T1	é	passada	para	T2

• *Escolha (tarefas	alternativas)*:	T1	[	]	T2	especifica	duas	tarefas	que	
estejam	habilitadas	num	momento,	mas	que,	uma	vez	que	uma	
delas	é	iniciada,	a	outra	é	desabilitada

• *Tarefas	concorrentes*:	T1	|||	T2	especifica	que	as	tarefas	podem	ser	
realizadas	em	qualquer	ordem	ou	ao	mesmo	tempo




<div align="center">
    <img src="../assets/CTTRelacoes.png.png" style="width:40vw"/>
    <p> Figura 3 - Especificações do CTT. Fonte: Autores </p> 
</div>

### **Motivação da escolha**

Optamos por empregar este método na análise das seguintes ações: "Cadastrar currículo," "Atualizar currículo," e "Buscar currículo." A razão para essa escolha reside no fato de que todas essas atividades requerem interações entre o usuário e o sistema. A abordagem da "Árvore de Tarefas Concorrentes" tem a capacidade de estruturar essas interações de forma hierárquica e, simultaneamente, estabelecer uma ordem cronológica para elas. Isso resulta em uma apresentação mais clara e organizada das tarefas.


### **Análise de Tarefa CTT 1: Cadastrar currículo**

A tarefa "Cadastrar currículo" consiste basicamente em inserir as informações do usuário no sistema para que essas informações sejam salvas e disponibilizadas na plataforma. Na figura 4 está a análise detalhada representada em diagrama.


<div align="center">
    <img src=" ../assets/CTTCadastrarCurriculo.png" style="width:40vw"/>
    <p> Figura 4 - Análise da Tarefa de "Cadastrar currículo". Fonte: Autores </p> 
</div>

### *Análise de Tarefa CTT 2: Atualizar currículo*

A tarefa "Atualizar currículo" consiste basicamente em editar as informações do usuário já cadastradas anteriormente no sistema. Na figura 5 está a análise detalhada representada em diagrama.


<div align="center">
    <img src="../assets/CTTAtualizarCurriculo.png" style="width:40vw"/>
    <p> Figura 5 - Análise da Tarefa de "Atualizar currículo". Fonte: Autores </p> 
</div>


### **Análise de Tarefa CTT 3: Buscar currículo**

A tarefa "Buscar currículo" consiste basicamente em buscar as informações de um usuário já cadastrado anteriormente no sistema. Na figura 6 está a análise detalhada representada em diagrama.


<div align="center">
    <img src="../assets/CTTBuscarCurriculo.png" style="width:40vw"/>
    <p> Figura 6 - Análise da Tarefa de "Buscar currículo". Fonte: Autores </p> 
</div>

### **Análise de Tarefa CTT 4: Buscar instituição**

A tarefa "Buscar instituição" consiste basicamente em buscar as informações de uma instituição já cadastrada anteriormente no sistema. Na figura 7 está a análise detalhada representada em diagrama.


<div align="center">
    <img src="../assets/buscar_Instituicao.png" style="width:40vw"/>
    <p> Figura 7 - Análise da Tarefa de "Buscar instituição". Fonte: SOARES, Joel </p> 
</div>

### **Análise de Tarefa CTT 5: Depositar pesquisa**

A tarefa "Depositar pesquisa" consiste basicamente em depositar uma pesquisa no sistema. Na figura 8 está a análise detalhada representada em diagrama.


<div align="center">
    <img src="../assets/CCTDepositarPesquisa.PNG" style="width:40vw"/>
    <p> Figura 8 - Análise da Tarefa de "Depositar pesquisa". Fonte: BASILIO, Guilherme </p> 
</div>

### **Análise de Tarefa CTT 5: Buscar pesquisa**

A tarefa "Consiste pesquisa" consiste basicamente em buscar uma pesquisa depositada no sistema. Na figura 9 está a análise detalhada representada em diagrama.

<div align="center">
    <img src="../assets/CTTBuscarPesquisa.png" style="width:40vw"/>
    <p> Figura 9 - Análise da Tarefa de "Buscar pesquisa". Fonte: de Frias, Miguel </p> 
</div>



## **Bibliografia**

> [1] Barbosa, Simone Diniz Junqueira Interação humano-computador / Simone Diniz Junqueira Barbosa, Bruno Santana da Silva. – Rio de Janeiro: Elsevier, 2010. Disponível em:  https://www.amazon.com.br/Intera%C3%A7%C3%A3o-Humano-Computador-Simone-Junqueira-Barbosa/dp/8535234187 



## **Histórico de Versões**

| Versão |          Descrição              |     Autor      |      Data      |   Revisor     |    Data de revisão    |  
|:------:|:-------------------------------:|:--------------:|:--------------:|:-------------:|:---------------------:|
|  1.0   | Criação Análise de tarefas |   Caio Lelis   |   16/10/2023   | Caio Braga  |       16/10/2023      |
|  1.1   | Adição HTA |   Caio Lelis e Joel   |   16/10/2023   | Guilherme  |       16/10/2023      |
|  1.2   | Adição do CTT |   Caio Braga   |   16/10/2023   |  Gabriel  |       16/10/2023      |
|  1.3   | Adicionando CTT de "Buscar Instituição" |   Joel Soares   |   22/10/2023   |  Miguel de Frias e Guilherme Basilio  |   23/10/2023      |
|  1.4   | Adicionando CTT de "Depositar Pesquisa" |   Guilherme Basilio  |   23/10/2023   |  Miguel de Frias e Guilherme Basilio  |  23/10/2023      |
|  1.5   | Adicionando CTT de "Buscar Pesquisa" |   Miguel de Frias |   23/10/2023   |  Miguel de Frias e Guilherme Basilio  |  23/10/2023      |