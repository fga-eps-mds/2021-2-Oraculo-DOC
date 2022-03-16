## Políticas dos Repositórios

### Histórico de Revisão

|Data|Versão|Descrição|Autor|
|--|--|--|--|
|08/03/2022|1.0| Criação do template do documento de políticas|[Caio César Beleza](github.com/Caiocbeleza)|
|08/03/2022|1.1| Adição do tópico de introdução | [Caio César Beleza](github.com/Caiocbeleza)|
|08/03/2022|1.2| Adição do tópico da política de commits | [Caio César Beleza](github.com/Caiocbeleza)|
|08/03/2022|1.3| Adição do tópico de monitoramento | [Caio César Beleza](github.com/Caiocbeleza)|
|08/03/2022|1.4| Adição do tópico da política do repositório de documentação | [Caio César Beleza](github.com/Caiocbeleza)|
|09/03/2022|1.5| Adição do tópico da política de criação de branches | [Caio César Beleza](github.com/Caiocbeleza)|
|09/03/2022|1.6| Adição do tópico da política de criação de issues | [Caio César Beleza](github.com/Caiocbeleza)|
|16/03/2022|1.7| Adição do tópico da política de criação de pull requests | [Caio César Beleza](github.com/Caiocbeleza)|




### 1. Introdução

Este documento tem como objetivo apresentar as políticas dos repositórios envolvidos no projeto Oráculo, visando orientar tanto os membros da equipe responsáveis pelo projeto no 2º semestre de 2021 das disciplinas MDS(Métodos de Desenvolvimento de Software) e EPS(Engenharia de Produto de Software), quanto para pessoas que se interessem em contribuir com o projeto posteriormente.

### 2. Repositórios de Código

Este tópico descreve as políticas relacionadas às contribuições aos repositórios onde são encontrados os códigos do projeto, como as políticas de criação de branches e commits.


#### 2.1. Política de Branches

Os repositórios de código têm duas branches principais. A branch Master é onde estará sempre mantida a versão estável do projeto, não são permitidos commits diretamente nela. A master só será atualizada a partir da branch Develop, quando esta estiver em uma versão estável.

A branch develop será a mais atualizada, ao final de cada sprint. Ela reunirá os resultados das atividades feitas a cada sprint.


##### 2.1.1. Criação de Branches

Para cada funcionalidade e/ou correções de erro, deverá ser criada uma branch, que deve evidenciar aquela atividade. Para tal, devem ser seguidos os seguintes direcionamentos:

- O padrão para uma branch criada para uma tarefa contida no Roadmap do projeto é:

  - <mark> TF[ID da tarefa no Roadmap]-[Nome da Tarefa] </mark>


- O padrão para uma branch criada a para uma correção é:

  - <mark> FIX[Nome da correção] </mark>


- O padrão para uma branch criada a para uma issue é:

  - <mark> ISSUE[ID da issue]-[Nome da issue] </mark>



#### 2.2. Política de Commits

Para que os commits fiquem no padrão esperado, é necessário se atentar aos seguintes tópicos:

- Os commits devem ser redigidos em português.
- Os títulos de commits devem ser claros e explicativos, quanto as alterações que foram realizadas.
- Os títulos de commits devem começar com letra maiúscula.

Além disso, se forem feitas alterações com mais de um autor, o commit deve evidenciar a participação de todos os autores, com a função "Co-authored-by".



### 3. Repositório de Documentação

Os commits no repositório de documentação devem seguir o mesmo padrão dos commits dos repositórios de código. Entretanto, as documentações serão inseridas diretamente na branch Master, sem a necessidade de criação de outras branches.

Os documentos devem conter, após o título, uma tabela com o histórico de revisões feitas nesse documento, contendo a data na qual foi realizada a revisão, a nova versão do documento, a descrição da revisão realizada e o nome de quem fez as alterações.

Além disso, ao final de todo documento deve ter um tópico de referências, onde serão evidenciadas as referências que foram consultadas para a confecção do documento



### 4. Issues

As issues serão utilizadas para mapear as atividades do projeto, como histórias de usuários e correção de bugs, pela facilidade de monitoramento, já que podem ser integradas aos zenhub.

As issues ativas serão identificadas por meio de labels para melhor entendimento dos membros do time, além de pessoas que possam ter interesse em contribuir com o projeto posteriormente.

As labels que identificarão as issues são as seguintes:

- US: Representa as histórias de usuário.
- UI/UX: Representa issues que incluem refatorações no visual e usabilidade da aplicação.
- Bug: Representa issues relacionadas a correções que precisam ser feitas na aplicação.
- Doc: Representa issues relacionadas à documentações do projeto.


A criação de issues deve seguir o seguinte padrão:
- <mark> [Tipo da Atividade]-[Nome da tarefa] </mark>

As histórias de usuário devem seguir o seguinte padrão:
- <mark>[US][Número da história] - [Nome da história] </mark>


### 5. Pull Requests

- Os pull requests só serão aceitos quando feitos a partir de branches válidas.
- Os pull requests têm que apresentar título e descrição explicativos sobre o que foi realizado.
- Para que o pull request seja aceito, tem que estar passando nos testes.
- Os pull requests tem que ser revisados e aceitos por, pelo menos, 1 membro de EPS.

### 6. Monitoramento

O monitoramento dos repositórios é feito pela equipe de gerenciamento do projeto(EPS), que é responsável também por orientar e ajudar os demais membros da equipe quanto ao cumprimento dos padrões estabelecidos. Dessa forma, é reservado à equipe de gerenciamento o poder de vetar e/ou excluir o que não estiver dentro das especificações.  

### 7. Referências

- Cafofo. Plano de Gestão e Configuração de Software. Disponível em: https://github.com/desenho-2019/Wiki/blob/master/docs/Din%C3%A2mica%20e%20Semin%C3%A1rio%20II/planoDeGCS.md. Acesso em: 09/03/2022.

- QueroCultura. Plano de Gerenciamento de Configuração. Disponível em https://github.com/fga-eps-mds/2017.2-QueroCultura/wiki/Plano-de-Gerenciamento-de-Configura%C3%A7%C3%A3o. Acesso em: 09/03/2022.
