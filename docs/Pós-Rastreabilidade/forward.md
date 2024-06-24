# Forward From

## Introdução

<!-- A rastreabilidade é a capacidade de descrever e acompanhar a vida de um requisito, desde sua origem, passando por seu desenvolvimento e especificação, até sua posterior implantação e uso. Ela é essencial para garantir que todos os requisitos tenham sido atendidos e para gerenciar mudanças nos requisitos ao longo do ciclo de vida do projeto.

A rastreabilidade é crucial para a gerência por requisitos e para a detecção de conflitos, além de ser essencial para o gerenciamento do desenvolvimento e controle de riscos. Ela ajuda a detectar requisitos não alocados a componentes e a gerenciar as mudanças e a evolução do sistema.

A rastreabilidade pode ser implementada por meio de elos ou ligações entre requisitos inter-relacionados, suas fontes, e os componentes que os implementam. Técnicas comuns incluem o uso de referências cruzadas e matrizes de rastreabilidade, frequentemente suportadas por ferramentas de software. -->

O "forward-from" (para frente, a partir de) é uma abordagem de pós-rastreabilidade que envolve a coleta de informações de rastreabilidade entre os requisitos e os artefatos gerados nas atividades de desenvolvimento subsequentes.

No contexto da rastreabilidade entre requisitos, o "forward-from" consiste no mapeamento das dependências entre os requisitos. Isso significa identificar se um requisito refina outro requisito, generaliza ou substitui algum requisito anterior. Por exemplo, um requisito pode ser uma evolução de outro requisito existente, incorporando novas funcionalidades ou modificando as existentes. Essa relação de dependência é importante para entender como os requisitos se relacionam entre si e para garantir que todos sejam adequadamente atendidos durante o desenvolvimento do software.


## Metodologia

