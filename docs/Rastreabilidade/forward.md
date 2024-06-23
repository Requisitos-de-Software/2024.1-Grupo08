# Forward From

## Introdução

<!-- A rastreabilidade é a capacidade de descrever e acompanhar a vida de um requisito, desde sua origem, passando por seu desenvolvimento e especificação, até sua posterior implantação e uso. Ela é essencial para garantir que todos os requisitos tenham sido atendidos e para gerenciar mudanças nos requisitos ao longo do ciclo de vida do projeto.

A rastreabilidade é crucial para a gerência por requisitos e para a detecção de conflitos, além de ser essencial para o gerenciamento do desenvolvimento e controle de riscos. Ela ajuda a detectar requisitos não alocados a componentes e a gerenciar as mudanças e a evolução do sistema.

A rastreabilidade pode ser implementada por meio de elos ou ligações entre requisitos inter-relacionados, suas fontes, e os componentes que os implementam. Técnicas comuns incluem o uso de referências cruzadas e matrizes de rastreabilidade, frequentemente suportadas por ferramentas de software. -->

O "forward-from" (para frente, a partir de) é uma aborgadem de pós-rastreabilidade que envolve a coleta de informações de rastreabilidade entre os requisitos e os artefatos gerados nas atividades de desenvolvimento subsequentes.

No contexto da rastreabilidade entre requisitos, o "forward-from" consiste no mapeamento das dependências entre os requisitos. Isso significa identificar se um requisito refina outro requisito, generaliza ou substitui algum requisito anterior. Por exemplo, um requisito pode ser uma evolução de outro requisito existente, incorporando novas funcionalidades ou modificando as existentes. Essa relação de dependência é importante para entender como os requisitos se relacionam entre si e para garantir que todos sejam adequadamente atendidos durante o desenvolvimento do software.


## Metodologia

A metodologia adotada foi o *Meta-modelo de Toranzo*[¹](), que propõe quatro níveis de classificação para as informações rastreadas, sendo eles:

- **Ambiental**: informações oriundas do ambiente em que está inserida a organização e como podem afetar o desenvolvimento do sistema
- **Organizacional**: informações relacionadas a organização (metas, padrões e objetivos) e seus respectivos impactos nos requisitos do sistema
- **Gerecial**: informações que permitem associar requisitos com tarefas, auxiliando na gestão do projeto
- **Desenvolvimento**: informações relacionadas aos artefatos gerados durante o desenvolvimento (diagramas, testes, etc.)

Dentro deste Meta-modelo, o suporte à rastreabilidade identifica diferentes tipos de elos, sendo eles:

- **Satisfação**: indica a classe de origem que depende da satisfação da classe de destino
- **Recurso**: indica a classe de origem que depende de recurso(s) da classe de destino
- **Responsabilidade**: indica a partipação de pessoas sobre os artefatos (responsabilidades e ações)
- **Representação**: representação ou modelagem dos requisitos em outras linguagens
- **Alocado**: classe de origem relacionada a classe de destino, representando subsistema
- **Agregação**: indica composição de elementos

## Matriz

Os requisitos funcionais e não funcionais previmente elicitados foram analisados e listados em uma tabela, formando uma matriz. Para isto, foi necessário verificar o estado da implementação dos requisitos, ou efetuar a criação dos protótipos caso não tivessem implementados na aplicação. Cada requisito foi analisado por determinado aluno, cobrindo assim todos os requisitos elicitados.

A Tabela 1 apresenta a legenda utilizada para identificar os diferentes tipos de artefatos.

| Legenda | Artefato                  |
| ------- | ------------------------- |
| US      | História de Usuário       |
| EPI     | Épico (backlog)           |
| ST      | Storytelling              |
| CDU     | Casos de Uso              |
| CEN     | Cenários                  |
| ESP     | Especificação Suplementar |
| INT     | Introspecção              |
| QUE     | Questionário              |
| ADD     | Análise de Documentos     |
| RF      | Requisitos Funcionais     |
| RNF     | Requisitos não Funcionais |

<div>
<p> Tabela 1: Legenda (Fonte: MEISTER, Guilherme. 2024).</p>
</div>

A tabela 2 abaixo apresenta a matriz ***forward form***, relacionando os requisitos com seus respectivos artefatos e elos:

