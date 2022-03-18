| Versão | Data       | Modificação                    | Motivo | Autor(es) |
| ------ | ---------- | ------------------------------ | :----: | ----- |
| 1.0    | 13/03/2022 | Criação do documento  | - | João Victor e Lucas Lopes |
| 1.1    | 13/03/2022 | Adição dos tópicos identificação dos riscos e analise qualitativa dos riscos | - | João Victor e Lucas Lopes |
| 1.2  | 13/03/2022 | Adição dos tópicos planejamento e monitoramento de riscos | - | João Victor e Lucas Lopes |

# Introdução 

Este documento descreve como a equipe do projeto gerenciará os riscos, funções e responsabilidades do projeto e as ferramentas que eles usam. 


O gerenciamento de riscos é o processo de identificação, rastreamento e gerenciamento de riscos potenciais que podem afetar a saúde geral e a reputação de um negócio.


*******

Tabelas de conteúdo 

 1. [Identificação de riscos](#identificação)
 2. [Análise Qualitativa de Riscos](#analise)
 3. [Planejando Respostas aos Riscos](#planejamento)
 4. [Implementando respostas de risco](#implementação)
 5. [Monitoramento de Riscos](#monitoramento)

*******


<div id='whatismarkdown'/>  

## Identificação de riscos


A identificação de riscos se refere ao mapeamento dos riscos individuais e gerais do projeto, bem como suas características. O principal benefício desse mapeamento é trazer informações para que a equipe consigam responder de forma adequada a esses riscos, independentemente se eles forem ameaças ou oportunidades.


Os riscos seram identificados durante os ritos do Scrum, daily scrum, sprint planning, sprint review.  

- Daily Scrum: Durante as Daily scrum o time irá gerenciar os riscos ao verificar as o metas da sprint e os diversos itens que devem ser entregues.
- Sprint Planning: Durante a sprint planning seram criadas previsôes que podem ou não serem realizadas, assim o time estará avaliando os riscos que podem ocorrer.
- Sprint Review: Durante a Sprint review seram discutidos os riscos enquanto se debate o atual incremento e suas pespectivas, como isso podendo haver mudanças no product backlog.
- Sprint retrospectives: Podem ocorrer discussões que ajudaram a reduzir os diversos tipos de riscos.

### Riscos Negativos

| Causa	| Risco	| Descrição do risco	| Impacto |
| -------- | -------- | -------- | -------- |
| Inexperiência do time |	RN1	| Dificuldades com a tecnologia de desenvolvimento | Baixa produtividade, atraso nas entregas e sobrecarga de outros membros. |
| Falta de meios para a realização do trabalho | RN2 | Acessibilidade à internet | Atraso nas entregas ou sobrecarga de outros membros |
| Escopo mal definido | RN3 | Mudança no escopo | Replanejamento das atividades e retrabalho |
| Impossibilidade realizar determinada atividade | RN4 | Doença ou incapacidade física/mental de algum dos membros da equipe  | Mudança no Planejamento |
| Divergência de horários entre os membros | RN5 | Membro do time não puder participar das reuniões com os P.O's ou reuniões oficiais do time | Falta de entendimento do membro do time acerca da situação do projeto |
| Desistência de membros da equipe | RN6 | Membro do time desistir do projeto durante o desenvolvimento | Atraso nas entregas, sobrecarga de outros membros e impacto no escopo do projeto |
| Baixa qualidade do produto | RN7 | Pruduto apresenta defeitos de desenvolvimento, falta de testes,  | Não atender expectaviva do cliente  |


### Riscos Positivos
| Causa	| Risco	| Descrição	| Impacto |
| -------- | -------- | -------- | -------- |
| Motivação com o projeto | RP1 | Interesse da equipe em evoluir o projeto | Continuidade do projeto |
| Alta produtividade da equipe | RP2 | Entregas no tempo previsto | Segurança para o cliente |
| Realizar o projeto antes do prazo previsto | RP3 | Realizar o escopo antes do cronograma estabelecido | Qualidade do projeto pode aumentar |


<div id='analise'/>  

## Análise Qualitativa de Riscos

Risco é um evento que tem a chance de ocorrer. Essa chance varia entre pouco mais que 0% e pouco menos que 100%. A análise qualitativa dos riscos, visa priorizar esses riscos  considerando principalmente sua probabilidade de ocorrência e seus impactos nos objetivos do projeto.


### Probabilidade 

| Probabilidade (P)	 | Intervalo de ocorrência | Peso |
| -------- | -------- | -------- |
| Muito Baixa | 0 <= P <=20% | 1 |
| Baixa | 20% < P <= 40%| 2 |
| Moderada | 40% < P <= 60% | 3 |
| Alta | 60% < P <= 80% | 4 |
| Muita Alta | 80% < P <= 100% | 5 |

### Impacto
O tamanho do impacto varia de acordo com o risco no projeto.

| Impacto - (I) | Descrição | Peso |
| -------- | -------- | -------- |
| Muito Baixa | Quase  imperceptível ao projeto.| 1 |
| Baixa | Pouca influência no projeto. | 2 |
| Moderada | Notável ao projeto, mas com poucas consequências. | 3 |
| Alta | Dificulta a realização projeto. | 4 |
| Muita Alta | Impossibilita a realização do projeto. | 5 |


### Riscos Negativos

| Risco | Probabilidade | Impacto |	Prioridade |
| -------- | -------- | -------- | -------- |
| RN1 | Moderada | Alto | Alta |
| RN2 | Baixa | Alto | Baixa |
| RN3 | Moderada | Alto | Alta |
| RN4 | Moderada | Alto | Moderada |
| RN5 | Moderada | Moderada | Alta | 
| RN6 | Moderada | Alto | Alta | 
| RN7 | Baixa | Moderada | Alta | 

### Riscos Positivos

| Risco | Probabilidade | Impacto |	Prioridade |
| -------- | -------- | -------- | -------- |
| RP1 | Moderada | Moderado | Baixa |
| RP2 | Baixa | Alto | Moderada |
| RP3 | Baixa | Moderada | Baixa |




<div id='planejamento'/>  

## Planejando Respostas aos Riscos

|  Risco| Estratégia | Resposta |
| -------- | -------- | -------- |
| RN1 | Previnir | Indentificar o nível de conhecimento do time e fazer treinamentos   |
| RN2 | Transferir | Quando ocorrer será feita a tranferência da tarefa para outro membro do time |
| RN3 | Mitigar | Utilizar diversas técnicas de definição de espoco para diminuir a ocorrência do risco |
| RN4 | Transferir | Quando ocorrer será feita a tranferência do impacto do risco para outro membro do time |
| RN5 | Mitigar | Para diminuir o impacto podem ser feitas gravações de reuniões e formulários para validação assincrona |
| RN6 | Transferir | Quando ocorrer será feita a tranferência do impacto do risco para outro membro do time |
| RN7 | Mitigar | Utilizar ferramentas de testes automatizados para verificar a qualidade do código |
| RP1 | Melhoria | Incentiva os membros da equipe contiuamente |
| RP2 | Melhoria | Utilizar  a metodologia ágil, que através dessa, será feito o acompanhamento constante da produtividade da equipe |
| RP3 | Exploração  | Se caso o risco aparecer, ele será aproveitado |




<div id='implementação'/>  

## Implementando respostas de risco

A equipe estará monitorando os riscos apresentados durante os eventos SCRUM. Se caso algum deles ou outro inesperado ocorra, será implementada a resposta ao risco.


<div id='monitoramento'/>  

## Monitoramento de Riscos


| Risco | Monitoramento 
| -------- | -------- |
| RN1 | Através do pareamento e das reuniões diárias |
| RN2 | Através das reuniões diárias e canais de comunicação da equipe  |
| RN3 | Atráves das reuniões com os clientes e pelo roadmap |
| RN4 | Através das reuniões diárias e canais de comunicação da equipe |
| RN5 | Através dos canais de comunicação da equipe |
| RN6 | Através das reuniões diárias e canais de comunicação da equipe |
| RN7 | Atráves do sonarcloud e dos testes automatizados |
| RP1 | Através das reuniões diárias e canais de comunicação da equipe |
| RP2 | Através da metodologia ágil, terá acompanhamento constante da produtividade da equipe |
| RP3 | Através do cronograma do projeto |

## Burndown de risco

![image](https://i.imgur.com/SxvYt5V.png)

[Planilha](https://docs.google.com/spreadsheets/d/1LdK-BoqEZfWQMOEm2_Gff1ewhN1jzP0w3mvZZlTNouc/edit?usp=sharing)


# Referências

EUAX. Gerenciamento de Riscos em Projetos: aprenda a lidar com as incertezas na gestão de iniciativas. Disponível em: https://www.euax.com.br/2018/02/importancia-do-gerenciamento-de-riscos/. Acesso em: 13 mar. 2022.

REDHAT. Gerenciamento de riscos. Disponível em: https://www.redhat.com/pt-br/topics/management/what-is-risk-management#:~:text=As%20estrat%C3%A9gias%20de%20gerenciamento%20de,as%20vulnerabilidades%20e%20mitigar%20riscos.. Acesso em: 13 mar. 2022.


