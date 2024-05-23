# Requisitos Elicitados

## Introdução

A elicitação de requisitos é uma etapa fundamental no desenvolvimento de software, pois é a partir dos requisitos que o sistema será projetado e implementado. Para a elicitação dos requisitos relacionados ao **Consumidor.gov**, foram utilizadas as seguintes técnicas:

- [Questionário](https://requisitos-de-software.github.io/2024.1-Consumidor.gov/Elicitação/Questionário/)
- [Introspecção](https://requisitos-de-software.github.io/2024.1-Consumidor.gov/Elicitação/introspec/)
- [Análise de Documentos](https://requisitos-de-software.github.io/2024.1-Consumidor.gov/Elicita%C3%A7%C3%A3o/analiseDoc/)

A tabela 1 apresenta os requisitos elicitados a partir destas técnicas, apresentando o **identificador**, **descrição**, e **origem** (a partir de qual técnica foi elicitado), sendo os **Requisitos Funcionais** numerados de ***1 a 22*** e os **Requisitos Não Funcionais** numerados de ***1 a 6***.

**Os identificadores presentes na tabela seguem a legenda abaixo:**

- ***RFx: Requisito Funcional número x***
- ***RNFx: Requisito Não Funcional número x***
- ***ADDx: Requisito número x obtido pela Análise de Documentos***
- ***INTx: Requisito número x obtido pela Introspecção***
- ***QUEx: Requisito número x obtido pelo Questionário***
- ***STx: Requisito número x obtido pelo Storytelling***

| Identificador  |     Descrição    | Origem|
| :-: | :----------------------------------------:|:------------------:|
| RF1 | Deve ser possível fazer login utilizando o gov.br |[INT01](https://requisitos-de-software.github.io/2024.1-Consumidor.gov/Elicitação/introspec/#metodologia);  [ST12](https://requisitos-de-software.github.io/2024.1-Consumidor.gov/Elicitação/Storytelling/)|
| RF2 | Deve ser possível pesquisar uma empresa pelo nome |[INT02, INT03](https://requisitos-de-software.github.io/2024.1-Consumidor.gov/Elicitação/introspec/#metodologia)|
| RF3 | Deve ser possível ver dados sobre uma empresa (CNPJ, contatos, estatísticas, etc.) |[QUE02](https://requisitos-de-software.github.io/2024.1-Consumidor.gov/Elicitação/Questionário/#possiveis-requisitos);  [INT02, INT03, INT04](https://requisitos-de-software.github.io/2024.1-Consumidor.gov/Elicitação/introspec/#metodologia)|
| RF4 | Deve ser exibidos gráficos/indicadores relacionados aos dados sobre uma empresa (Tempo médio de resposta, confiabilidade, etc.) |[QUE02, QUE05](https://requisitos-de-software.github.io/2024.1-Consumidor.gov/Elicitação/Questionário/#possiveis-requisitos);  [INT02, INT03, INT04](https://requisitos-de-software.github.io/2024.1-Consumidor.gov/Elicitação/introspec/#metodologia); [ST04, ST05](https://requisitos-de-software.github.io/2024.1-Consumidor.gov/Elicitação/Storytelling/); [ADD01](https://requisitos-de-software.github.io/2024.1-Consumidor.gov/Elicitação/analiseDoc/)|
| RF5 | Deve ser possível informar as circunstâncias da compra do produto/serviço (internet, loja física, telefone, etc.) |[INT05](https://requisitos-de-software.github.io/2024.1-Consumidor.gov/Elicitação/introspec/#metodologia);[ST01, ST03](https://requisitos-de-software.github.io/2024.1-Consumidor.gov/Elicitação/Storytelling/)|
| RF6 | Deve ser possível escolher qual a categoria da reclamação (atendimento, cobrança, entrega, etc.) |[INT06](https://requisitos-de-software.github.io/2024.1-Consumidor.gov/Elicitação/introspec/#metodologia);[ST01, ST03](https://requisitos-de-software.github.io/2024.1-Consumidor.gov/Elicitação/Storytelling/)|
| RF7 | Deve ser possível fornecer detalhes sobre a reclamação |[INT07](https://requisitos-de-software.github.io/2024.1-Consumidor.gov/Elicitação/introspec/#metodologia);[ST01, ST03](https://requisitos-de-software.github.io/2024.1-Consumidor.gov/Elicitação/Storytelling/)|
| RF8 | Deve ser possível informar o que espera da empresa (reembolso, resposta, justificativa, etc.) |[INT08](https://requisitos-de-software.github.io/2024.1-Consumidor.gov/Elicitação/introspec/#metodologia);[ST01, ST03](https://requisitos-de-software.github.io/2024.1-Consumidor.gov/Elicitação/Storytelling/)|
| RF9 | Deve ser possível anexar arquivos relacionados a reclamação (prints, nota fiscal, ordem de serviço, etc.) |[INT09](https://requisitos-de-software.github.io/2024.1-Consumidor.gov/Elicitação/introspec/#metodologia);[ST01, ST03](https://requisitos-de-software.github.io/2024.1-Consumidor.gov/Elicitação/Storytelling/; [ST07](https://requisitos-de-software.github.io/2024.1-Consumidor.gov/Elicitação/Storytelling/))|
| RF10 | Deve ser possível visualizar as reclamações feitas no app | [QUE04](https://requisitos-de-software.github.io/2024.1-Consumidor.gov/Elicitação/Questionário/#possiveis-requisitos); [INT10](https://requisitos-de-software.github.io/2024.1-Consumidor.gov/Elicitação/introspec/#metodologia); [ADD01](https://requisitos-de-software.github.io/2024.1-Consumidor.gov/Elicitação/analiseDoc/) |
| RF11 | Deve ser possível acompanhar o status de uma reclamação feita | [QUE06, QUE11](https://requisitos-de-software.github.io/2024.1-Consumidor.gov/Elicitação/Questionário/#possiveis-requisitos); [INT10, INT11](https://requisitos-de-software.github.io/2024.1-Consumidor.gov/Elicitação/introspec/#metodologia)|
| RF12 | Deve ser possível receber notificações sobre o status de reclamações | [QUE11](https://requisitos-de-software.github.io/2024.1-Consumidor.gov/Elicitação/Questionário/#possiveis-requisitos); [INT10,INT11](https://requisitos-de-software.github.io/2024.1-Consumidor.gov/Elicitação/introspec/#metodologia) |
| RF13 | Deve ser possível visualizar reclamações feitas por outros usuários |[QUE04](https://requisitos-de-software.github.io/2024.1-Consumidor.gov/Elicitação/Questionário/#possiveis-requisitos); [INT12, INT13](https://requisitos-de-software.github.io/2024.1-Consumidor.gov/Elicitação/introspec/#metodologia); [ST05](https://requisitos-de-software.github.io/2024.1-Consumidor.gov/Elicitação/Storytelling/); [ADD01](https://requisitos-de-software.github.io/2024.1-Consumidor.gov/Elicitação/analiseDoc/)|
| RF14 | Deve ser possível visulizar detalhes de uma reclamação de outro usuário (status, avaliação, tempo de resposta, etc.) | [QUE04](https://requisitos-de-software.github.io/2024.1-Consumidor.gov/Elicitação/Questionário/#possiveis-requisitos); [INT12,INT13](https://requisitos-de-software.github.io/2024.1-Consumidor.gov/Elicitação/introspec/#metodologia); [ST05](https://requisitos-de-software.github.io/2024.1-Consumidor.gov/Elicitação/Storytelling/); [ADD01](https://requisitos-de-software.github.io/2024.1-Consumidor.gov/Elicitação/analiseDoc/)|
| RF15 | Deve ser possível avaliar uma reclamação (nível de satisfação/nota) | [QUE11](https://requisitos-de-software.github.io/2024.1-Consumidor.gov/Elicitação/Questionário/#possiveis-requisitos); [INT15](https://requisitos-de-software.github.io/2024.1-Consumidor.gov/Elicitação/introspec/#metodologia) |
| RF16 | Deve ser possível cadastrar os dados de uma empresa | [QUE11](https://requisitos-de-software.github.io/2024.1-Consumidor.gov/Elicitação/Questionário/#possiveis-requisitos); [INT15](https://requisitos-de-software.github.io/2024.1-Consumidor.gov/Elicitação/introspec/#metodologia) |
| RF17 | Deve ser possível fazer upload da logomarca para o cadastro de uma empresa | [QUE11](https://requisitos-de-software.github.io/2024.1-Consumidor.gov/Elicitação/Questionário/#possiveis-requisitos); [INT15](https://requisitos-de-software.github.io/2024.1-Consumidor.gov/Elicitação/introspec/#metodologia) |
| RF18 | Deve ser possível anexar documentos para o cadastro de uma empresa | [QUE11](https://requisitos-de-software.github.io/2024.1-Consumidor.gov/Elicitação/Questionário/#possiveis-requisitos); [INT15](https://requisitos-de-software.github.io/2024.1-Consumidor.gov/Elicitação/introspec/#metodologia) |
| RF19 | Deve ser possível visualizar as reclamações feitas sobre uma empresa | [QUE11](https://requisitos-de-software.github.io/2024.1-Consumidor.gov/Elicitação/Questionário/#possiveis-requisitos); [INT15](https://requisitos-de-software.github.io/2024.1-Consumidor.gov/Elicitação/introspec/#metodologia); [ST04](https://requisitos-de-software.github.io/2024.1-Consumidor.gov/Elicitação/Storytelling/) |
| RF20 | Deve ser possível visualizar como o cliente fez a compra | [QUE11](https://requisitos-de-software.github.io/2024.1-Consumidor.gov/Elicitação/Questionário/#possiveis-requisitos); [INT15](https://requisitos-de-software.github.io/2024.1-Consumidor.gov/Elicitação/introspec/#metodologia) |
| RF21 | Deve ser possível visualizar qual tipo de reclamação o cliente apresentou | [QUE11](https://requisitos-de-software.github.io/2024.1-Consumidor.gov/Elicitação/Questionário/#possiveis-requisitos); [INT15](https://requisitos-de-software.github.io/2024.1-Consumidor.gov/Elicitação/introspec/#metodologia) |
| RF22 | Deve ser possível visualizar os detalhes e anexos de uma reclamação sobre uma empresa | [QUE11](https://requisitos-de-software.github.io/2024.1-Consumidor.gov/Elicitação/Questionário/#possiveis-requisitos); [INT15](https://requisitos-de-software.github.io/2024.1-Consumidor.gov/Elicitação/introspec/#metodologia) |
| RF23 | Deve ser possível responder uma reclamação feita | [QUE11](https://requisitos-de-software.github.io/2024.1-Consumidor.gov/Elicitação/Questionário/#possiveis-requisitos); [INT15](https://requisitos-de-software.github.io/2024.1-Consumidor.gov/Elicitação/introspec/#metodologia) |
| RF24 | Deve ser possível visualizar estatísticas das reclamações sobre uma empresa | [QUE05](https://requisitos-de-software.github.io/2024.1-Consumidor.gov/Elicitação/Questionário/#possiveis-requisitos); [INT15](https://requisitos-de-software.github.io/2024.1-Consumidor.gov/Elicitação/introspec/#metodologia) |
| RF25 | Deve ser possível visualizar avaliação das reclamações | [QUE05](https://requisitos-de-software.github.io/2024.1-Consumidor.gov/Elicitação/Questionário/#possiveis-requisitos); [INT15](https://requisitos-de-software.github.io/2024.1-Consumidor.gov/Elicitação/introspec/#metodologia) |
| RNF1 | O aplicativo deve funcionar tanto em dispositivos Android quanto iOS |[INT10](https://requisitos-de-software.github.io/2024.1-Consumidor.gov/Elicitação/introspec/#metodologia); [ADD04, ADD15](https://requisitos-de-software.github.io/2024.1-Consumidor.gov/Elicitação/analiseDoc/)|
| RNF2 | Novos usuários devem ser capazes de realizar as tarefas básicas (ex.:acessar conta, fazer reclamação) em menos de 5 minutos |[QUE01](https://requisitos-de-software.github.io/2024.1-Consumidor.gov/Elicitação/Questionário/#possiveis-requisitos) ; [INT11](https://requisitos-de-software.github.io/2024.1-Consumidor.gov/Elicitação/introspec/#metodologia); [ST11](https://requisitos-de-software.github.io/2024.1-Consumidor.gov/Elicitação/Storytelling/); [ADD05, ADD12](https://requisitos-de-software.github.io/2024.1-Consumidor.gov/Elicitação/analiseDoc/)|
| RNF3 | O aplicativo deve fornecer opções de acessibilidade (ex.:modo escuro, esquemas de cores, conteúdos em libras) |[QUE03](https://requisitos-de-software.github.io/2024.1-Consumidor.gov/Elicitação/Questionário/#possiveis-requisitos); [INT12](https://requisitos-de-software.github.io/2024.1-Consumidor.gov/Elicitação/introspec/#metodologia); [ST08](https://requisitos-de-software.github.io/2024.1-Consumidor.gov/Elicitação/Storytelling/); [ADD06, ADD07](https://requisitos-de-software.github.io/2024.1-Consumidor.gov/Elicitação/analiseDoc/)|
| RNF4 | O aplicativo deve fornecer feedback ao usuário em caso de erros/falhas |[QUE03](https://requisitos-de-software.github.io/2024.1-Consumidor.gov/Elicitação/Questionário/#possiveis-requisitos);  [QUE08, QUE09](https://requisitos-de-software.github.io/2024.1-Consumidor.gov/Elicitação/introspec/#metodologia); [ST09](https://requisitos-de-software.github.io/2024.1-Consumidor.gov/Elicitação/Storytelling/)|
| RNF5 | Todos os dados sensíveis transmitidos entre o cliente e o servidor devem ser criptografados |[INT13](https://requisitos-de-software.github.io/2024.1-Consumidor.gov/Elicitação/introspec/#metodologia); [ADD09, ADD11, ADD13](https://requisitos-de-software.github.io/2024.1-Consumidor.gov/Elicitação/analiseDoc/)|
| RNF6 | O aplicativo deve validar todas as entradas do usuário para proteger de possíveis ataques |[INT13](https://requisitos-de-software.github.io/2024.1-Consumidor.gov/Elicitação/introspec/#metodologia); [ADD09, ADD11, ADD13](https://requisitos-de-software.github.io/2024.1-Consumidor.gov/Elicitação/analiseDoc/)|
| RNF7 | O aplicativo deve fornecer feedback em menos de 1 segundo após cada ação do usuário |[INT13](https://requisitos-de-software.github.io/2024.1-Consumidor.gov/Elicitação/introspec/#metodologia); [ST06](https://requisitos-de-software.github.io/2024.1-Consumidor.gov/Elicitação/Storytelling/); [ADD02](https://requisitos-de-software.github.io/2024.1-Consumidor.gov/Elicitação/analiseDoc/)|
| RNF8 | As ações principais do site (ex.:fazer reclamação, ver reclamação) devem ser executadas em no máximo 4 passos |[QUE01](https://requisitos-de-software.github.io/2024.1-Consumidor.gov/Elicitação/Questionário/#possiveis-requisitos) ; [INT11](https://requisitos-de-software.github.io/2024.1-Consumidor.gov/Elicitação/introspec/#metodologia); [ST11](https://requisitos-de-software.github.io/2024.1-Consumidor.gov/Elicitação/Storytelling/); [ADD05, ADD12](https://requisitos-de-software.github.io/2024.1-Consumidor.gov/Elicitação/analiseDoc/)|
| RNF9 | Senhas dos usuários devem ser armazenadas utilizando técnicas de hashing seguras |[INT13](https://requisitos-de-software.github.io/2024.1-Consumidor.gov/Elicitação/introspec/#metodologia); [ADD09, ADD11, ADD13](https://requisitos-de-software.github.io/2024.1-Consumidor.gov/Elicitação/analiseDoc/)|


<div align="center">
<figcaption align="left">Tabela 1: Requisitos identificados através da introspecção(Autor: GALDINO, Henrique 2024)</figcaption>
</div>
<br/>

## Bibliografia

[1] PAGANINI, Diogo. Técnicas para Elicitação de Requisitos, 2019. Disponível em: <https://pt.linkedin.com/pulse/técnicas-para-elicitação-de-requisitos-diogo-paganini>

[2] PUC-Rio. Elicitação de Requisitos, acesso em 12 de abril de 2024. Disponível em: <https://www.maxwell.vrac.puc-rio.br/15760/15760_3.PDF>


## Histórico de Versão
| Versão | Data de execução | Data de revisão |  Descrição            | Autor(es)         | Revisor(es)  |
| :------: | :----------: | :--------: | :--------------------: | :-------------: | :----------: |
| `1.3` | 23/05/2024  | 23/05/2024 | Adição e correção conforme feedback | [Matheus Ferreira](https://github.com/matferreira1) | [Guilherme Meister](https://github.com/gmeister18) |
| `1.2` | 21/04/2024  | 22/04/2024 | Adição novos requisitos | [Rodrigo Gontijo](https://github.com/rodrigogontijoo) | [Guilherme Meister](https://github.com/gmeister18) |
| `1.1` | 16/04/2024  | 16/04/2024 | Correções de formatação da revisão | [Rodrigo Gontijo](https://github.com/rodrigogontijoo) | [Guilherme Meister](https://github.com/gmeister18) |
| `1.0` | 10/04/2024  | 10/04/2024 | Criação do artefato de introspecção | [Henrique Galdino](https://github.com/hgaldino05) | [Igor Thiago](https://github.com/alladin-51) |
<div align="center">
<figcaption align="left">Tabela 2: Histórico de versões(Autor: GALDINO, Henrique 2024)</figcaption>
</div>
<br/>