| REQUISITO | ARTEFATOS | IMPLEMENTAÇÃO | REPRESENTAÇÃO | ELO |
| :--: | :--: | :--: | :--: | :--: |
| RF1 | [EPI1](https://requisitos-de-software.github.io/2024.1-Consumidor.gov/Modelagem/Modelagem%20Ágil/Backlog/#epico-1-abertura-e-acompanhamento-de-reclamacoes); [HUS1](https://requisitos-de-software.github.io/2024.1-Consumidor.gov/Modelagem/Modelagem%20Ágil/Historias/#us1-login-no-aplicativo); | IMPLEMENTADO |  |  |
| RF2 | [CDU01](https://requisitos-de-software.github.io/2024.1-Consumidor.gov/Modelagem/casosdeuso/#uc01); [CEN01](https://requisitos-de-software.github.io/2024.1-Consumidor.gov/Modelagem/cenarios/#c01-pesquisar-empresa-pelo-nome); [LEX01](https://requisitos-de-software.github.io/2024.1-Consumidor.gov/Modelagem/lexicos/#tabela-4-lexico-01-pesquisar-empresa-l01); [HUS2](https://requisitos-de-software.github.io/2024.1-Consumidor.gov/Modelagem/Modelagem%20Ágil/Historias/#us2-pesquisar-empresa) | IMPLEMENTADO |  |  |  |
| RF3 |  | PARCIAL |  |  |  |
| RF4 |  | IMPLEMENTADO |  |  |  |
| RF5 |  | IMPLEMENTADO |  |  |  |
| RF6 |  | IMPLEMENTADO |  |  |  |
| RF7 |  | IMPLEMENTADO |  |  |  |
| RF8 | | IMPLEMENTADO |  |  |  |
| RF9 | | IMPLEMENTADO |  |  |  |
| RF10 | | IMPLEMENTADO |  |  |  |
| RF11 | | IMPLEMENTADO |  |  |  |
| RF12 | | NÃO IMPLEMENTADO |  |  |  |
| RF13 | | IMPLEMENTADO |  |  |  |
| RF14 | | IMPLEMENTADO |  |  |  |
| RF15 | | IMPLEMENTADO |  |  |  |
| RF16 | | INDEFINIDO* |  |  |  |
| RF17 | | INDEFINIDO* |  |  |  |
| RF18 | | INDEFINIDO* |  |  |  |
| RF19 | | IMPLEMENTADO |  |  |  |
| RF20 | | IMPLEMENTADO |  |  |  |
| RF21 | | IMPLEMENTADO |  |  |  |
| RF22 | | IMPLEMENTADO |  |  |  |
| RF23 | | IMPLEMENTADO |  |  |  |
| RF24 | | IMPLEMENTADO |  |  |  |
| RF25 | | IMPLEMENTADO |  |  |  |
| RNF1 | | IMPLEMENTADO |  |  |  |
| RNF2 | | IMPLEMENTADO* |  |  |  |
| RNF3 | | NÃO IMPLEMENTADO |  |  |  |
| RNF4 | | IMPLEMENTADO* |  |  |  |
| RNF5 | | INDEFINIDO* |  |  |  |
| RNF6 | | IMPLEMENTADO |  |  |  |
| RNF7 | | IMPLEMENTADO* |  |  |  |
| RNF8 | | IMPLEMENTADO* |  |  |  |
| RNF9 | | INDEFINIDO* |  |  |  |
| RNF10 | IMPLEMENTADO* |  |  |  |  |
| RNF11 | PARCIAL |  |  |  |  |
| RNF12 | IMPLEMENTADO |  |  |  |  |
| RNF13 | INDEFINIDO* |  |  |  |  |
| RNF14 | IMPLEMENTADO |  |  |  |  |

### Observações

- Requisitos com a *implementação* descrita como INDEFINIDO* foram marcados desta forma devido ao fato de serem funcionalidades imaginadas pela equipe, uma vez a mesma não possui acesso ao "ponto de vista" da empresa dentro do aplicativo,  ou devido a falta de informações sobre a arquitetura do aplicativo **Consumidor.gov**.

- Requisitos com a *implementação* descrita como IMPLEMENTADO* foram marcados desta forma devido ao fato de serem testáveis, porém as métricas estabelecidas podem ser ultrapassadas devido a certos fatores (problemas de conexão, inexperiência de usuário, etc).

<div>
<p> Tabela 2: Matriz Forward Form (Fonte: MEISTER, Guilherme. 2024).</p>
</div>

## Elos

| ID | REQUISITO | SATISFAÇÃO | RECURSO | REPRESENTAÇÃO | ALOCADO | AGREGAÇÃO |
| :--: | :--: | :--: | :--: | :--: | :--: | :--: |
| EF1  | RF1 | US1 | UC1 A UC8 |  | NFR01 | - |
| EF2  | RF2 | US2 | UC1, CEN1, LEX1 |  | NF01 | RF3 A RF9| 
| EF3  | RF3 | US3 |  |  | NFR01 | RF4 |
| EF4  | RF4 |  |  |  |  |  |
| EF5  | RF5 |  |  |  |  |  |
| EF6  | RF6 |  |  |  |  |  |
| EF7  | RF7 |  |  |  |  |  |
| EF8  | RF8  | |  |  |  |  |
| EF9  | RF9  | |  |  |  |  |
| EF10 | RF10 | |  |  |  |  |
| EF11 | RF11 | |  |  |  |  |
| EF12 | RF12 | |  |  |  |  |
| EF13 | RF13 | |  |  |  |  |
| EF14 | RF14 | |  |  |  |  |
| EF15 | RF15 | |  |  |  |  |
| EF16 | RF16 | |  |  |  |  |
| EF17 | RF17 | |  |  |  |  |
| EF18 | RF18 | |  |  |  |  |
| EF19 | RF19 | |  |  |  |  |
| EF20 | RF20 | |  |  |  |  |
| EF21 | RF21 | |  |  |  |  |
| EF22 | RF22 | |  |  |  |  |
| EF23 | RF23 | |  |  |  |  |
| EF24 | RF24 | |  |  |  |  |
| EF25 | RF25 | |  |  |  |  |
| EF26 | RNF1 | |  |  |  |  |
| EF27 | RNF2 | |  |  |  |  |
| EF28 | RNF3 | |  |  |  |  |
| EF29 | RNF4 | |  |  |  |  |
| EF30 | RNF5 | |  |  |  |  |
| EF31 | RNF6 | |  |  |  |  |
| EF32 | RNF7 | |  |  |  |  |
| EF33 | RNF8 | |  |  |  |  |
| EF34 | RNF9 | |  |  |  |  |
| EF35 | RNF10 | |  |  |  |  |
| EF36 | RNF11 | |  |  |  |  |
| EF37 | RNF12 | |  |  |  |  |
| EF38 | RNF13 | |  |  |  |  |
| EF39 | RNF14 | |  |  |  |  |

## Bibliografia

[1] SERRANO, Milene; SERRANO, Maurício. Requisitos - Aula 26. 2019. Disponível em: <https://aprender3.unb.br/pluginfile.php/2845096/mod_resource/content/1/Requisitos%20-%20Aula%20026.pdf>. Acesso em: 12 de jun de 2024. Acessado em: 12 de junho de 2024

[2] POHL, Klaus; RUPP, Chris. Requirements Engineering Fundamental. Acessado em 12 de junho de 2024

[3] SAYÃO, Miriam; LEITE, Julio. Rastreabilidade de Requisitos. PUC-Rio: Departamento de Informática, ISSN 0103-9741, Rio de Janeiro, 2005. Disponível em: <https://aprender3.unb.br/pluginfile.php/2845099/mod_resource/content/3/05_20_sayao.pdf>. Acesso em: 12 de jun de 2024.

## Histórico de Versões

| Versão | Data de execução | Data de revisão |  Descrição                          | Autor(es)                                           | Revisor(es)                                           |
| :----: | :--------------: | :-------------: | :---------------------------------: | :-------------------------------------------------: | :---------------------------------------------------: |
| 1.2    | 20/06/2024       | 20/06/2024      | Adicionando elos   | Guilherme Meister, Henrique Galdino, Igor Thiago, Júlio César, Matheus Ferreira, Rodrigo Gontijo   | Guilherme Meister, Henrique Galdino, Igor Thiago, Júlio César, Matheus Ferreira, Rodrigo Gontijo |
| 1.1    | 16/06/2024       | 16/06/2024      | Corrigindo e complementando metodologia e tabelas   | [Henrique Galdino](https://github.com/hgaldino05)   | [Júlio César](https://github.com/Julio1099)         |
| 1.0    | 12/06/2024       | 12/06/2024      | Criação do artefato | [Guilherme Meister](https://github.com/gmeister18)   | [Henrique Galdino](https://github.com/hgaldino05)     |