A metodologia adotada foi o *Meta-modelo de Toranzo*[¹](https://requisitos-de-software.github.io/2024.1-Consumidor.gov/P%C3%B3s-Rastreabilidade/forward/#anchor_1), que propõe quatro níveis de classificação para as informações rastreadas, sendo eles:

- **Ambiental**: informações oriundas do ambiente em que está inserida a organização e como podem afetar o desenvolvimento do sistema
- **Organizacional**: informações relacionadas a organização (metas, padrões e objetivos) e seus respectivos impactos nos requisitos do sistema
- **Gerencial**: informações que permitem associar requisitos com tarefas, auxiliando na gestão do projeto
- **Desenvolvimento**: informações relacionadas aos artefatos gerados durante o desenvolvimento (diagramas, testes, etc.)

No contexto do projeto, as informações apresentadas neste artefato *Forward From*  se encaixam na classificação **Desenvolvimento**, visto que os requisitos e os documentos/artefatos desenvolvidos a partir dos mesmos apresentam informações fundamentais para o desenvolvimento do projeto.


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
| HUS      | História de Usuário       |
| EPI     | Épico (backlog)           |
| CDU     | Casos de Uso              |
| CEN     | Cenários                  |
| LEX     | Léxicos |
| NFR     | NFR Framework |
| ESP     | Especificação Suplementar |
| RF      | Requisitos Funcionais     |
| RNF     | Requisitos não Funcionais |

<div>
<p> Tabela 1: Legenda (Autor: MEISTER, Guilherme. 2024).</p>
</div>

A tabela 2 abaixo apresenta a matriz ***forward form***, relacionando os requisitos com seus respectivos artefatos e elos:

| REQUISITO | ARTEFATOS | IMPLEMENTAÇÃO | REPRESENTAÇÃO | ELO |
| :--: | :--: | :--: | :--: | :--: |
| RF1 | [EPI1](https://requisitos-de-software.github.io/2024.1-Consumidor.gov/Modelagem/Modelagem%20Ágil/Backlog/#epico-1-abertura-e-acompanhamento-de-reclamacoes); [HUS1](https://requisitos-de-software.github.io/2024.1-Consumidor.gov/Modelagem/Modelagem%20Ágil/Historias/#us1-login-no-aplicativo); | IMPLEMENTADO |  |  |
| RF2 | [CDU01](https://requisitos-de-software.github.io/2024.1-Consumidor.gov/Modelagem/casosdeuso/#uc01); [CEN01](https://requisitos-de-software.github.io/2024.1-Consumidor.gov/Modelagem/cenarios/#c01-pesquisar-empresa-pelo-nome); [LEX01](https://requisitos-de-software.github.io/2024.1-Consumidor.gov/Modelagem/lexicos/#tabela-4-lexico-01-pesquisar-empresa-l01); [HUS2](https://requisitos-de-software.github.io/2024.1-Consumidor.gov/Modelagem/Modelagem%20Ágil/Historias/#us2-pesquisar-empresa) | IMPLEMENTADO |  |  |  |
| RF3 | [EPI02](https://requisitos-de-software.github.io/2024.1-Consumidor.gov/Modelagem/Modelagem%20%C3%81gil/Backlog/#epico-2-pesquisa-de-empresa); [HUS03](https://requisitos-de-software.github.io/2024.1-Consumidor.gov/Modelagem/Modelagem%20%C3%81gil/Historias/#us3-ver-dados-sobre-uma-empresa) | PARCIAL |  |  |  |
| RF4 | [EPI02](https://requisitos-de-software.github.io/2024.1-Consumidor.gov/Modelagem/Modelagem%20%C3%81gil/Backlog/#epico-2-pesquisa-de-empresa) | IMPLEMENTADO |  |  |  |
| RF5 | [EPI01](https://requisitos-de-software.github.io/2024.1-Consumidor.gov/Modelagem/Modelagem%20%C3%81gil/Backlog/#epico-1-abertura-e-acompanhamento-de-reclamacoes); [HUS04](https://requisitos-de-software.github.io/2024.1-Consumidor.gov/Modelagem/Modelagem%20%C3%81gil/Historias/#us4-fazer-reclamacao); [CEN02](https://requisitos-de-software.github.io/2024.1-Consumidor.gov/Modelagem/cenarios/#c02-cadastrar-reclamacao); [LEX02](https://requisitos-de-software.github.io/2024.1-Consumidor.gov/Modelagem/lexicos/#l02-abrir-reclamacao) | IMPLEMENTADO |  |  |  |
| RF6 | [EPI01](https://requisitos-de-software.github.io/2024.1-Consumidor.gov/Modelagem/Modelagem%20%C3%81gil/Backlog/#epico-1-abertura-e-acompanhamento-de-reclamacoes); [CEN02](https://requisitos-de-software.github.io/2024.1-Consumidor.gov/Modelagem/cenarios/#c02-cadastrar-reclamacao)/ [LEX02](https://requisitos-de-software.github.io/2024.1-Consumidor.gov/Modelagem/lexicos/#l02-abrir-reclamacao) | IMPLEMENTADO |  |  |  |
| RF7 | [EPI01](https://requisitos-de-software.github.io/2024.1-Consumidor.gov/Modelagem/Modelagem%20%C3%81gil/Backlog/#epico-1-abertura-e-acompanhamento-de-reclamacoes); [CDU02](https://requisitos-de-software.github.io/2024.1-Consumidor.gov/Modelagem/casosdeuso/#uc02); [CEN02](https://requisitos-de-software.github.io/2024.1-Consumidor.gov/Modelagem/cenarios/#c02-cadastrar-reclamacao); [LEX02](https://requisitos-de-software.github.io/2024.1-Consumidor.gov/Modelagem/lexicos/#l02-abrir-reclamacao) | IMPLEMENTADO |  |  |  |
| RF8 | [EPI01](https://requisitos-de-software.github.io/2024.1-Consumidor.gov/Modelagem/Modelagem%20%C3%81gil/Backlog/#epico-1-abertura-e-acompanhamento-de-reclamacoes); [CDU02](https://requisitos-de-software.github.io/2024.1-Consumidor.gov/Modelagem/casosdeuso/#uc02); [CEN02](https://requisitos-de-software.github.io/2024.1-Consumidor.gov/Modelagem/cenarios/#c02-cadastrar-reclamacao); [LEX02](https://requisitos-de-software.github.io/2024.1-Consumidor.gov/Modelagem/lexicos/#l02-abrir-reclamacao) | IMPLEMENTADO |  |  |  |
| RF9 | [EPI01](https://requisitos-de-software.github.io/2024.1-Consumidor.gov/Modelagem/Modelagem%20%C3%81gil/Backlog/#epico-1-abertura-e-acompanhamento-de-reclamacoes); [CDU02](https://requisitos-de-software.github.io/2024.1-Consumidor.gov/Modelagem/casosdeuso/#uc02); [HUS05](https://requisitos-de-software.github.io/2024.1-Consumidor.gov/Modelagem/Modelagem%20%C3%81gil/Historias/#us5-anexar-arquivos-na-reclamacao); [LEX02](https://requisitos-de-software.github.io/2024.1-Consumidor.gov/Modelagem/lexicos/#l02-abrir-reclamacao) | IMPLEMENTADO |  |  |  |
| RF10 | [EPI01](https://requisitos-de-software.github.io/2024.1-Consumidor.gov/Modelagem/Modelagem%20%C3%81gil/Backlog/#epico-1-abertura-e-acompanhamento-de-reclamacoes); [CDU04](https://requisitos-de-software.github.io/2024.1-Consumidor.gov/Modelagem/casosdeuso/#uc04); [HUS06](https://requisitos-de-software.github.io/2024.1-Consumidor.gov/Modelagem/Modelagem%20%C3%81gil/Historias/#us6-visualizar-reclamacoes-feitas-no-app); [CEN04](https://requisitos-de-software.github.io/2024.1-Consumidor.gov/Modelagem/cenarios/#c04-visualizar-minhas-reclamacoes); [LEX04](https://requisitos-de-software.github.io/2024.1-Consumidor.gov/Modelagem/lexicos/#l04-visualizar-minhas-reclamacoes) | IMPLEMENTADO |  |  |  |
| RF11 |[EPI01](https://requisitos-de-software.github.io/2024.1-Consumidor.gov/Modelagem/Modelagem%20%C3%81gil/Backlog/#epico-1-abertura-e-acompanhamento-de-reclamacoes); [CDU04](https://requisitos-de-software.github.io/2024.1-Consumidor.gov/Modelagem/casosdeuso/#uc04); [HUS07](https://requisitos-de-software.github.io/2024.1-Consumidor.gov/Modelagem/Modelagem%20%C3%81gil/Historias/#us7-acompanhar-status-de-uma-reclamacao); [CEN04](https://requisitos-de-software.github.io/2024.1-Consumidor.gov/Modelagem/cenarios/#c04-visualizar-minhas-reclamacoes); [LEX04](https://requisitos-de-software.github.io/2024.1-Consumidor.gov/Modelagem/lexicos/#l04-visualizar-minhas-reclamacoes) | IMPLEMENTADO |  |  |  |
| RF12 | [EPI01](https://requisitos-de-software.github.io/2024.1-Consumidor.gov/Modelagem/Modelagem%20%C3%81gil/Backlog/#epico-1-abertura-e-acompanhamento-de-reclamacoes); [HUS08](https://requisitos-de-software.github.io/2024.1-Consumidor.gov/Modelagem/Modelagem%20%C3%81gil/Historias/#us8-receber-notificacoes-sobre-o-status-das-reclamacoes) | NÃO IMPLEMENTADO |  |  |  |
| RF13 | [EPI01, EPI02](https://requisitos-de-software.github.io/2024.1-Consumidor.gov/Modelagem/Modelagem%20%C3%81gil/Backlog/#epicos); [CDU03](https://requisitos-de-software.github.io/2024.1-Consumidor.gov/Modelagem/casosdeuso/#uc03); [HUS09](https://requisitos-de-software.github.io/2024.1-Consumidor.gov/Modelagem/Modelagem%20%C3%81gil/Historias/#us9-visualizar-reclamacoes-de-outros-usuarios); [CEN03](https://requisitos-de-software.github.io/2024.1-Consumidor.gov/Modelagem/cenarios/#c03-visualizar-reclamacoes-de-outros-usuarios); [LEX03](https://requisitos-de-software.github.io/2024.1-Consumidor.gov/Modelagem/lexicos/#l03-visualizar-reclamacoes-de-outros-usuarios) | IMPLEMENTADO |  |  |  |
| RF14 | [EPI01](https://requisitos-de-software.github.io/2024.1-Consumidor.gov/Modelagem/Modelagem%20%C3%81gil/Backlog/#epico-1-abertura-e-acompanhamento-de-reclamacoes); [CDU03](https://requisitos-de-software.github.io/2024.1-Consumidor.gov/Modelagem/casosdeuso/#uc03); [CEN03](https://requisitos-de-software.github.io/2024.1-Consumidor.gov/Modelagem/cenarios/#c03-visualizar-reclamacoes-de-outros-usuarios); [LEX03](https://requisitos-de-software.github.io/2024.1-Consumidor.gov/Modelagem/lexicos/#l03-visualizar-reclamacoes-de-outros-usuarios) | IMPLEMENTADO |  |  |  |
| RF15 | [EPI01](https://requisitos-de-software.github.io/2024.1-Consumidor.gov/Modelagem/Modelagem%20%C3%81gil/Backlog/#epico-1-abertura-e-acompanhamento-de-reclamacoes); [HUS10](https://requisitos-de-software.github.io/2024.1-Consumidor.gov/Modelagem/Modelagem%20%C3%81gil/Historias/#us10-avaliar-uma-reclamacao); [CEN08](https://requisitos-de-software.github.io/2024.1-Consumidor.gov/Modelagem/cenarios/#c08-avaliar-empresa); [LEX08](https://requisitos-de-software.github.io/2024.1-Consumidor.gov/Modelagem/lexicos/#l08-avaliar-empresa) | IMPLEMENTADO |  |  |  |
| RF16 | [EPI01](https://requisitos-de-software.github.io/2024.1-Consumidor.gov/Modelagem/Modelagem%20%C3%81gil/Backlog/#epico-1-abertura-e-acompanhamento-de-reclamacoes); [HUS11](https://requisitos-de-software.github.io/2024.1-Consumidor.gov/Modelagem/Modelagem%20%C3%81gil/Historias/) | INDEFINIDO* |  |  |  |
| RF17 | [EPI01](https://requisitos-de-software.github.io/2024.1-Consumidor.gov/Rastreabilidade/matriz/) | INDEFINIDO* |  |  |  |
| RF18 | [EPI01](https://requisitos-de-software.github.io/2024.1-Consumidor.gov/Rastreabilidade/matriz/) | INDEFINIDO* |  |  |  |
| RF19 | [EPI02](https://requisitos-de-software.github.io/2024.1-Consumidor.gov/Modelagem/Modelagem%20%C3%81gil/Backlog/#epico-2-pesquisa-de-empresa) | IMPLEMENTADO |  |  |  |
| RF20 | [EPI02](https://requisitos-de-software.github.io/2024.1-Consumidor.gov/Modelagem/Modelagem%20%C3%81gil/Backlog/#epico-2-pesquisa-de-empresa) | IMPLEMENTADO |  |  |  |
| RF21 | [EPI02](https://requisitos-de-software.github.io/2024.1-Consumidor.gov/Modelagem/Modelagem%20%C3%81gil/Backlog/#epico-2-pesquisa-de-empresa) | IMPLEMENTADO |  |  |  |
| RF22 | [EPI02](https://requisitos-de-software.github.io/2024.1-Consumidor.gov/Modelagem/Modelagem%20%C3%81gil/Backlog/#epico-2-pesquisa-de-empresa) | IMPLEMENTADO |  |  |  |
| RF23 | [EPI01](https://requisitos-de-software.github.io/2024.1-Consumidor.gov/Modelagem/Modelagem%20%C3%81gil/Backlog/#epico-1-abertura-e-acompanhamento-de-reclamacoes); [CDU07](https://requisitos-de-software.github.io/2024.1-Consumidor.gov/Modelagem/casosdeuso/#uc07); [HUS12](https://requisitos-de-software.github.io/2024.1-Consumidor.gov/Modelagem/Modelagem%20%C3%81gil/Historias/#us12-responder-uma-reclamacao); [CEN04, CEN07](https://requisitos-de-software.github.io/2024.1-Consumidor.gov/Modelagem/cenarios/); [LEX07](https://requisitos-de-software.github.io/2024.1-Consumidor.gov/Modelagem/lexicos/#l07-responder-reclamacao) | IMPLEMENTADO |  |  |  |
| RF24 | [EPI02](https://requisitos-de-software.github.io/2024.1-Consumidor.gov/Modelagem/Modelagem%20%C3%81gil/Backlog/#epico-2-pesquisa-de-empresa) | IMPLEMENTADO |  |  |  |
| RF25 | [HUS13](https://requisitos-de-software.github.io/2024.1-Consumidor.gov/Modelagem/Modelagem%20%C3%81gil/Historias/#us13-funcionamento-em-android-e-ios); [ESP](https://requisitos-de-software.github.io/2024.1-Consumidor.gov/Modelagem/especsuplementar/#u-usabilidade); [NFR](https://requisitos-de-software.github.io/2024.1-Consumidor.gov/Modelagem/Modelagem%20Ágil/NFR/) | IMPLEMENTADO |  |  |  |
| RNF1 | [HUS13](https://requisitos-de-software.github.io/2024.1-Consumidor.gov/Modelagem/Modelagem%20%C3%81gil/Historias/#us13-funcionamento-em-android-e-ios); [ESP](https://requisitos-de-software.github.io/2024.1-Consumidor.gov/Modelagem/especsuplementar/#u-usabilidade); [NFR](https://requisitos-de-software.github.io/2024.1-Consumidor.gov/Modelagem/Modelagem%20Ágil/NFR/) | IMPLEMENTADO |  |  |  |
| RNF2 | [CEN](https://requisitos-de-software.github.io/2024.1-Consumidor.gov/Modelagem/cenarios); [ESP](https://requisitos-de-software.github.io/2024.1-Consumidor.gov/Modelagem/especsuplementar/); [NFR](https://requisitos-de-software.github.io/2024.1-Consumidor.gov/Modelagem/Modelagem%20Ágil/NFR/) | IMPLEMENTADO* |  |  |  |
| RNF3 | [HUS14](https://requisitos-de-software.github.io/2024.1-Consumidor.gov/Modelagem/Modelagem%20%C3%81gil/Historias/#us14-opcoes-de-acessibilidade); [ESP](https://requisitos-de-software.github.io/2024.1-Consumidor.gov/Modelagem/especsuplementar/); [NFR](https://requisitos-de-software.github.io/2024.1-Consumidor.gov/Modelagem/Modelagem%20Ágil/NFR/) | NÃO IMPLEMENTADO |  |  |  |
| RNF4 | [EPI04](https://requisitos-de-software.github.io/2024.1-Consumidor.gov/Modelagem/Modelagem%20%C3%81gil/Backlog/#epico-4-seguranca-e-privacidade); [HUS15](https://requisitos-de-software.github.io/2024.1-Consumidor.gov/Modelagem/Modelagem%20%C3%81gil/Historias/#us15-feedback-em-caso-de-erros); [ESP](https://requisitos-de-software.github.io/2024.1-Consumidor.gov/Modelagem/especsuplementar/#u-usabilidade); [NFR](https://requisitos-de-software.github.io/2024.1-Consumidor.gov/Modelagem/Modelagem%20Ágil/NFR/) | IMPLEMENTADO* |  |  |  |
| RNF5 | [EPI04](https://requisitos-de-software.github.io/2024.1-Consumidor.gov/Modelagem/Modelagem%20%C3%81gil/Backlog/#epico-4-seguranca-e-privacidade); [HUS16](https://requisitos-de-software.github.io/2024.1-Consumidor.gov/Modelagem/Modelagem%20%C3%81gil/Historias/#us16-medidas-de-protecao); [ESP](https://requisitos-de-software.github.io/2024.1-Consumidor.gov/Modelagem/especsuplementar/#r-confiabilidade); [NFR](https://requisitos-de-software.github.io/2024.1-Consumidor.gov/Modelagem/Modelagem%20Ágil/NFR/) | INDEFINIDO* |  |  |  |
| RNF6 |  [EPI04](https://requisitos-de-software.github.io/2024.1-Consumidor.gov/Modelagem/Modelagem%20%C3%81gil/Backlog/#epico-4-seguranca-e-privacidade); [HUS16](https://requisitos-de-software.github.io/2024.1-Consumidor.gov/Modelagem/Modelagem%20%C3%81gil/Historias/#us16-medidas-de-protecao); [ESP](https://requisitos-de-software.github.io/2024.1-Consumidor.gov/Modelagem/especsuplementar/#r-confiabilidade); [NFR](https://requisitos-de-software.github.io/2024.1-Consumidor.gov/Modelagem/Modelagem%20Ágil/NFR/) | IMPLEMENTADO |  |  |  |
| RNF7 | [EPI03](https://requisitos-de-software.github.io/2024.1-Consumidor.gov/Modelagem/Modelagem%20%C3%81gil/Backlog/#epico-3-desempenho); [HUS17](https://requisitos-de-software.github.io/2024.1-Consumidor.gov/Modelagem/Modelagem%20%C3%81gil/Historias/#us17-otimizacao-de-carregamento); [ESP](https://requisitos-de-software.github.io/2024.1-Consumidor.gov/Modelagem/especsuplementar/); [NFR](https://requisitos-de-software.github.io/2024.1-Consumidor.gov/Modelagem/Modelagem%20Ágil/NFR/) | IMPLEMENTADO* |  |  |  |
| RNF8 | [ESP](https://requisitos-de-software.github.io/2024.1-Consumidor.gov/Modelagem/especsuplementar/#u-usabilidade); [NFR](https://requisitos-de-software.github.io/2024.1-Consumidor.gov/Modelagem/Modelagem%20Ágil/NFR/) | IMPLEMENTADO* |  |  |  |
| RNF9 | [EPI03](https://requisitos-de-software.github.io/2024.1-Consumidor.gov/Modelagem/Modelagem%20%C3%81gil/Backlog/#epico-3-desempenho); [ESP](https://requisitos-de-software.github.io/2024.1-Consumidor.gov/Modelagem/especsuplementar/#r-confiabilidade); [NFR](https://requisitos-de-software.github.io/2024.1-Consumidor.gov/Modelagem/Modelagem%20Ágil/NFR/) | INDEFINIDO* |  |  |  |
| RNF10 | [EPI03](https://requisitos-de-software.github.io/2024.1-Consumidor.gov/Modelagem/Modelagem%20%C3%81gil/Backlog/#epico-3-desempenho); [ESP](https://requisitos-de-software.github.io/2024.1-Consumidor.gov/Modelagem/especsuplementar); [NFR](https://requisitos-de-software.github.io/2024.1-Consumidor.gov/Modelagem/Modelagem%20Ágil/NFR/) | IMPLEMENTADO* |  |  |  |
| RNF11 | [ESP](https://requisitos-de-software.github.io/2024.1-Consumidor.gov/Modelagem/especsuplementar/#p-performance); [NFR](https://requisitos-de-software.github.io/2024.1-Consumidor.gov/Modelagem/Modelagem%20Ágil/NFR/) | PARCIAL |  |  |  |
| RNF12 | [ESP](https://requisitos-de-software.github.io/2024.1-Consumidor.gov/Modelagem/especsuplementar/#p-performance); [NFR](https://requisitos-de-software.github.io/2024.1-Consumidor.gov/Modelagem/Modelagem%20Ágil/NFR/) | IMPLEMENTADO |  |  |  |
| RNF13 | [ESP](https://requisitos-de-software.github.io/2024.1-Consumidor.gov/Modelagem/especsuplementar/#u-usabilidade); [NFR](https://requisitos-de-software.github.io/2024.1-Consumidor.gov/Modelagem/Modelagem%20Ágil/NFR/) | INDEFINIDO* |  |  |  |
| RNF14 | [HUS17](https://requisitos-de-software.github.io/2024.1-Consumidor.gov/Modelagem/Modelagem%20%C3%81gil/Historias/#us17-otimizacao-de-carregamento); [ESP](https://requisitos-de-software.github.io/2024.1-Consumidor.gov/Modelagem/especsuplementar/#requisitos-de-documentacao); [NFR](https://requisitos-de-software.github.io/2024.1-Consumidor.gov/Modelagem/Modelagem%20Ágil/NFR/) | IMPLEMENTADO |  |  |  |

<div>
<p> Tabela 2: Matriz Forward Form (Fonte: MEISTER, Guilherme. 2024).</p>
</div>

### Observações

- Requisitos com a *implementação* descrita como INDEFINIDO* foram marcados desta forma devido ao fato de serem funcionalidades imaginadas pela equipe, uma vez a mesma não possui acesso ao "ponto de vista" da empresa dentro do aplicativo,  ou devido a falta de informações sobre a arquitetura do aplicativo **Consumidor.gov**.

- Requisitos com a *implementação* descrita como IMPLEMENTADO* foram marcados desta forma devido ao fato de serem testáveis, porém as métricas estabelecidas podem ser ultrapassadas devido a certos fatores (problemas de conexão, inexperiência de usuário, etc).


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
| EF22 | RF22 | [HUS6, HUS9](https://requisitos-de-software.github.io/2024.1-Consumidor.gov/Modelagem/Modelagem%20%C3%81gil/Historias/) | [CDU01, CDU03, CDU04](https://requisitos-de-software.github.io/2024.1-Consumidor.gov/Modelagem/casosdeuso/); [LEX01](https://requisitos-de-software.github.io/2024.1-Consumidor.gov/Modelagem/lexicos/#l01-pesquisar-empresa); [CEN01](https://requisitos-de-software.github.io/2024.1-Consumidor.gov/Modelagem/cenarios/#c01-pesquisar-empresa-pelo-nome) |  | [NFR](https://requisitos-de-software.github.io/2024.1-Consumidor.gov/Modelagem/Modelagem%20%C3%81gil/NFR/#nfr01-usabilidade) | [RF10, RF14](https://requisitos-de-software.github.io/2024.1-Consumidor.gov/Elicita%C3%A7%C3%A3o/requisitos-elicitados/) |
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

## Referência Bibliográfica

> <a id="1" href="#anchor_1">1.</a> SERRANO, Milene; SERRANO, Maurício. Requisitos - Aula 26. 2019. Disponível em: <https://aprender3.unb.br/pluginfile.php/2845096/mod_resource/content/1/Requisitos%20-%20Aula%20026.pdf>. Acesso em: 12 de jun de 2024. Acessado em: 12 de junho de 2024

> <a id="2" href="#anchor_2">2.</a> SAYÃO, Miriam; LEITE, Julio. Rastreabilidade de Requisitos. PUC-Rio: Departamento de Informática, ISSN 0103-9741, Rio de Janeiro, 2005. Disponível em: <https://aprender3.unb.br/pluginfile.php/2845099/mod_resource/content/3/05_20_sayao.pdf>. Acesso em: 12 de jun de 2024.


## Bibliografia

> POHL, Klaus; RUPP, Chris. Requirements Engineering Fundamental. Acessado em 12 de junho de 2024


## Histórico de Versões

| Versão | Data de execução | Data de revisão |  Descrição                          | Autor(es)                                           | Revisor(es)                                           |
| :----: | :--------------: | :-------------: | :---------------------------------: | :-------------------------------------------------: | :---------------------------------------------------: |
| 1.2    | 20/06/2024       | 20/06/2024      | Adicionando elos   | Guilherme Meister, Henrique Galdino, Igor Thiago, Júlio César, Matheus Ferreira, Rodrigo Gontijo   | Guilherme Meister, Henrique Galdino, Igor Thiago, Júlio César, Matheus Ferreira, Rodrigo Gontijo |
| 1.1    | 16/06/2024       | 16/06/2024      | Corrigindo e complementando metodologia e tabelas   | [Henrique Galdino](https://github.com/hgaldino05)   | [Júlio César](https://github.com/Julio1099)         |
| 1.0    | 12/06/2024       | 12/06/2024      | Criação do artefato | [Guilherme Meister](https://github.com/gmeister18)   | [Henrique Galdino](https://github.com/hgaldino05)     |
