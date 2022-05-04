| Versão | Data       | Modificação                    | Motivo | Autor(es) |
| ------ | ---------- | ------------------------------ | :----: | ----- |
| 1.0    | 13/03/2022 | Criação do documento  | - | João Victor, Lucas Lopes, Caio César |
| 2.0    | 04/04/2022 | Criação do documento  | Atualização métrica de Nível de Satisfação do Usuário  | João Victor, Lucas Lopes, Caio César |




# Plano de Qualidade


O plano de qualidade é desenvolvido para descrever práticas, recursos ou parâmetros necessários para garantir a qualidade de um sistema. 

## Modelo

![Untitled Diagram drawio](https://user-images.githubusercontent.com/38164895/158085194-b797d13c-f388-40f6-8bfd-455b8c0a7f7e.png)

## Objetivos

### Objetivo 01 - Boa usabilidade

Analisar | Propósito | Em relação a | Ponto de vista | Produto |
:--------- | :------: | -------:| -------: | -------: |
Usabilidade do software | Melhoria | Facilidade de uso | Usuário final | Oráculo |


Foco da qualidade | Fatores de Variação | Hipóteses de Baseline  | Variações nas hipóteses |
:--------- | :------: | -------:| -------: |
1 - Teste de aceitação por parte do usuáirio <br> 2 - Satisfação do usuário <br> 3 - Padronização na execução de tarefas <br> | 1 - O caminho a ser percorrido até chegar  na  funcionalidade  afeta o usuário <br> 2 - A satisfação do usuário melhora conforme ele aprende a usar <br> 3 - O conhecimento do usuário em outras ferramentas similares <br> | 1 - Formulário respondido de forma assincrona pelo usuário <br> 2 - Espera-se que funcionalidades semelhates tenham o fluxo parecido <br> | 1 - A complexidade de uma funcionalidade pode fazer com que ela seja quebrada em várias etapas <br> 2 - O interesse do usuário pela aplicação <br>  |

### Objetivo 02 - Código  Fonte Manutenível

Analisar | Propósito | Em relação a | Ponto de vista | Produto |
:--------- | :------: | -------:| -------: | -------: |
código da aplicação| Entender e melhorar | manutenção  | Desenvolvedor | Oráculo |


Foco da qualidade | Fatores de Variação | Hipóteses de Baseline  | Variações nas hipóteses |
:--------- | :------: | -------:| -------: |
1 - Código reaproveitado <br> 2 - Aplicar padrões de escrita <br> 3 - Quantidade do software que foi testada <br> | 1 - Experiência do desenvolvedor com as tecnologias <br> 2 - Qualidade dos testes <br> | 1 - Máximo possível de código reaproveitado <br> 2 - Padrão de escrita e de código no projeto <br> 3 - Baixa complexidade no código <br> 4 - Alta cobertura de testes <br> 5 - Alta coesão <br> 6 - Baixo Acomplamento <br> | 1 - Códigos muito semelhantes mas com propósitos diferentes podem ser considerados duplicados pelo sonar <br> 2 - Podem ocorrer exceções quanto a folha de estilo  <br> |


### Objetivo 03 - Capacitação da equipe

Analisar | Propósito | Em relação a | Ponto de vista | Produto |
:--------- | :------: | -------:| -------: | -------: |
Capacitação da equipe | Entender e melhorar | Aquisição de conhecimento | Aluno | Oráculo |

Foco da qualidade | Fatores de Variação | Hipóteses de Baseline  | Variações nas hipóteses |
:--------- | :------: | -------:| -------: |
1 - Conhecimento da equipe <br> 2 - Disseminação do conhecimento na equipe <br> | 1 - Desenvolver habilidades por meio de outros projetos <br> | 1 - Melhora de conhecimentos a cada sprint <br> 2 - Rodízio nas duplas de pareamento <br> | 1 - Ao ter mais contato com determinada tecnologia, o estudante pode perceber que não  conhece tão bem e diminuir a classificação no quadro de conhecimento <br> 2 - Histórias pequenas podem ser entregues antes do previsto <br> 3 - Histórias podem ser mal estimadas e levar mais tempo que o previsto <br> |

### Objetivo 4: Produtividade da Equipe

Analisar | Propósito | Em relação a | Ponto de vista | Produto |
:--------- | :------: | -------:| -------: | -------: |
Capacitação da equipe | Entender e melhorar | Aquisição de conhecimento | Aluno | Oráculo |

Foco da qualidade | Fatores de Variação | Hipóteses de Baseline  | Variações nas hipóteses |
:--------- | :------: | -------:| -------: |
1 - Burdown <br> 2 - Velocity <br>  3 - Capacidade de cada aluno <br> | 1 - Desenvolvedor em determina sprint pode ter algum problema que possa produzir menos <br> | 1 - A produtividade do desenvolvedor deve se manter constante ou aumentar a cada sprint.<br> 2 Espera-se que o velocity da equipe seja maior que 20 pontos. <br> | 1 - Dificuldades por baixo conhecimento da tecnologia <br> 2 - Histórias pequenas podem ser entregues antes do previsto  <br> 3 - Histórias podem ser mal estimadas e levar mais tempo que o previsto <br> |


## Métricas de medição




<p> <b> Nível de Satisfação do Usuário <b> </p>

| Objetivo da Medição | Identificar o quão confortável o usuário se sente para usar  no sistema.
:--------- | :------: |
| Método | 	Em um formulário disponibilizado pelos clientes, devem responder o quão a vontade ele se sente ao usar no sistema. |
|Escala de medição | Numérica |
| Forma de coleta | o sistema, pedir que usem o aplicativo, testando as novas funcionalidades implementadas e por fim, pedir para eles avaliarem em uma escala de 0 a 10 e questões qualitativas o quão intuitivo e prático foi mecher na aplicação. |
| Análise | 0 a 2: Ruim. Deve-se reavaliar  a lógica de interação <br> 3 a 5: Razoável. Porém,  promover melhoras na lógica de interação. <br> 6 a 8 Satisfatório <br> 0 a 10 Excelente  <br>

<p> <b> Duplicidade de Código <b> </p>

| Objetivo da Medição | Verificar se existe código duplicado que pode ser reaproveitado 
:--------- | :------: |
| Método | 	Quantidade de códigos/funções idênticas ou semelhantes presentes no código. |
| Escala de medição | Racional |
| Forma de coleta | Através do sonar |
| Análise | Se apresentar duplicações, realizar medidas devem ser tomadas para reaproveitar melhor o código da aplicação. |


<p> <b> Manutenabilidade <b> </p>


| Objetivo da Medição | Monitorar e melhorar a manutenabilidade do código que está sendo gerado |
:--------- | :------: |
| Método | 	- |
| Escala de medição | Racional |
| Forma de coleta | Através do sonar |
| Análise | Se apresentar resultado abaixo de B, reavaliar o código |

<p> <b> Complexidade Ciclomática  <b> </p>

| Objetivo da Medição | Verificar a quantidade de caminhos de execução independentes. |
:--------- | :------: |
| Método | 	V(G) = e - n + p Onde V(G) é a complexidade ciclomática, n = vértice, e = aresta, p = componentes conectados. A média é feita, M(V(G)), dando a complexidade ciclomática média. |
| Escala de medição | Racional |
| Forma de coleta | Através do sonar |
| Análise | Caso a ferramenta acuse algum problema de complexidade, o código deverá ser corrigido .|

<p> <b> Cobertura de testes  <b> </p>

| Objetivo da Medição | Verificar a porcentagem do código que está sendo testado, afim de garantir a manutenabilidade e a qualidade |
:--------- | :------: |
| Método | 	Cobertura = Linhas testadas / Linhas totais  |
| Escala de medição | Racional |
| Forma de coleta | Através do sonar |
| Análise | 0 a 89%: Preocupante. Deve-se abrir histórias técnicas para a testar a aplicação <br> 90% ou mais: Satisfatório |

<p> <b> Quadro de Conhecimentos <b> </p>

| Objetivo da Medição | Acompanhar a evolução da equipe em relação ao conhecimento adquirido. |
:--------- | :------: |
| Método | 	Não se aplica nessa métrica  |
| Escala de medição | Intervalar |
| Forma de coleta |  Antes de começar a sprint review, todos os membros devem atualizar o quadro de conhecimentos com os conhecimentos adquiridos durante aquela sprint. |
| Análise | 0 a 2: Baixíssimo ou nenhum conhecimento <br> 3 a 5:  pouco de conhecimento <br>  6 a 7: Conhecimento razoável <br> 8 a 10: Conhecimento satisfatório <br> |

<p> <b> Pareamentos <b> </p>

| Objetivo da Medição | Verificar se os membros estão interagindo com o intuido de difundir os  conhecimentos. |
:--------- | :------: |
| Método | 	Não se aplica nessa métrica  |
| Escala de medição | Racional |
| Forma de coleta |   Antes de começar a sprint review, um membro de cada par deve atualizar o quadro de número de pareamentos indicando com quais pessoas ele pareou durante a sprint.  |
| Análise | Quanto mais homogêneo estiver o quadro de número de pareamentos, entende-se que o conhecimento está sendo difundido entre toda a equipe. Caso, algum valor seja muito discrepante em relação aos outros deve-se averiguar o motivo e tomar providências afim de disseminar o connhecimento |

<p> <b> Burdown <b> </p>

| Objetivo da Medição | Acompanhar a entrega contínua de atividades dentro da sprint  |
:--------- | :------: |
| Método | 	Não se aplica nessa métrica  |
| Escala de medição | Não se aplica nessa métrica |
| Forma de coleta |   Após o fechamento da sprint, coletar a imagem do gráfico gerado por meio do github  |
| Análise | Se as issues são finalizadas  durante a sprint entende-se que há constância na produtividade da equipe. Se as issues são entregues somente no final, ou não são entregues, a forma de planejar a sprint deve ser repensada e as histórias analisadas, uma sugestão é:  a equipe  deve transformar a história em um épico e quebrá-la em histórias menores. |



<p> <b> Velocity <b> </p>

| Objetivo da Medição | Acompanhar a capacidade de produção da equipe para auxiliar no planejamento das próximas sprints  |
:--------- | :------: |
| Método | 	Média de pontos entregues por sprints  |
| Escala de medição | Racional |
| Forma de coleta |   Após o fechamento da sprint, coletar a imagem do gráfico gerado pelo zenhub  |
| Análise | Com base nos resultado do velocity deve-se estimar a próxima sprint em torno da mesma quantidade de pontos. |











