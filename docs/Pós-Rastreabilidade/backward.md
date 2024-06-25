# Backward From

## Introdução

O "backward-from" (para trás, vindo de) é uma abordagem de pré-rastreabilidade que envolve a coleta de informações de rastreabilidade entre os requisitos e suas fontes.

No contexto da rastreabilidade entre requisitos, o "backward-from" consiste no mapeamento das origens dos requisitos. Isso significa identificar como foi definido aquele requisito, qual o contexto de sua origem e quais as suas características. Um requisito pode apresentar mais de uma fonte/origem, o que é importante para saber o nível de sua importância para a satisfação do cliente. Apresentar uma relação dos mesmos junto às suas respectivas fontes auxilia no desenvolvimento do produto, facilitando os desenvolvedores a identificar e entender mais rapidamente um requisito.


## Metodologia

A metodologia adotada foi o *Meta-modelo de Toranzo*[¹](https://requisitos-de-software.github.io/2024.1-Consumidor.gov/P%C3%B3s-Rastreabilidade/forward/#anchor_1), que propõe quatro níveis de classificação para as informações rastreadas, sendo eles:

- **Ambiental**: informações oriundas do ambiente em que está inserida a organização e como podem afetar o desenvolvimento do sistema
- **Organizacional**: informações relacionadas a organização (metas, padrões e objetivos) e seus respectivos impactos nos requisitos do sistema
- **Gerencial**: informações que permitem associar requisitos com tarefas, auxiliando na gestão do projeto
- **Desenvolvimento**: informações relacionadas aos artefatos gerados durante o desenvolvimento (diagramas, testes, etc.)

No contexto do projeto, as informações apresentadas neste artefato *Backward From*  se encaixam na classificação **Desenvolvimento**, visto que os requisitos (e suas respectivas origens) apresentam informações fundamentais para o desenvolvimento do projeto.

Dentro deste Meta-modelo, o suporte à rastreabilidade identifica diferentes tipos de elos[²](https://requisitos-de-software.github.io/2024.1-Consumidor.gov/P%C3%B3s-Rastreabilidade/forward/#anchor_2), sendo eles:

- **Satisfação**: indica a classe de origem que depende da satisfação da classe de destino
- **Recurso**: indica a classe de origem que depende de recurso(s) da classe de destino
- **Responsabilidade**: indica a participação de pessoas sobre os artefatos (responsabilidades e ações)
- **Representação**: representação ou modelagem dos requisitos em outras linguagens
- **Alocado**: classe de origem relacionada a classe de destino, representando subsistema
- **Agregação**: indica composição de elementos

## Matriz

Os requisitos funcionais e não funcionais previamente elicitados foram analisados e listados em uma tabela, formando uma matriz. Para isto, foi necessário verificar o estado da implementação dos requisitos, ou efetuar a criação dos protótipos caso não tivessem implementados na aplicação. Cada requisito foi analisado por determinado aluno, cobrindo assim todos os requisitos elicitados.

A Tabela 1 apresenta a legenda utilizada para identificar os diferentes tipos de artefatos.

| Legenda | Artefato                  |
| ------- | ------------------------- |
| QUE     | Requisito de Questionário |
| ST      | Requisito de Storytelling |
| ADD     | Requisito de Análise de Documentos|
| INT     | Requisito de Introspecção |
| RF      | Requisitos Funcionais     |
| RNF     | Requisitos não Funcionais |

<div>
<p> Tabela 1: Legenda (Autor: GALDINO, Henrique. 2024).</p>
</div>

A tabela 2 abaixo apresenta a matriz ***forward form***, relacionando os requisitos com seus respectivos artefatos e elos:

| REQUISITO | ARTEFATOS | IMPLEMENTAÇÃO | REPRESENTAÇÃO | ELO |
| :--: | :--: | :--: | :--: | :--: |
| RF1 | [ST12](https://requisitos-de-software.github.io/2024.1-Consumidor.gov/Elicitação/Storytelling/#requisitos-elicitados); [INT01](https://requisitos-de-software.github.io/2024.1-Consumidor.gov/Elicitação/introspec/#requisitos-funcionais-identificados) | IMPLEMENTADO |  | EB1 |
| RF2 | [INT02, INT03](https://requisitos-de-software.github.io/2024.1-Consumidor.gov/Elicita%C3%A7%C3%A3o/introspec/#metodologia) | IMPLEMENTADO |  | EB2 |  
| RF3 | [QUE02](https://requisitos-de-software.github.io/2024.1-Consumidor.gov/Elicitação/Questionário/#possiveis-requisitos);  [INT02, INT03, INT04](https://requisitos-de-software.github.io/2024.1-Consumidor.gov/Elicitação/introspec/#metodologia) | PARCIAL |  | EB3 |  
| RF4 | [QUE02, QUE05](https://requisitos-de-software.github.io/2024.1-Consumidor.gov/Elicitação/Questionário/#possiveis-requisitos);  [INT02, INT03, INT04](https://requisitos-de-software.github.io/2024.1-Consumidor.gov/Elicitação/introspec/#metodologia); [ST04, ST05](https://requisitos-de-software.github.io/2024.1-Consumidor.gov/Elicitação/Storytelling/); [ADD01](https://requisitos-de-software.github.io/2024.1-Consumidor.gov/Elicitação/analiseDoc/) | IMPLEMENTADO |  | EB4 | 
| RF5 | [INT05](https://requisitos-de-software.github.io/2024.1-Consumidor.gov/Elicitação/introspec/#metodologia);[ST01, ST03](https://requisitos-de-software.github.io/2024.1-Consumidor.gov/Elicitação/Storytelling/) | IMPLEMENTADO |  | EB5 |  
| RF6 | [INT06](https://requisitos-de-software.github.io/2024.1-Consumidor.gov/Elicitação/introspec/#metodologia);[ST01, ST03](https://requisitos-de-software.github.io/2024.1-Consumidor.gov/Elicitação/Storytelling/) | IMPLEMENTADO |  | EB6 |  
| RF7 | [INT07](https://requisitos-de-software.github.io/2024.1-Consumidor.gov/Elicitação/introspec/#metodologia);[ST01, ST03](https://requisitos-de-software.github.io/2024.1-Consumidor.gov/Elicitação/Storytelling/) | IMPLEMENTADO |  | EB7 |  
| RF8 | [INT08](https://requisitos-de-software.github.io/2024.1-Consumidor.gov/Elicitação/introspec/#metodologia);[ST01, ST03](https://requisitos-de-software.github.io/2024.1-Consumidor.gov/Elicitação/Storytelling/) | IMPLEMENTADO |  | EB8|  
| RF9 | [INT09](https://requisitos-de-software.github.io/2024.1-Consumidor.gov/Elicitação/introspec/#metodologia); [ST01, ST03](https://requisitos-de-software.github.io/2024.1-Consumidor.gov/Elicitação/Storytelling/); [ST07](https://requisitos-de-software.github.io/2024.1-Consumidor.gov/Elicitação/Storytelling/) | IMPLEMENTADO |  | EB9 |  
| RF10 | [QUE04](https://requisitos-de-software.github.io/2024.1-Consumidor.gov/Elicitação/Questionário/#possiveis-requisitos); [INT10](https://requisitos-de-software.github.io/2024.1-Consumidor.gov/Elicitação/introspec/#metodologia); [ADD01](https://requisitos-de-software.github.io/2024.1-Consumidor.gov/Elicitação/analiseDoc/) | IMPLEMENTADO |  | EB10 |  
| RF11 | [QUE06, QUE11](https://requisitos-de-software.github.io/2024.1-Consumidor.gov/Elicitação/Questionário/#possiveis-requisitos); [INT10, INT11](https://requisitos-de-software.github.io/2024.1-Consumidor.gov/Elicitação/introspec/#metodologia) | IMPLEMENTADO |  | EB11|  
| RF12 | [QUE11](https://requisitos-de-software.github.io/2024.1-Consumidor.gov/Elicitação/Questionário/#possiveis-requisitos); [INT10,INT11](https://requisitos-de-software.github.io/2024.1-Consumidor.gov/Elicitação/introspec/#metodologia) | IMPLEMENTADO |  | EB12 |  
| RF13 | [QUE04](https://requisitos-de-software.github.io/2024.1-Consumidor.gov/Elicitação/Questionário/#possiveis-requisitos); [INT12, INT13](https://requisitos-de-software.github.io/2024.1-Consumidor.gov/Elicitação/introspec/#metodologia); [ST05](https://requisitos-de-software.github.io/2024.1-Consumidor.gov/Elicitação/Storytelling/); [ADD01](https://requisitos-de-software.github.io/2024.1-Consumidor.gov/Elicitação/analiseDoc/) | IMPLEMENTADO |  | EB13 |  
| RF14 | [QUE04](https://requisitos-de-software.github.io/2024.1-Consumidor.gov/Elicitação/Questionário/#possiveis-requisitos); [INT12,INT13](https://requisitos-de-software.github.io/2024.1-Consumidor.gov/Elicitação/introspec/#metodologia); [ST05](https://requisitos-de-software.github.io/2024.1-Consumidor.gov/Elicitação/Storytelling/); [ADD01](https://requisitos-de-software.github.io/2024.1-Consumidor.gov/Elicitação/analiseDoc/) | IMPLEMENTADO |  | EB14 |  
| RF15 | [QUE11](https://requisitos-de-software.github.io/2024.1-Consumidor.gov/Elicitação/Questionário/#possiveis-requisitos); [INT15](https://requisitos-de-software.github.io/2024.1-Consumidor.gov/Elicitação/introspec/#metodologia) | IMPLEMENTADO |  | EB15 |  
| RF16 | [QUE11](https://requisitos-de-software.github.io/2024.1-Consumidor.gov/Elicitação/Questionário/#possiveis-requisitos); [INT15](https://requisitos-de-software.github.io/2024.1-Consumidor.gov/Elicitação/introspec/#metodologia) | INDEFINIDO* |  | EB16|  
| RF17 | [QUE11](https://requisitos-de-software.github.io/2024.1-Consumidor.gov/Elicitação/Questionário/#possiveis-requisitos); [INT15](https://requisitos-de-software.github.io/2024.1-Consumidor.gov/Elicitação/introspec/#metodologia) | INDEFINIDO* |  | EB17 |  
| RF18 | [QUE11](https://requisitos-de-software.github.io/2024.1-Consumidor.gov/Elicitação/Questionário/#possiveis-requisitos); [INT15](https://requisitos-de-software.github.io/2024.1-Consumidor.gov/Elicitação/introspec/#metodologia) | INDEFINIDO* |  | EB18 |  
| RF19 | [QUE11](https://requisitos-de-software.github.io/2024.1-Consumidor.gov/Elicitação/Questionário/#possiveis-requisitos); [INT15](https://requisitos-de-software.github.io/2024.1-Consumidor.gov/Elicitação/introspec/#metodologia); [ST04](https://requisitos-de-software.github.io/2024.1-Consumidor.gov/Elicitação/Storytelling/) | IMPLEMENTADO |  | EB19 |  
| RF20 | [QUE11](https://requisitos-de-software.github.io/2024.1-Consumidor.gov/Elicitação/Questionário/#possiveis-requisitos); [INT15](https://requisitos-de-software.github.io/2024.1-Consumidor.gov/Elicitação/introspec/#metodologia) | IMPLEMENTADO |  | EB20 |  
| RF21 | [QUE11](https://requisitos-de-software.github.io/2024.1-Consumidor.gov/Elicitação/Questionário/#possiveis-requisitos); [INT15](https://requisitos-de-software.github.io/2024.1-Consumidor.gov/Elicitação/introspec/#metodologia) | IMPLEMENTADO |  | EB21 |  
| RF22 |  [QUE11](https://requisitos-de-software.github.io/2024.1-Consumidor.gov/Elicitação/Questionário/#possiveis-requisitos); [INT15](https://requisitos-de-software.github.io/2024.1-Consumidor.gov/Elicitação/introspec/#metodologia) | IMPLEMENTADO |  | EB22 |  
| RF23 | [QUE11](https://requisitos-de-software.github.io/2024.1-Consumidor.gov/Elicitação/Questionário/#possiveis-requisitos); [INT15](https://requisitos-de-software.github.io/2024.1-Consumidor.gov/Elicitação/introspec/#metodologia) | IMPLEMENTADO |  | EB23 |  
| RF24 | [QUE05](https://requisitos-de-software.github.io/2024.1-Consumidor.gov/Elicitação/Questionário/#possiveis-requisitos); [INT15](https://requisitos-de-software.github.io/2024.1-Consumidor.gov/Elicitação/introspec/#metodologia) | IMPLEMENTADO |  | EB24 |  
| RF25 | [QUE05](https://requisitos-de-software.github.io/2024.1-Consumidor.gov/Elicitação/Questionário/#possiveis-requisitos); [INT15](https://requisitos-de-software.github.io/2024.1-Consumidor.gov/Elicitação/introspec/#metodologia) | IMPLEMENTADO |  | EB25 |  
| RNF1 |  [INT28, INT29](https://requisitos-de-software.github.io/2024.1-Consumidor.gov/Elicitação/introspec/#requisitos-nao-funcionais); [ADD04](https://requisitos-de-software.github.io/2024.1-Consumidor.gov/Elicitação/analiseDoc/) | IMPLEMENTADO |  | EB26 |  
| RNF2 | [QUE01](https://requisitos-de-software.github.io/2024.1-Consumidor.gov/Elicitação/Questionário/#possiveis-requisitos) ; [INT32, 33](https://requisitos-de-software.github.io/2024.1-Consumidor.gov/Elicitação/introspec/#requisitos-nao-funcionais); [ST11](https://requisitos-de-software.github.io/2024.1-Consumidor.gov/Elicitação/Storytelling/); [ADD05, ADD12](https://requisitos-de-software.github.io/2024.1-Consumidor.gov/Elicitação/analiseDoc/) | IMPLEMENTADO* |  | EB27 |  
| RNF3 | [QUE03](https://requisitos-de-software.github.io/2024.1-Consumidor.gov/Elicitação/Questionário/#possiveis-requisitos); [INT38](https://requisitos-de-software.github.io/2024.1-Consumidor.gov/Elicitação/introspec/#requisitos-nao-funcionais); [ST08](https://requisitos-de-software.github.io/2024.1-Consumidor.gov/Elicitação/Storytelling/); [ADD06, ADD07](https://requisitos-de-software.github.io/2024.1-Consumidor.gov/Elicitação/analiseDoc/) | NÃO IMPLEMENTADO |  | EB28 |  
| RNF4 | [QUE08, QUE09](https://requisitos-de-software.github.io/2024.1-Consumidor.gov/Elicitação/introspec/#metodologia); [INT41](https://requisitos-de-software.github.io/2024.1-Consumidor.gov/Elicitação/introspec/#requisitos-nao-funcionais); [ST09](https://requisitos-de-software.github.io/2024.1-Consumidor.gov/Elicitação/Storytelling/) | IMPLEMENTADO* |  | EB29 |  
| RNF5 | [INT42, INT43](https://requisitos-de-software.github.io/2024.1-Consumidor.gov/Elicitação/introspec/#requisitos-nao-funcionais); [ADD09, ADD11, ADD13](https://requisitos-de-software.github.io/2024.1-Consumidor.gov/Elicitação/analiseDoc/) | INDEFINIDO* |  | EB30 |  
| RNF6 | [INT13](https://requisitos-de-software.github.io/2024.1-Consumidor.gov/Elicitação/introspec/#metodologia); [ADD09, ADD11, ADD13](https://requisitos-de-software.github.io/2024.1-Consumidor.gov/Elicitação/analiseDoc/) | IMPLEMENTADO |  | EB31 |  
| RNF7 | [INT42](https://requisitos-de-software.github.io/2024.1-Consumidor.gov/Elicitação/introspec/#metodologia); [ST12](https://requisitos-de-software.github.io/2024.1-Consumidor.gov/Elicitação/Storytelling/); [ADD09, ADD11, ADD13](https://requisitos-de-software.github.io/2024.1-Consumidor.gov/Elicitação/analiseDoc/) | IMPLEMENTADO* |  | EB32 |  
| RNF8 | [QUE01](https://requisitos-de-software.github.io/2024.1-Consumidor.gov/Elicitação/Questionário/#possiveis-requisitos); [INT32](https://requisitos-de-software.github.io/2024.1-Consumidor.gov/Elicitação/introspec/#metodologia); [ST11](https://requisitos-de-software.github.io/2024.1-Consumidor.gov/Elicitação/Storytelling/); [ADD05, ADD12](https://requisitos-de-software.github.io/2024.1-Consumidor.gov/Elicitação/analiseDoc/) | IMPLEMENTADO* |  | EB33 |  
| RNF9 | [INT40](https://requisitos-de-software.github.io/2024.1-Consumidor.gov/Elicitação/introspec/#metodologia) | INDEFINIDO* |  | EB34 |  
| RNF10 | [INT34](https://requisitos-de-software.github.io/2024.1-Consumidor.gov/Elicitação/introspec/#metodologia)| IMPLEMENTADO* |  | EB35 |  
| RNF11 | [INT44](https://requisitos-de-software.github.io/2024.1-Consumidor.gov/Elicitação/introspec/#metodologia) | PARCIAL |  | EB36 |  
| RNF12 | [INT45](https://requisitos-de-software.github.io/2024.1-Consumidor.gov/Elicitação/introspec/#metodologia) | IMPLEMENTADO |  | EB37 |  
| RNF13 | [INT37](https://requisitos-de-software.github.io/2024.1-Consumidor.gov/Elicitação/introspec/#metodologia) | INDEFINIDO* |  | EB38 |  
| RNF14 | [INT36](https://requisitos-de-software.github.io/2024.1-Consumidor.gov/Elicitação/introspec/#metodologia) | IMPLEMENTADO |  | EB39 |  

<div>
<p> Tabela 2: Matriz Backward Form (Fonte: GALDINO, Henrique. 2024).</p>
</div>

## Elos

| ELO | REQUISITO | TIPO DE ELO | DESCRIÇÃO | RELACIONADO A (respectivamente) |
| :--: | :--: | :--: | :--: |:--: |
| EB1  | RF1 | Recurso | Para que os demais requisitos funcionais sejam aceitos, é necessário fazer login | [RF2 a RF25](https://requisitos-de-software.github.io/2024.1-Consumidor.gov/Elicitação/requisitos-elicitados/) |
| EB2  | RF2 | Recurso | As ações relacionadas a reclamação dependem da pesquisa de uma empresa, e esta pesquisa depende do usuário estar logado  | [RF3 a RF9](https://requisitos-de-software.github.io/2024.1-Consumidor.gov/Elicitação/requisitos-elicitados/) |
| EB3  | RF3 | Recurso | As visualização dos dados de uma empresa depende da pesquisa | [RF2](https://requisitos-de-software.github.io/2024.1-Consumidor.gov/Elicitação/requisitos-elicitados/) |
| EB4  | RF4 | Satisfaçãoo | A visualização dos gráficos/indicadores satisfaz, consequentemente, a visualização dos dados | [RF2 e RF3](https://requisitos-de-software.github.io/2024.1-Consumidor.gov/Elicitação/requisitos-elicitados/) |
| EB5  | RF5 | Recurso | As ações relacionadas a reclamação dependem da pesquisa de uma empresa | [RF2](https://requisitos-de-software.github.io/2024.1-Consumidor.gov/Elicitação/requisitos-elicitados/) |
| EB6  | RF6 | Recurso | As ações relacionadas a reclamação dependem da pesquisa de uma empresa | [RF2](https://requisitos-de-software.github.io/2024.1-Consumidor.gov/Elicitação/requisitos-elicitados/) |
| EB7  | RF7 | Recurso | As ações relacionadas a reclamação dependem da pesquisa de uma empresa | [RF2](https://requisitos-de-software.github.io/2024.1-Consumidor.gov/Elicitação/requisitos-elicitados/) |
| EB8  | RF8 | Recurso | As ações relacionadas a reclamação dependem da pesquisa de uma empresa | [RF2](https://requisitos-de-software.github.io/2024.1-Consumidor.gov/Elicitação/requisitos-elicitados/) |
| EB9  | RF9 | Recurso | As ações relacionadas a reclamação dependem da pesquisa de uma empresa | [RF2](https://requisitos-de-software.github.io/2024.1-Consumidor.gov/Elicitação/requisitos-elicitados/) |
| EB10 | RF10 | Recurso | A visualização das reclamações feitas dependem da realização de ao menos uma reclamação | [RF2, RF5 a RF9](https://requisitos-de-software.github.io/2024.1-Consumidor.gov/Elicitação/requisitos-elicitados/) |
| EB11 | RF11 | Satisfação | O acompanhamento do status satisfaz, consequentemente, a visualização de uma reclamação feita | [RF10](https://requisitos-de-software.github.io/2024.1-Consumidor.gov/Elicitação/requisitos-elicitados/) |
| EB12 | RF12 | Alocado | Relaciona-se com o subsistema de notificação do aplicativo | [RF10, RF11](https://requisitos-de-software.github.io/2024.1-Consumidor.gov/Elicitação/requisitos-elicitados/) |
| EB13 | RF13 | Recurso | Depende da pesquisa uma empresa | [RF2](https://requisitos-de-software.github.io/2024.1-Consumidor.gov/Elicitação/requisitos-elicitados/) |
| EB14 | RF14 | Satisfação | Visualizar detalhes de reclamações de outros usuários satisfaz, consequentemente, a visualização da mesmas. | [RF13](https://requisitos-de-software.github.io/2024.1-Consumidor.gov/Elicitação/requisitos-elicitados/) |
| EB15 | RF15 | Recurso | Avaliar reclamação depende de uma reclamação ter sido feita | [RF5 a RF9](https://requisitos-de-software.github.io/2024.1-Consumidor.gov/Elicitação/requisitos-elicitados/) |
| EB16 | RF16 | Recurso | Depende do login ser efetuado | [RF1](https://requisitos-de-software.github.io/2024.1-Consumidor.gov/Elicitação/requisitos-elicitados/)  |
| EB17 | RF17 | Recurso | Depende do cadastro da empresa | [RF16](https://requisitos-de-software.github.io/2024.1-Consumidor.gov/Elicitação/requisitos-elicitados/) |
| EB18 | RF18 | Recurso | Depende do cadastro da empresa | [RF16](https://requisitos-de-software.github.io/2024.1-Consumidor.gov/Elicitação/requisitos-elicitados/) |
| EB19 | RF19 | Satisfação | Interagir com as reclamações dos clientes satisfaz, consequentemente, cadastro da empresa | [RF16 a RF18](https://requisitos-de-software.github.io/2024.1-Consumidor.gov/Elicitação/requisitos-elicitados/) |
| EB20 | RF20 | Satisfação | Interagir com as reclamações dos clientes satisfaz, consequentemente, cadastro da empresa | [RF16 a RF18](https://requisitos-de-software.github.io/2024.1-Consumidor.gov/Elicitação/requisitos-elicitados/) |
| EB21 | RF21 | Satisfação | Interagir com as reclamações dos clientes satisfaz, consequentemente, cadastro da empresa | [RF16 a RF18](https://requisitos-de-software.github.io/2024.1-Consumidor.gov/Elicitação/requisitos-elicitados/) |
| EB22 | RF22 | Satisfação | Interagir com as reclamações dos clientes satisfaz, consequentemente, cadastro da empresa | [RF16 a RF18](https://requisitos-de-software.github.io/2024.1-Consumidor.gov/Elicitação/requisitos-elicitados/) |
| EB23 | RF23 | Satisfação | Interagir com as reclamações dos clientes satisfaz, consequentemente, cadastro da empresa | [RF16 a RF18](https://requisitos-de-software.github.io/2024.1-Consumidor.gov/Elicitação/requisitos-elicitados/) |
| EBF4 | RF24 | Recurso | Depende da pesquisa de uma empresa | [RF2](https://requisitos-de-software.github.io/2024.1-Consumidor.gov/Elicitação/requisitos-elicitados/) |
| EB25 | RF25 | Recurso | Depende da pesquisa de uma empresa | [RF2](https://requisitos-de-software.github.io/2024.1-Consumidor.gov/Elicitação/requisitos-elicitados/) |
| EB26 | RNF1 | Representação | Depende de representação em outra linguagem | - |
| EB27 | RNF2 | Representação | Depende de representação em outra linguagem | - |
| EB28 | RNF3 | Representação | Depende de representação em outra linguagem | - |
| EB29 | RNF4 | Representação | Depende de representação em outra linguagem | - |
| EB30 | RNF5 | Representação | Depende de representação em outra linguagem | - |
| EB31 | RNF6 | Representação | Depende de representação em outra linguagem | - |
| EB32 | RNF7 | Representação | Depende de representação em outra linguagem | - |
| EB33 | RNF8 | Representação | Depende de representação em outra linguagem | - |
| EB34 | RNF9 | Representação | Depende de representação em outra linguagem | - |
| EB35 | RNF10 | Representação | Depende de representação em outra linguagem | - |
| EB36 | RNF11 | Representação | Depende de representação em outra linguagem | - |
| EB37 | RNF12 | Representação | Depende de representação em outra linguagem | - |
| EB38 | RNF13 | Representação | Depende de representação em outra linguagem | - |
| EB39 | RNF14 | Representação | Depende de representação em outra linguagem | - |

## Histórico de Versões

| Versão | Data de execução | Data de revisão |  Descrição                          | Autor(es)                                           | Revisor(es)                                           |
| :----: | :--------------: | :-------------: | :---------------------------------: | :-------------------------------------------------: | :---------------------------------------------------: |
| 1.1    | 24/06/2024       | 24/06/2024      | Complementando matriz   | Guilherme Meister, Henrique Galdino, Igor Thiago, Júlio César, Matheus Ferreira, Rodrigo Gontijo   | Guilherme Meister, Henrique Galdino, Igor Thiago, Júlio César, Matheus Ferreira, Rodrigo Gontijo |
| 1.1    | 22/06/2024       | 22/06/2024      | Adicionando matriz e elos   | Guilherme Meister, Henrique Galdino, Igor Thiago, Júlio César, Matheus Ferreira, Rodrigo Gontijo   | Guilherme Meister, Henrique Galdino, Igor Thiago, Júlio César, Matheus Ferreira, Rodrigo Gontijo |
| 1.0    | 12/06/2024       | 12/06/2024      | Criação do artefato | [Guilherme Meister](https://github.com/gmeister18)   | [Henrique Galdino](https://github.com/hgaldino05)     |
