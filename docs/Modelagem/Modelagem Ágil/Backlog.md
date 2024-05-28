# Backlog do Produto

## Introdução


<p>&emsp;&emsp;Refere-se a uma lista priorizada de requisitos do produto, onde cada item representa uma funcionalidade, melhoria, correção de defeitos ou qualquer outra demanda relacionada ao produto que precisa ser implementada pela equipe de desenvolvimento. isso permite um planejamento melhor das sprints em técnicas ágeis[1].</p>
<p>&emsp;&emsp; É importante salientar que novos itens importantes podem compor o backlog a qualquer etapa do desenvolvimento. Os requisitos associados ao backlog podem ser fragmentados em diferentes níveis de abstração, e hierárquicos, sendo eles épicos, temas e histórias de usuário[2].</p>


## Vantagens de usar o backlog 

- Facilita a comunicação e o alinhamento entre todos os stakeholders sobre as prioridades e o progresso do projeto.
- Prioriza as funcionalidades mais valiosas, garantindo que a equipe trabalhe nas tarefas que trazem mais benefícios ao negócio.
- Permite ajustes rápidos às mudanças e novas informações, mantendo o projeto alinhado com as necessidades atuais.
- A revisão constante dos itens do backlog promove a refinamento progressivo e a melhoria contínua do produto.
- Considera os produtos em longo prazo, não apenas em termos de necessidades imediatas.
- Agrega valor ao cliente
- Identifica antecipadamente possíveis problemas, permitindo a mitigação de riscos antes que se tornem críticos.


## Metodologia

<p>&emsp;&emsp; Para a metodologia foi utilizado uma planilha em excel para organizar em temas e épico dos requisitos funcionais, partindo da análise e verificação dos mesmos elicitados. Posteriormente os dados vieram o artefato. </p>

## Requisitos Elicitados
<div style="text-align:justify">
<p>&emsp;&emsp; Nas Tabelas de 1 a 5 estão registrados todos os requisitos elicitados durante o processo de elicitação, juntamente com a rastreabilidade de cada um.</p>
</div>

### 3.1. Abertura e acompanhamento de reclamações

