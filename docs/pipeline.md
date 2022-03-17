## Histórico de revisão

| Data       | Versão | Alteração                                                    | Autor                    |
| ---------- | ------ | ------------------------------------------------------------ | ------------------------ |
16/03/2022 | 1.0 | Criado documento de pipeline| Lucas Lopes |


<h1 style="text-align: center">Pipelines</h1>

<p style="text-align:justify">&emsp;&emsp; O objetivo de uma pipeline é automatizar o processo de entrega de software em produção de forma rápida, ao mesmo tempo garantindo sua estabilidade, qualidade e resiliência </p>

## Ambiente de desenvolvimento

No ambiente de desenvolvimento, há três pipelines diferentes.  <br>
A primeira, executa a aplicação pelo sonar para estimar as métricas de qualidade.  <br>
Já a segunda, depois de ter passado pela primeira pipeline, faz o deploy automaticamente na heroku atráves da `branch devel`. <br>
A terceira, ao criar uma tag, é gerado uma nova release e é enviada as métricas para o [repositório de documentação](https://github.com/fga-eps-mds/2021-2-Oraculo-Doc)

## Ambiente de documentação

No ambiente de documentação, só existe uma pipeline. Ao fazer um push, é enviado ao github pages a nova versão da página.

## Fluxo de desenvolvimento

Há 2 ramos (branchs) fixos:

main: ambiente de produção; <br>
devel: ambiente de homologação.

As mudanças da devel que são fundidas (Pull Request merge) na `main` não geram release ou geram uma `release (major ou minor)`.

As mudanças de um ramo do tipo hotfix que são fundidas (Pull Request Merge) na `main` geram uma `release patch.`

O desenvolvimento de novas funcionalidades deve derivar do ramo `devel`, em seguidas fundidas na `devel` e depois integrar todas as funcionalidades na `devel`. Por fim, é fundida  na `main`
