# **Padronização do projeto**

## **Introdução** 
Usando as linguagens de marcação Markdown e HTML na qual estamos utilizando ao longo de toda a documentação do projeto faremos um documento para guardar alguns templates para ajudar na padronização colaborando para a ordem do projeto, trazendo otimização de tarefas e aumento na produtividade. 

## **Componentes**

Aqui teremos alguns componentes e seus acompanhamentos que serão padronizados pela a equipe

### **Tópicos: títulos e Subtítulos**.

Os **títulos** do projeto definem o nome do documento no mkdocs, assim sendo importante definir nomes significativo para os arquivos criados

Os **subtitulos** são definidos para informar os tópicos do documento sendo de importancia defini-los de maneira correta para evitar erros de interpretação.

 Estruturas:
# **Nome do título**
## **Nome do Subtítulo**
---

### **Legendas de Figuras/Tabelas/Etc**

Colocar logo abaixo (saltando uma linha no markdown), a seguinte estrutura:

<div style="text-align: center">
    <p> <b> Tabela X ou Figura X </b> : Descrição breve. (Fonte: Fulano de Tal, 2023).</p>
</div>

---

### **Histórico de versão: estrutura, versionamento, autores, revisores e datas.**

Trazendo informações sobre o versionamento do documento possuindo informações sobre: Versão, data que foi versionado, descrição, autor, revisor e data de revisao


- Estrutura:

| Versão |          Descrição              |     Autor      |      Data      |   Revisor     |    Data de revisão    |  
|:------:|:-------------------------------:|:--------------:|:--------------:|:-------------:|:---------------------:|
|  1.0   | Descrição sobre o versionamento |   Nome Autor   |   dd/mm/yyyy   | Nome Revisor  |       dd/mm/yyyy      |

---

### **Referência Bibliográfica: estrutura, citação, citação de autor, data e link**
Usada para trazer embasamento ao texto escrito, assim trazendo detalhamento da fonte na qual surgiu sua inspiração para escrever um determinado texto

Estrutura:

>[1] Quem escreveu o artigo, **Título do artigo**, Disponível em: <Link para o acesso >, Acesso em dd de Mês de yyyy.

---
### **Bibliografia: estrutura, nome site, data e link**
Usado para apoio da documentação, contendo link para ferramentas, sites usados e etc

> [1] "Nome do site", Disponivel em: [link ddo site], acesso em 04 de Outubro de 2023

---
### **Imagens: tag, link referênciado, padrão, legendas**.
As imagens contidas nesse documento são para melhorar visualmente ideias e trazer uma interpretação visual sobre um certo assunto.Usando a tag em html de img, trazemos o link dá imagem que deve está no repositório do github

Estrutura:

<img src = "link da imagem" width = tamanhopx>
 
---

### **Cronograma: tabelas**
O cronograma traz detalhadamente todo o planejamento e execução do grupo


| Tarefa | Período de Desenvolvimento | Atribuição | Período de Revisão | Revisor|
|--------|:--------------------------:|------------|:------------------:|--------|
| tarefa | Início: dd/mm <br> Fim: dd/mm | pessoa01 | Início: dd/mm <br> Fim: dd/mm| pessoa02 |

sendo o mesmo cronograma para o planejado e executado 


### **Estrutura do projetos: nome do arquivo, estrutura.**
Aqui temos a estruturação do arquivo que iremos trabalhar:

Estrutura:

- Cada pasta representa uma parte da entrega da disciplina
- pasta "img"-> guarda imagens referentes as entregas

---
### **Guias Github**

Aqui teremos alguns guias e padronizações da nossa ferramenta de versionamento Github, trazendo versões da documentação para a plataforma, assim todos podem contribuir de maneira rápida e correta. 

---

### **Issues:estrutura**
Issues são feitas para designar tarefas feitas em reuniões para o github, servindo de guia para a resolução de tarefas e questões 

Estrutura:
#### Descrição 
- Atributos do projeto

#### Prazo 
- Entrega : dd/mm
- Revisão : dd/mm 

---
### **Pull Request: estrutura, quando fazer, como fazer.** 
As pull request servem para solicitar a junção da branch criada com a principal,também usado para mecanismo de revisão de código pelo revisar. Sendo feito pelo revisor logo após a suposta revisão 

Estrutura:
#### **Descrição**
- branch do pull request, autor e revisor

---

### **Padronização de commit: estrutura, padrões, mensagem.**
A padronização de commit é importante para a identificação de commit's feitos durante o processo no projeto

Estrutura: git commit -m "docs: Mensagem"

--- 

### **Markdown e Html**
Aqui teremos guias para o uso das linguagens de marcação

---

### **Markdown: guia, principais conceitos.** 
Markdown é a linguagem de marcação mais usada no documento

[Guia markdown](https://docs.pipz.com/central-de-ajuda/learning-center/guia-basico-de-markdown#open)


## **Referencias Bibliograficas**

>[1] Raphael Pires, **Qual a importância da padronização de documentos?**, Disponível em: <https://rockcontent.com/br/blog/padronizacao-de-documentos/>, Acesso em : 06 de Outubro de 2023.

>[2] Awari Code, **Versionamento de código: entenda o que é e porque é importante**, Disponível em: <https://awari.com.br/versionamento-de-codigo/?utm_source=blog&utm_campaign=projeto+blog&utm_medium=Versionamento%20de%20c%C3%B3digo:%20entenda%20o%20que%20%C3%A9%20e%20porque%20%C3%A9%20importante#:~:text=Ou%20seja,%20o%20Github%20funciona,%C3%A9%20igual%20ao%20do%20Git.>, Acesso em : 06 de Outubro de 2023.

>[3] Even3, **Referência bibliográfica: como fazer e qual a sua importância**, Discponível em: <https://blog.even3.com.br/referencia-bibliografica-como-fazer-e-qual-a-sua-importancia/>, Acesso em : 07 de Outubro de 2023

>[4] Daniela Diana, **Bibliografia**, Disponível em: <https://www.todamateria.com.br/bibliografia/>, Acesso em: 07 de Outrubro de 2023

## **Histórico de Versões**

|
| Versão |          Descrição              |     Autor      |      Data      |   Revisor     |    Data de revisão    |  
|:------:|:-------------------------------:|:--------------:|:--------------:|:-------------:|:---------------------:|
| 1.0    | Criando guia de contribuição | Doan Filho | 22/10/2023 |  Caio Braga |  |