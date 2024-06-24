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
| RF1 | [ST12](https://requisitos-de-software.github.io/2024.1-Consumidor.gov/Elicitação/Storytelling/#requisitos-elicitados); [INT01](https://requisitos-de-software.github.io/2024.1-Consumidor.gov/Elicitação/introspec/#requisitos-funcionais-identificados) | IMPLEMENTADO |  |  |
| RF2 | [INT02, INT03](https://requisitos-de-software.github.io/2024.1-Consumidor.gov/Elicita%C3%A7%C3%A3o/introspec/#metodologia) | IMPLEMENTADO |  |  |  
| RF3 | [QUE02](https://requisitos-de-software.github.io/2024.1-Consumidor.gov/Elicitação/Questionário/#possiveis-requisitos);  [INT02, INT03, INT04](https://requisitos-de-software.github.io/2024.1-Consumidor.gov/Elicitação/introspec/#metodologia) | PARCIAL |  |  |  |
| RF4 | [QUE02, QUE05](https://requisitos-de-software.github.io/2024.1-Consumidor.gov/Elicitação/Questionário/#possiveis-requisitos);  [INT02, INT03, INT04](https://requisitos-de-software.github.io/2024.1-Consumidor.gov/Elicitação/introspec/#metodologia); [ST04, ST05](https://requisitos-de-software.github.io/2024.1-Consumidor.gov/Elicitação/Storytelling/); [ADD01](https://requisitos-de-software.github.io/2024.1-Consumidor.gov/Elicitação/analiseDoc/) | IMPLEMENTADO |  |  |  
| RF5 | [INT05](https://requisitos-de-software.github.io/2024.1-Consumidor.gov/Elicitação/introspec/#metodologia);[ST01, ST03](https://requisitos-de-software.github.io/2024.1-Consumidor.gov/Elicitação/Storytelling/) | IMPLEMENTADO |  |  |  
| RF6 | [INT06](https://requisitos-de-software.github.io/2024.1-Consumidor.gov/Elicitação/introspec/#metodologia);[ST01, ST03](https://requisitos-de-software.github.io/2024.1-Consumidor.gov/Elicitação/Storytelling/) | IMPLEMENTADO |  |  |  
| RF7 | [INT07](https://requisitos-de-software.github.io/2024.1-Consumidor.gov/Elicitação/introspec/#metodologia);[ST01, ST03](https://requisitos-de-software.github.io/2024.1-Consumidor.gov/Elicitação/Storytelling/) | IMPLEMENTADO |  |  |  
| RF8 | [INT08](https://requisitos-de-software.github.io/2024.1-Consumidor.gov/Elicitação/introspec/#metodologia);[ST01, ST03](https://requisitos-de-software.github.io/2024.1-Consumidor.gov/Elicitação/Storytelling/) | IMPLEMENTADO |  |  |  
| RF9 | [INT09](https://requisitos-de-software.github.io/2024.1-Consumidor.gov/Elicitação/introspec/#metodologia); [ST01, ST03](https://requisitos-de-software.github.io/2024.1-Consumidor.gov/Elicitação/Storytelling/); [ST07](https://requisitos-de-software.github.io/2024.1-Consumidor.gov/Elicitação/Storytelling/) | IMPLEMENTADO |  |  |  
| RF10 | [QUE04](https://requisitos-de-software.github.io/2024.1-Consumidor.gov/Elicitação/Questionário/#possiveis-requisitos); [INT10](https://requisitos-de-software.github.io/2024.1-Consumidor.gov/Elicitação/introspec/#metodologia); [ADD01](https://requisitos-de-software.github.io/2024.1-Consumidor.gov/Elicitação/analiseDoc/) | IMPLEMENTADO |  |  |  
| RF11 | [QUE06, QUE11](https://requisitos-de-software.github.io/2024.1-Consumidor.gov/Elicitação/Questionário/#possiveis-requisitos); [INT10, INT11](https://requisitos-de-software.github.io/2024.1-Consumidor.gov/Elicitação/introspec/#metodologia) | IMPLEMENTADO |  |  |  
| RF12 | [QUE11](https://requisitos-de-software.github.io/2024.1-Consumidor.gov/Elicitação/Questionário/#possiveis-requisitos); [INT10,INT11](https://requisitos-de-software.github.io/2024.1-Consumidor.gov/Elicitação/introspec/#metodologia) | IMPLEMENTADO |  |  |  
| RF13 | [QUE04](https://requisitos-de-software.github.io/2024.1-Consumidor.gov/Elicitação/Questionário/#possiveis-requisitos); [INT12, INT13](https://requisitos-de-software.github.io/2024.1-Consumidor.gov/Elicitação/introspec/#metodologia); [ST05](https://requisitos-de-software.github.io/2024.1-Consumidor.gov/Elicitação/Storytelling/); [ADD01](https://requisitos-de-software.github.io/2024.1-Consumidor.gov/Elicitação/analiseDoc/) | IMPLEMENTADO |  |  |  
| RF14 | [QUE04](https://requisitos-de-software.github.io/2024.1-Consumidor.gov/Elicitação/Questionário/#possiveis-requisitos); [INT12,INT13](https://requisitos-de-software.github.io/2024.1-Consumidor.gov/Elicitação/introspec/#metodologia); [ST05](https://requisitos-de-software.github.io/2024.1-Consumidor.gov/Elicitação/Storytelling/); [ADD01](https://requisitos-de-software.github.io/2024.1-Consumidor.gov/Elicitação/analiseDoc/) | IMPLEMENTADO |  |  |  
| RF15 | [QUE11](https://requisitos-de-software.github.io/2024.1-Consumidor.gov/Elicitação/Questionário/#possiveis-requisitos); [INT15](https://requisitos-de-software.github.io/2024.1-Consumidor.gov/Elicitação/introspec/#metodologia) | IMPLEMENTADO |  |  |  
| RF16 | [QUE11](https://requisitos-de-software.github.io/2024.1-Consumidor.gov/Elicitação/Questionário/#possiveis-requisitos); [INT15](https://requisitos-de-software.github.io/2024.1-Consumidor.gov/Elicitação/introspec/#metodologia) | INDEFINIDO* |  |  |  
| RF17 | [QUE11](https://requisitos-de-software.github.io/2024.1-Consumidor.gov/Elicitação/Questionário/#possiveis-requisitos); [INT15](https://requisitos-de-software.github.io/2024.1-Consumidor.gov/Elicitação/introspec/#metodologia) | INDEFINIDO* |  |  |  
| RF18 | [QUE11](https://requisitos-de-software.github.io/2024.1-Consumidor.gov/Elicitação/Questionário/#possiveis-requisitos); [INT15](https://requisitos-de-software.github.io/2024.1-Consumidor.gov/Elicitação/introspec/#metodologia) | INDEFINIDO* |  |  |  
| RF19 | [QUE11](https://requisitos-de-software.github.io/2024.1-Consumidor.gov/Elicitação/Questionário/#possiveis-requisitos); [INT15](https://requisitos-de-software.github.io/2024.1-Consumidor.gov/Elicitação/introspec/#metodologia); [ST04](https://requisitos-de-software.github.io/2024.1-Consumidor.gov/Elicitação/Storytelling/) | IMPLEMENTADO |  |  |  
| RF20 | [QUE11](https://requisitos-de-software.github.io/2024.1-Consumidor.gov/Elicitação/Questionário/#possiveis-requisitos); [INT15](https://requisitos-de-software.github.io/2024.1-Consumidor.gov/Elicitação/introspec/#metodologia) | IMPLEMENTADO |  |  |  
| RF21 | [QUE11](https://requisitos-de-software.github.io/2024.1-Consumidor.gov/Elicitação/Questionário/#possiveis-requisitos); [INT15](https://requisitos-de-software.github.io/2024.1-Consumidor.gov/Elicitação/introspec/#metodologia) | IMPLEMENTADO |  |  |  
| RF22 |  [QUE11](https://requisitos-de-software.github.io/2024.1-Consumidor.gov/Elicitação/Questionário/#possiveis-requisitos); [INT15](https://requisitos-de-software.github.io/2024.1-Consumidor.gov/Elicitação/introspec/#metodologia) | IMPLEMENTADO |  |  |  
| RF23 | [QUE11](https://requisitos-de-software.github.io/2024.1-Consumidor.gov/Elicitação/Questionário/#possiveis-requisitos); [INT15](https://requisitos-de-software.github.io/2024.1-Consumidor.gov/Elicitação/introspec/#metodologia) | IMPLEMENTADO |  |  |  
| RF24 | [QUE05](https://requisitos-de-software.github.io/2024.1-Consumidor.gov/Elicitação/Questionário/#possiveis-requisitos); [INT15](https://requisitos-de-software.github.io/2024.1-Consumidor.gov/Elicitação/introspec/#metodologia) | IMPLEMENTADO |  |  |  
| RF25 | [QUE05](https://requisitos-de-software.github.io/2024.1-Consumidor.gov/Elicitação/Questionário/#possiveis-requisitos); [INT15](https://requisitos-de-software.github.io/2024.1-Consumidor.gov/Elicitação/introspec/#metodologia) | IMPLEMENTADO |  |  |  
| RNF1 |  [INT28, INT29](https://requisitos-de-software.github.io/2024.1-Consumidor.gov/Elicitação/introspec/#requisitos-nao-funcionais); [ADD04](https://requisitos-de-software.github.io/2024.1-Consumidor.gov/Elicitação/analiseDoc/) | IMPLEMENTADO |  |  |  
| RNF2 | [QUE01](https://requisitos-de-software.github.io/2024.1-Consumidor.gov/Elicitação/Questionário/#possiveis-requisitos) ; [INT32, 33](https://requisitos-de-software.github.io/2024.1-Consumidor.gov/Elicitação/introspec/#requisitos-nao-funcionais); [ST11](https://requisitos-de-software.github.io/2024.1-Consumidor.gov/Elicitação/Storytelling/); [ADD05, ADD12](https://requisitos-de-software.github.io/2024.1-Consumidor.gov/Elicitação/analiseDoc/) | IMPLEMENTADO* |  |  |  
| RNF3 | [QUE03](https://requisitos-de-software.github.io/2024.1-Consumidor.gov/Elicitação/Questionário/#possiveis-requisitos); [INT38](https://requisitos-de-software.github.io/2024.1-Consumidor.gov/Elicitação/introspec/#requisitos-nao-funcionais); [ST08](https://requisitos-de-software.github.io/2024.1-Consumidor.gov/Elicitação/Storytelling/); [ADD06, ADD07](https://requisitos-de-software.github.io/2024.1-Consumidor.gov/Elicitação/analiseDoc/) | NÃO IMPLEMENTADO |  |  |  
| RNF4 | [QUE08, QUE09](https://requisitos-de-software.github.io/2024.1-Consumidor.gov/Elicitação/introspec/#metodologia); [INT41](https://requisitos-de-software.github.io/2024.1-Consumidor.gov/Elicitação/introspec/#requisitos-nao-funcionais); [ST09](https://requisitos-de-software.github.io/2024.1-Consumidor.gov/Elicitação/Storytelling/) | IMPLEMENTADO* |  |  |  
| RNF5 | [INT42, INT43](https://requisitos-de-software.github.io/2024.1-Consumidor.gov/Elicitação/introspec/#requisitos-nao-funcionais); [ADD09, ADD11, ADD13](https://requisitos-de-software.github.io/2024.1-Consumidor.gov/Elicitação/analiseDoc/) | INDEFINIDO* |  |  |  
| RNF6 | [INT13](https://requisitos-de-software.github.io/2024.1-Consumidor.gov/Elicitação/introspec/#metodologia); [ADD09, ADD11, ADD13](https://requisitos-de-software.github.io/2024.1-Consumidor.gov/Elicitação/analiseDoc/) | IMPLEMENTADO |  |  |  
| RNF7 | [INT42](https://requisitos-de-software.github.io/2024.1-Consumidor.gov/Elicitação/introspec/#metodologia); [ST12](https://requisitos-de-software.github.io/2024.1-Consumidor.gov/Elicitação/Storytelling/); [ADD09, ADD11, ADD13](https://requisitos-de-software.github.io/2024.1-Consumidor.gov/Elicitação/analiseDoc/) | IMPLEMENTADO* |  |  |  
| RNF8 | [QUE01](https://requisitos-de-software.github.io/2024.1-Consumidor.gov/Elicitação/Questionário/#possiveis-requisitos); [INT32](https://requisitos-de-software.github.io/2024.1-Consumidor.gov/Elicitação/introspec/#metodologia); [ST11](https://requisitos-de-software.github.io/2024.1-Consumidor.gov/Elicitação/Storytelling/); [ADD05, ADD12](https://requisitos-de-software.github.io/2024.1-Consumidor.gov/Elicitação/analiseDoc/) | IMPLEMENTADO* |  |  |  
| RNF9 | [INT40](https://requisitos-de-software.github.io/2024.1-Consumidor.gov/Elicitação/introspec/#metodologia) | INDEFINIDO* |  |  |  
| RNF10 | [INT34](https://requisitos-de-software.github.io/2024.1-Consumidor.gov/Elicitação/introspec/#metodologia)| IMPLEMENTADO* |  |  |  
| RNF11 | [INT44](https://requisitos-de-software.github.io/2024.1-Consumidor.gov/Elicitação/introspec/#metodologia) | PARCIAL |  |  |  
| RNF12 | [INT45](https://requisitos-de-software.github.io/2024.1-Consumidor.gov/Elicitação/introspec/#metodologia) | IMPLEMENTADO |  |  |  
| RNF13 | [INT37](https://requisitos-de-software.github.io/2024.1-Consumidor.gov/Elicitação/introspec/#metodologia) | INDEFINIDO* |  |  |  
| RNF14 | [INT36](https://requisitos-de-software.github.io/2024.1-Consumidor.gov/Elicitação/introspec/#metodologia) | IMPLEMENTADO |  |  |  

<div>
<p> Tabela 2: Matriz Backward Form (Fonte: GALDINO, Henrique. 2024).</p>
</div>

## Elos

## Elos

| ID | REQUISITO | SATISFAÇÃO | RECURSO | REPRESENTAÇÃO | ALOCADO | AGREGAÇÃO |
| :--: | :--: | :--: | :--: | :--: | :--: | :--: |
| EB1  | RF1 | US1 | UC1 A UC8 |  | NFR01 | - |
| EB2  | RF2 | US2 | UC1, CEN1, LEX1 |  | NF01 | RF3 A RF9| 
| EB3  | RF3 | US3 |  |  | NFR01 | RF4 |
| EB4  | RF4 |  |  |  |  |  |
| EB5  | RF5 |  |  |  |  |  |
| EB6  | RF6 |  |  |  |  |  |
| EB7  | RF7 |  |  |  |  |  |
| EB8  | RF8  | |  |  |  |  |
| EB9  | RF9  | |  |  |  |  |
| EB10 | RF10 | |  |  |  |  |
| EB11 | RF11 | |  |  |  |  |
| EB12 | RF12 | |  |  |  |  |
| EB13 | RF13 | |  |  |  |  |
| EB14 | RF14 | |  |  |  |  |
| EB15 | RF15 | |  |  |  |  |
| EB16 | RF16 | |  |  |  |  |
| EB17 | RF17 | |  |  |  |  |
| EB18 | RF18 | |  |  |  |  |
| EB19 | RF19 | |  |  |  |  |
| EB20 | RF20 | |  |  |  |  |
| EB21 | RF21 | |  |  |  |  |
| EB22 | RF22 | |  |  |  |  |
| EB23 | RF23 | |  |  |  |  |
| EBF24 | RF24 | |  |  |  |  |
| EB25 | RF25 | |  |  |  |  |
| EB26 | RNF1 | |  |  |  |  |
| EB27 | RNF2 | |  |  |  |  |
| EB28 | RNF3 | |  |  |  |  |
| EB29 | RNF4 | |  |  |  |  |
| EB30 | RNF5 | |  |  |  |  |
| EB31 | RNF6 | |  |  |  |  |
| EB32 | RNF7 | |  |  |  |  |
| EB33 | RNF8 | |  |  |  |  |
| EB34 | RNF9 | |  |  |  |  |
| EB35 | RNF10 | |  |  |  |  |
| EB36 | RNF11 | |  |  |  |  |
| EB37 | RNF12 | |  |  |  |  |
| EB38 | RNF13 | |  |  |  |  |
| EB39 | RNF14 | |  |  |  |  |

## Histórico de Versões

| Versão | Data de execução | Data de revisão |  Descrição                          | Autor(es)                                           | Revisor(es)                                           |
| :----: | :--------------: | :-------------: | :---------------------------------: | :-------------------------------------------------: | :---------------------------------------------------: |
| 1.1    | 24/06/2024       | 24/06/2024      | Complementando matriz   | Guilherme Meister, Henrique Galdino, Igor Thiago, Júlio César, Matheus Ferreira, Rodrigo Gontijo   | Guilherme Meister, Henrique Galdino, Igor Thiago, Júlio César, Matheus Ferreira, Rodrigo Gontijo |
| 1.1    | 22/06/2024       | 22/06/2024      | Adicionando matriz e elos   | Guilherme Meister, Henrique Galdino, Igor Thiago, Júlio César, Matheus Ferreira, Rodrigo Gontijo   | Guilherme Meister, Henrique Galdino, Igor Thiago, Júlio César, Matheus Ferreira, Rodrigo Gontijo |
| 1.0    | 12/06/2024       | 12/06/2024      | Criação do artefato | [Guilherme Meister](https://github.com/gmeister18)   | [Henrique Galdino](https://github.com/hgaldino05)     |
