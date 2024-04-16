# Requisitos Elicitados

## Introdução

A elicitação de requisitos é uma etapa fundamental no desenvolvimento de software, pois é a partir dos requisitos que o sistema será projetado e implementado. Para a elicitação dos requisitos relacionados ao **Consumidor.gov**, foram utilizadas as seguintes técnicas:

- [Questionário](https://requisitos-de-software.github.io/2024.1-Consumidor.gov/Elicitação/Questionário/)
- [Introspecção](https://requisitos-de-software.github.io/2024.1-Consumidor.gov/Elicitação/introspec/)
- [Brainstorming](https://requisitos-de-software.github.io/2024.1-Consumidor.gov/Elicitação/brainstorming/)

A tabela 1 apresenta os requisitos elicitados a partir destas técnicas, apresentando o **identificador**, **descrição**, **tipo** (funcional ou não funcional), **origem** (a partir de qual técnica foi elicitado).

| Identificador  |     Descrição    | Tipo  | Origem|
| :-: | :----------------------------------------: | :--------------------: |:------------------:|
| REQ01 | Deve ser possível fazer login utilizando o gov.br | Requisito Funcional |[INT01](https://requisitos-de-software.github.io/2024.1-Consumidor.gov/Elicitação/introspec/#metodologia)|
| REQ02 | Deve ser possível pesquisar uma empresa pelo nome | Requisito Funcional |[INT02](https://requisitos-de-software.github.io/2024.1-Consumidor.gov/Elicitação/introspec/#metodologia)|
| REQ03 | Deve ser possível ver dados sobre uma empresa (Tempo médio de resposta, confiabilidade, etc.) | Requisito Funcional |[QUE02, QUE05, QUE11](https://requisitos-de-software.github.io/2024.1-Consumidor.gov/Elicitação/Questionário/#possiveis-requisitos);  [INT02](https://requisitos-de-software.github.io/2024.1-Consumidor.gov/Elicitação/introspec/#metodologia)|
| REQ04 | Deve ser exibidos gráficos/indicadores relacionados aos dados sobre uma empresa (Tempo médio de resposta, confiabilidade, etc.) | Requisito Funcional |[QUE02, QUE05, QUE11](https://requisitos-de-software.github.io/2024.1-Consumidor.gov/Elicitação/Questionário/#possiveis-requisitos);  [INT02](https://requisitos-de-software.github.io/2024.1-Consumidor.gov/Elicitação/introspec/#metodologia)|
| REQ05 | Deve ser possível informar como/onde foi feita a compra (internet, loja física, telefone, etc.) | Requisito Funcional |[INT03](https://requisitos-de-software.github.io/2024.1-Consumidor.gov/Elicitação/introspec/#metodologia)|
| REQ06 | Deve ser possível escolher qual a categoria da reclamação (atendimento, cobrança, entrega, etc.) | Requisito Funcional |[INT04](https://requisitos-de-software.github.io/2024.1-Consumidor.gov/Elicitação/introspec/#metodologia)|
| REQ07 | Deve ser possível escolher qual a categoria da reclamação (atendimento, SAC, etc.) | Requisito Funcional |[INT05](https://requisitos-de-software.github.io/2024.1-Consumidor.gov/Elicitação/introspec/#metodologia)|
| REQ08 | Deve ser possível fornecer detalhes sobre a reclamação | Requisito Funcional |[INT06](https://requisitos-de-software.github.io/2024.1-Consumidor.gov/Elicitação/introspec/#metodologia)|
| REQ09 | Deve ser possível informar o que espera da empresa (reembolso, resposta, justificativa, etc.) | Requisito Funcional |[INT07](https://requisitos-de-software.github.io/2024.1-Consumidor.gov/Elicitação/introspec/#metodologia)|
| REQ10 | Deve ser possível anexar arquivos relacionados a reclamação (prints, nota fiscal, ordem de serviço, etc.) | Requisito Funcional |[INT08](https://requisitos-de-software.github.io/2024.1-Consumidor.gov/Elicitação/introspec/#metodologia)|
| REQ11 | Deve ser possível visualizar as reclamações feitas | Requisito Funcional | [QUE04](https://requisitos-de-software.github.io/2024.1-Consumidor.gov/Elicitação/Questionário/#possiveis-requisitos); [INT09](https://requisitos-de-software.github.io/2024.1-Consumidor.gov/Elicitação/introspec/#metodologia) |
| REQ12 | Deve ser possível acompanhar o status de uma reclamação feita | Requisito Funcional |[QUE18](https://requisitos-de-software.github.io/2024.1-Consumidor.gov/Elicitação/Questionário/#possiveis-requisitos);  [INT10](https://requisitos-de-software.github.io/2024.1-Consumidor.gov/Elicitação/introspec/#metodologia)|
| REQ13 | O aplicativo deve funcionar tanto em dispositivos Android quanto iOS | Requisito Não Funcional |[INT11](https://requisitos-de-software.github.io/2024.1-Consumidor.gov/Elicitação/introspec/#metodologia)|
| REQ14 | O aplicativo deve apresentar uma interface simples e intuitiva | Requisito Não Funcional |[QUE15, QUE19](https://requisitos-de-software.github.io/2024.1-Consumidor.gov/Elicitação/Questionário/#possiveis-requisitos) ; [INT12](https://requisitos-de-software.github.io/2024.1-Consumidor.gov/Elicitação/introspec/#metodologia)|
| REQ15 | O aplicativo deve fornecer opções de acessibilidade (modo escuro, esquemas de cores, conteúdos em libras, etc.) | Requisito Não Funcional |[QUE03](https://requisitos-de-software.github.io/2024.1-Consumidor.gov/Elicitação/Questionário/#possiveis-requisitos); [INT13](https://requisitos-de-software.github.io/2024.1-Consumidor.gov/Elicitação/introspec/#metodologia)|
| REQ16 | O aplicativo deve fornecer feedback ao usuário em caso de erros/falhas | Requisito Não Funcional |[INT14](https://requisitos-de-software.github.io/2024.1-Consumidor.gov/Elicitação/introspec/#metodologia)|

<div align="center">
<figcaption align="left">Tabela 1: Requisitos identificados através da introspecção(Fonte: Henrique Galdino, 2024)</figcaption>
</div>
<br/>

## Bibliografia

[1] PAGANINI, Diogo. Técnicas para Elicitação de Requisitos, 2019. Disponível em: <https://pt.linkedin.com/pulse/técnicas-para-elicitação-de-requisitos-diogo-paganini>

[2] PUC-Rio. Elicitação de Requisitos, acesso em 12 de abril de 2024. Disponível em: <https://www.maxwell.vrac.puc-rio.br/15760/15760_3.PDF>


## Histórico de Versão
| Versão | Data de execução | Data de revisão |  Descrição            | Autor(es)         | Revisor(es)  |
| :------: | :----------: | :--------: | :--------------------: | :-------------: | :----------: |
| `1.1` | 16/04/2024  | 16/04/2024 | Correções de formatação da revisão | [Rodrigo Gontijo](https://github.com/rodrigogontijoo) | [Guilherme Meister](https://github.com/gmeister18) |
| `1.0` | 10/04/2024  | 10/04/2024 | Criação do artefato de introspecção | [Henrique Galdino](https://github.com/hgaldino05) | [Igor Thiago](https://github.com/alladin-51) |
<div align="center">
<figcaption align="left">Tabela 2: Histórico de versões(Fonte: Henrique Galdino, 2024)</figcaption>
</div>
<br/>