| Identificador  |     Descrição    | Origem|
| :-: | :----------------------------------------:|:------------------:|
| R1 | Deve ser possível fazer login utilizando o gov.br |[INT01](https://requisitos-de-software.github.io/2024.1-Consumidor.gov/Elicitação/introspec/#metodologia);  [ST12](https://requisitos-de-software.github.io/2024.1-Consumidor.gov/Elicitação/Storytelling/)|
| RF5 | Deve ser possível informar as circunstâncias da compra do produto/serviço (internet, loja física, telefone, etc.) |[INT05](https://requisitos-de-software.github.io/2024.1-Consumidor.gov/Elicitação/introspec/#metodologia);[ST01, ST03](https://requisitos-de-software.github.io/2024.1-Consumidor.gov/Elicitação/Storytelling/)|
| RF6 | Deve ser possível escolher qual a categoria da reclamação (atendimento, cobrança, entrega, etc.) |[INT06](https://requisitos-de-software.github.io/2024.1-Consumidor.gov/Elicitação/introspec/#metodologia);[ST01, ST03](https://requisitos-de-software.github.io/2024.1-Consumidor.gov/Elicitação/Storytelling/)|
| RF7 | Deve ser possível fornecer detalhes sobre a reclamação |[INT07](https://requisitos-de-software.github.io/2024.1-Consumidor.gov/Elicitação/introspec/#metodologia);[ST01, ST03](https://requisitos-de-software.github.io/2024.1-Consumidor.gov/Elicitação/Storytelling/)|
| RF8 | Deve ser possível informar o que espera da empresa (reembolso, resposta, justificativa, etc.) |[INT08](https://requisitos-de-software.github.io/2024.1-Consumidor.gov/Elicitação/introspec/#metodologia);[ST01, ST03](https://requisitos-de-software.github.io/2024.1-Consumidor.gov/Elicitação/Storytelling/)|
| RF9 | Deve ser possível anexar arquivos relacionados a reclamação (prints, nota fiscal, ordem de serviço, etc.) |[INT09](https://requisitos-de-software.github.io/2024.1-Consumidor.gov/Elicitação/introspec/#metodologia);[ST01, ST03](https://requisitos-de-software.github.io/2024.1-Consumidor.gov/Elicitação/Storytelling/; [ST07](https://requisitos-de-software.github.io/2024.1-Consumidor.gov/Elicitação/Storytelling/))|
| RF10 | Deve ser possível visualizar as reclamações feitas no app | [QUE04](https://requisitos-de-software.github.io/2024.1-Consumidor.gov/Elicitação/Questionário/#possiveis-requisitos); [INT10](https://requisitos-de-software.github.io/2024.1-Consumidor.gov/Elicitação/introspec/#metodologia); [ADD01](https://requisitos-de-software.github.io/2024.1-Consumidor.gov/Elicitação/analiseDoc/) |
| RF11 | Deve ser possível acompanhar o status de uma reclamação feita | [QUE06, QUE11](https://requisitos-de-software.github.io/2024.1-Consumidor.gov/Elicitação/Questionário/#possiveis-requisitos); [INT10, INT11](https://requisitos-de-software.github.io/2024.1-Consumidor.gov/Elicitação/introspec/#metodologia)|
| RF12 | Deve ser possível receber notificações sobre o status de reclamações | [QUE11](https://requisitos-de-software.github.io/2024.1-Consumidor.gov/Elicitação/Questionário/#possiveis-requisitos); [INT10,INT11](https://requisitos-de-software.github.io/2024.1-Consumidor.gov/Elicitação/introspec/#metodologia) |
| RF15 | Deve ser possível avaliar uma reclamação (nível de satisfação/nota) | [QUE11](https://requisitos-de-software.github.io/2024.1-Consumidor.gov/Elicitação/Questionário/#possiveis-requisitos); [INT15](https://requisitos-de-software.github.io/2024.1-Consumidor.gov/Elicitação/introspec/#metodologia) |
| RF16 | Deve ser possível cadastrar os dados de uma empresa | [QUE11](https://requisitos-de-software.github.io/2024.1-Consumidor.gov/Elicitação/Questionário/#possiveis-requisitos); [INT15](https://requisitos-de-software.github.io/2024.1-Consumidor.gov/Elicitação/introspec/#metodologia) |
| RF17 | Deve ser possível fazer upload da logomarca para o cadastro de uma empresa | [QUE11](https://requisitos-de-software.github.io/2024.1-Consumidor.gov/Elicitação/Questionário/#possiveis-requisitos); [INT15](https://requisitos-de-software.github.io/2024.1-Consumidor.gov/Elicitação/introspec/#metodologia) |
| RF18 | Deve ser possível anexar documentos para o cadastro de uma empresa | [QUE11](https://requisitos-de-software.github.io/2024.1-Consumidor.gov/Elicitação/Questionário/#possiveis-requisitos); [INT15](https://requisitos-de-software.github.io/2024.1-Consumidor.gov/Elicitação/introspec/#metodologia) |
| RF23 | Deve ser possível responder uma reclamação feita | [QUE11](https://requisitos-de-software.github.io/2024.1-Consumidor.gov/Elicitação/Questionário/#possiveis-requisitos); [INT15](https://requisitos-de-software.github.io/2024.1-Consumidor.gov/Elicitação/introspec/#metodologia) |

<div align="center">
<p> <b>Tabela 1</b>: Funcionalidades (Autor: MEISTER, Guilherme 2024). </p>
</div>

### 3.2. Pesquisa de empresa

| ID  | Requisito                                                               | Rastreabilidade                           |
| --- | ----------------------------------------------------------------------- | ----------------------------------------- |
| RF2 | Deve ser possível pesquisar uma empresa pelo nome |[INT02, INT03](https://requisitos-de-software.github.io/2024.1-Consumidor.gov/Elicitação/introspec/#metodologia)|
| RNF8 | As ações principais do site (ex.:fazer reclamação, ver reclamação) devem ser executadas em no máximo 5 passos  | [ST](https://requisitos-de-software.github.io/2024.1-Consumidor.gov/Elicita%C3%A7%C3%A3o/Storytelling/) |
| RNF14 | Aplicativo deve estabelecer e seguir um padrão de cores e tamanhos para suas interfaces/componentes | [QUE](https://requisitos-de-software.github.io/2024.1-Consumidor.gov/Elicita%C3%A7%C3%A3o/Question%C3%A1rio/) |
| RF13 | Deve ser possível visualizar reclamações feitas por outros usuários |[QUE04](https://requisitos-de-software.github.io/2024.1-Consumidor.gov/Elicitação/Questionário/#possiveis-requisitos); [INT12, INT13](https://requisitos-de-software.github.io/2024.1-Consumidor.gov/Elicitação/introspec/#metodologia); [ST05](https://requisitos-de-software.github.io/2024.1-Consumidor.gov/Elicitação/Storytelling/); [ADD01](https://requisitos-de-software.github.io/2024.1-Consumidor.gov/Elicitação/analiseDoc/)|
| RF14 | Deve ser possível visulizar detalhes de uma reclamação de outro usuário (status, avaliação, tempo de resposta, etc.) | [QUE04](https://requisitos-de-software.github.io/2024.1-Consumidor.gov/Elicitação/Questionário/#possiveis-requisitos); [INT12,INT13](https://requisitos-de-software.github.io/2024.1-Consumidor.gov/Elicitação/introspec/#metodologia); [ST05](https://requisitos-de-software.github.io/2024.1-Consumidor.gov/Elicitação/Storytelling/); [ADD01](https://requisitos-de-software.github.io/2024.1-Consumidor.gov/Elicitação/analiseDoc/)|
| RF19 | Deve ser possível visualizar as reclamações feitas sobre uma empresa | [QUE11](https://requisitos-de-software.github.io/2024.1-Consumidor.gov/Elicitação/Questionário/#possiveis-requisitos); [INT15](https://requisitos-de-software.github.io/2024.1-Consumidor.gov/Elicitação/introspec/#metodologia); [ST04](https://requisitos-de-software.github.io/2024.1-Consumidor.gov/Elicitação/Storytelling/) |
| RF20 | Deve ser possível visualizar como o cliente fez a compra | [QUE11](https://requisitos-de-software.github.io/2024.1-Consumidor.gov/Elicitação/Questionário/#possiveis-requisitos); [INT15](https://requisitos-de-software.github.io/2024.1-Consumidor.gov/Elicitação/introspec/#metodologia) |
| RF21 | Deve ser possível visualizar qual tipo de reclamação o cliente apresentou | [QUE11](https://requisitos-de-software.github.io/2024.1-Consumidor.gov/Elicitação/Questionário/#possiveis-requisitos); [INT15](https://requisitos-de-software.github.io/2024.1-Consumidor.gov/Elicitação/introspec/#metodologia) |
| RF22 | Deve ser possível visualizar os detalhes e anexos de uma reclamação sobre uma empresa | [QUE11](https://requisitos-de-software.github.io/2024.1-Consumidor.gov/Elicitação/Questionário/#possiveis-requisitos); [INT15](https://requisitos-de-software.github.io/2024.1-Consumidor.gov/Elicitação/introspec/#metodologia) |
| RF24 | Deve ser possível visualizar estatísticas das reclamações sobre uma empresa | [QUE05](https://requisitos-de-software.github.io/2024.1-Consumidor.gov/Elicitação/Questionário/#possiveis-requisitos); [INT15](https://requisitos-de-software.github.io/2024.1-Consumidor.gov/Elicitação/introspec/#metodologia) |
| RF25 | Deve ser possível visualizar avaliação das reclamações | [QUE05](https://requisitos-de-software.github.io/2024.1-Consumidor.gov/Elicitação/Questionário/#possiveis-requisitos); [INT15](https://requisitos-de-software.github.io/2024.1-Consumidor.gov/Elicitação/introspec/#metodologia) |

<div align="center">
<p> <b>Tabela 2</b>: Interface de usuário (Autor: MEISTER, Guilherme 2024). </p>
</div>

### 3.3. Desempenho

| ID  | Requisito                                                               | Rastreabilidade                           |
| --- | ----------------------------------------------------------------------- | ----------------------------------------- |
| RNF7 | O aplicativo deve iniciar o carregamento de telas/componentes em até 2 segundos | [ST](https://requisitos-de-software.github.io/2024.1-VLC/#/elicitacao/storytelling) |
| RNF9 | O aplicativo não deve ficar indisponível por mais de 24 horas (exceto sob aviso prévio) | [INT](https://requisitos-de-software.github.io/2024.1-Consumidor.gov/Elicitação/introspec/#metodologia) |
| RNF10 | O aplicativo deve carregar interfaces e/ou componentes dentro de 20 segundos | [INT](https://requisitos-de-software.github.io/2024.1-Consumidor.gov/Elicitação/introspec/#metodologia) |

<div align="center">
<p> <b>Tabela 4</b>: Desempenho (Autor: MEISTER, Guilherme 2024). </p>
</div>

### 3.4. Segurança e Privacidade

| ID  | Requisito                                                               | Rastreabilidade                           |
| --- | ----------------------------------------------------------------------- | ----------------------------------------- |
| RNF4 | O aplicativo deve fornecer feedback ao usuário em caso de erros/falhas |[QUE08, QUE09](https://requisitos-de-software.github.io/2024.1-Consumidor.gov/Elicitação/introspec/#metodologia); [INT41](https://requisitos-de-software.github.io/2024.1-Consumidor.gov/Elicitação/introspec/#requisitos-nao-funcionais); [ST09](https://requisitos-de-software.github.io/2024.1-Consumidor.gov/Elicitação/Storytelling/)|
| RNF5 | Todos os dados sensíveis devem ser devidamente protegidos utilizando criptografia |[INT42, INT43](https://requisitos-de-software.github.io/2024.1-Consumidor.gov/Elicitação/introspec/#requisitos-nao-funcionais); [ADD09, ADD11, ADD13](https://requisitos-de-software.github.io/2024.1-Consumidor.gov/Elicitação/analiseDoc/)|
| RNF6 | O aplicativo deve validar a entrada do usuário(gov.br) para prevenção de ataques |[INT13](https://requisitos-de-software.github.io/2024.1-Consumidor.gov/Elicitação/introspec/#metodologia); [ADD09, ADD11, ADD13](https://requisitos-de-software.github.io/2024.1-Consumidor.gov/Elicitação/analiseDoc/)|
<div align="center">
<p> <b>Tabela 5</b>: Segurança e Privacidade (Autor: MEISTER, Guilherme 2024). </p>
</div>

## Backlog 

### Temas 
<div style="text-align:justify">
    <p>&emsp;&emsp; Após a etapa de verificação e análise dos requisitos, foi observado que eles poderiam ser organizados em cinco grandes temas, que compõem o maior nível de abstração do backlog.</p>
    <ul>
        <li> Abertura de reclamação 
        <li> Avaliações
        <li> Acessibilidade
        <li> Segurança
        <li> Desempenho
    </ul>
    <p>&emsp;&emsp; Após a definição dos temas, os requisitos foram especificados em um maior nível de abstração, por meio dos épicos. Os épicos são histórias de usuário que ainda podem ser mais especificadas e foram escritos utilizando o mesmo padrão do utilizado nas histórias de usuário.</p>
</div>

### Épicos 

<div style="text-align: justify">

&emsp;&emsp; Para diminuir o nível de abstração expresso nos temas, foram registrados os épicos, que são histórias de usuário que ainda podem ser mais especificadas. Para facilitar a leitura do backlog, os épicos estão especificados a seguir.

</div>

- #### Épico 1: Abertura e acompanhamento de reclamações

    - Requisitos relacionados: RF1, RF5, RF6, RF7, RF8 ,RF9 RF10, RF11, RF12, RF13, RF14, RF15, RF16, RF17, RF18, RF23.
    - Descrição: Este épico aborda a funcionalidade principal do Consumidor.gov, que é a de abrir reclamações. Ele inclui requisitos como visualizar as reclamações feitas, avaliar uma reclamação (nível de satisfação/nota), escolher qual a categoria da reclamação (atendimento, cobrança, entrega, etc.), informar o que espera da empresa (reembolso, resposta, justificativa, etc.).

- #### Épico 2: Pesquisa de empresa

    - Requisitos relacionados: RF2, RF3, RF4, RF13, RF14, RF19, RF20, RF21, RF22, RF24, RF25.
    - Descrição: Este épico trata da interface de usuário do Consumidor.gov. Ele engloba requisitos como uma interface de usuário deve ter contraste de cor, interface facilmente acessível e de fácil compreensão.


- #### Épico 3: Desempenho

    - Requisitos relacionados: RNF7, RNF9, RNF10.
    - Descrição: Este épico trata dos requisitos de desempenho do Consumidor.gov. Inclui requisitos como resposta rápidos para garantir uma experiência de usuário satisfatória e O aplicativo deve ter uma boa performance e velocidade.

- #### Épico 4: Segurança e Privacidade

    - Requisitos relacionados: RNF4, RNF5, RNF6
    - Descrição: Este épico aborda os requisitos de segurança e privacidade do Consumidor.gov. Inclui requisitos como gproteger os dados sensíveis do usuário, apresentar medidas de proteção, Fornecimento de informações funcione corretamente.

A tabela 6 abaixo vai relacionar a prioridade de cada história:

| História de Usuário | Épico                  | Prioridade |
|--------------------|------------------------------------------------------|--------------------------------------------------------------------------------|
| US01               | Épico 1 |   Must |
| US02               | Épico 2 |  Must      |
| US03               | Épico 2  | Must       |
| US04               | Épico 1  | Must       |
| US05               | Épico 1 | Must  |
| US06               | Épico 1   | Must      |
| US07               | Épico 1  | Must      |
| US08               | Épico 1   | Could      |
| US09               | Épico 2 | Could |
| US10               | Épico 1  | Must      |
| US11               | Épico 1   | Could      |
| US12               | Épico 1  | Must     |
| US13               | Épico 3   | Could      |
| US14               | Épico 3   | Must      |
| US15               | Épico 4   | Could      |
| US16               | Épico 4   | Must      |
| US17               | Épico 3   | Could      |

<div align="center">
<p> <b>Tabela 6</b>: Backlog do produto (Autor: MEISTER, Guilherme 2024). </p>
</div>


## Bibliografia

- RADIGAN, Dan. O backlog do produto: sua lista de tarefas definitiva. Atlassian. Disponível em: [Backlog](https://www.atlassian.com/br/agile/scrum/backlogs)

- O QUE É BACKLOG DO PRODUTO SCRUM E COMO FAZER UM. Lucidchart. Disponível em: [Backlog](https://www.lucidchart.com/blog/pt/como-fazer-um-backlog-do-produto)

## Histórico de Versões
|   Data     | Versão | Descrição                   |    Autor(es)     |  Data de revisão | Revisor(es) |
| :--------: | :----: | :-------------------------: | :--------------: | :--------------: | :---------: |
| 23/05/2024   |  `1.0`  | Criação do documento               | [Guilherme Meister](https://github.com/gmeister18) | 25/05/2024 | [Matheus Ferreira](https://github.com/) |
| 27/05/2024   |  `1.1`  | Atualização do documento               | [Guilherme Meister](https://github.com/gmeister18) | 27/05/2024 | [Matheus Ferreira](https://github.com/) |

