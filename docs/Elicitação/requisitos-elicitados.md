# Requisitos Elicitados

## Introdução

A elicitação de requisitos é uma etapa fundamental no desenvolvimento de software, pois é a partir dos requisitos que o sistema será projetado e implementado. Para a elicitação dos requisitos relacionados ao **Consumidor.gov**, foram utilizadas as seguintes técnicas:

- [Questionário](https://requisitos-de-software.github.io/2024.1-Consumidor.gov/Elicitação/Questionário/)
- [Introspecção](https://requisitos-de-software.github.io/2024.1-Consumidor.gov/Elicitação/introspec/)
- [Análise de Documentos](https://requisitos-de-software.github.io/2024.1-Consumidor.gov/Elicita%C3%A7%C3%A3o/analiseDoc/)

A tabela 1 apresenta os requisitos elicitados a partir destas técnicas, apresentando o **identificador**, **descrição**, **tipo** (funcional ou não funcional), **origem** (a partir de qual técnica foi elicitado).

| Identificador  |     Descrição    | Tipo  | Origem|
| :-: | :----------------------------------------: | :--------------------: |:------------------:|
| REQ01 | Deve ser possível fazer login utilizando o gov.br | Requisito Funcional |[INT01](https://requisitos-de-software.github.io/2024.1-Consumidor.gov/Elicitação/introspec/#metodologia)|
| REQ02 | Deve ser possível pesquisar uma empresa pelo nome | Requisito Funcional |[INT02, INT03](https://requisitos-de-software.github.io/2024.1-Consumidor.gov/Elicitação/introspec/#metodologia)|
| REQ03 | Deve ser possível ver dados sobre uma empresa (CNPJ, contatos, estatísticas, etc.) | Requisito Funcional |[QUE02, QUE05](https://requisitos-de-software.github.io/2024.1-Consumidor.gov/Elicitação/Questionário/#possiveis-requisitos);  [INT02, INT03, INT04](https://requisitos-de-software.github.io/2024.1-Consumidor.gov/Elicitação/introspec/#metodologia)|
| REQ04 | Deve ser exibidos gráficos/indicadores relacionados aos dados sobre uma empresa (Tempo médio de resposta, confiabilidade, etc.) | Requisito Funcional |[QUE02, QUE05](https://requisitos-de-software.github.io/2024.1-Consumidor.gov/Elicitação/Questionário/#possiveis-requisitos);  [INT02, INT03, INT04](https://requisitos-de-software.github.io/2024.1-Consumidor.gov/Elicitação/introspec/#metodologia)|
| REQ05 | Deve ser possível informar as circunstâncias da compra do produto/serviço (internet, loja física, telefone, etc.) | Requisito Funcional |[INT05](https://requisitos-de-software.github.io/2024.1-Consumidor.gov/Elicitação/introspec/#metodologia)|
| REQ06 | Deve ser possível escolher qual a categoria da reclamação (atendimento, cobrança, entrega, etc.) | Requisito Funcional |[INT06](https://requisitos-de-software.github.io/2024.1-Consumidor.gov/Elicitação/introspec/#metodologia)|
| REQ07 | Deve ser possível fornecer detalhes sobre a reclamação | Requisito Funcional |[INT07](https://requisitos-de-software.github.io/2024.1-Consumidor.gov/Elicitação/introspec/#metodologia)|
| REQ08 | Deve ser possível informar o que espera da empresa (reembolso, resposta, justificativa, etc.) | Requisito Funcional |[INT08](https://requisitos-de-software.github.io/2024.1-Consumidor.gov/Elicitação/introspec/#metodologia)|
| REQ09 | Deve ser possível anexar arquivos relacionados a reclamação (prints, nota fiscal, ordem de serviço, etc.) | Requisito Funcional |[INT09](https://requisitos-de-software.github.io/2024.1-Consumidor.gov/Elicitação/introspec/#metodologia)|
| REQ10 | Deve ser possível visualizar as reclamações feitas no app | Requisito Funcional | [QUE04](https://requisitos-de-software.github.io/2024.1-Consumidor.gov/Elicitação/Questionário/#possiveis-requisitos); [INT10](https://requisitos-de-software.github.io/2024.1-Consumidor.gov/Elicitação/introspec/#metodologia) |
| REQ11 | Deve ser possível acompanhar o status de uma reclamação feita | Requisito Funcional | [INT10, INT11](https://requisitos-de-software.github.io/2024.1-Consumidor.gov/Elicitação/introspec/#metodologia)|
| REQ12 | Deve ser possível receber notificações sobre o status de reclamações | Requisito Funcional | [QUE11](https://requisitos-de-software.github.io/2024.1-Consumidor.gov/Elicitação/Questionário/#possiveis-requisitos); [INT10,INT11](https://requisitos-de-software.github.io/2024.1-Consumidor.gov/Elicitação/introspec/#metodologia) |
| REQ13 | Deve ser possível visualizar reclamações feitas por outros usuários | Requisito Funcional | [INT12, INT13](https://requisitos-de-software.github.io/2024.1-Consumidor.gov/Elicitação/introspec/#metodologia)|
| REQ14 | Deve ser possível visulizar detalhes de uma reclamação de outro usuário (status, avaliação, tempo de resposta, etc.) | Requisito Funcional | [QUE11](https://requisitos-de-software.github.io/2024.1-Consumidor.gov/Elicitação/Questionário/#possiveis-requisitos); [INT12,INT13](https://requisitos-de-software.github.io/2024.1-Consumidor.gov/Elicitação/introspec/#metodologia) |
| REQ15 | Deve ser possível avaliar uma reclamação (nível de satisfação/nota) | Requisito Funcional | [QUE11](https://requisitos-de-software.github.io/2024.1-Consumidor.gov/Elicitação/Questionário/#possiveis-requisitos); [INT15](https://requisitos-de-software.github.io/2024.1-Consumidor.gov/Elicitação/introspec/#metodologia) |
| REQ16 | Deve ser possível cadastrar os dados de uma empresa | Requisito Funcional | [QUE11](https://requisitos-de-software.github.io/2024.1-Consumidor.gov/Elicitação/Questionário/#possiveis-requisitos); [INT15](https://requisitos-de-software.github.io/2024.1-Consumidor.gov/Elicitação/introspec/#metodologia) |
| REQ17 | Deve ser possível fazer upload da logomarca para o cadastro de uma empresa | Requisito Funcional | [QUE11](https://requisitos-de-software.github.io/2024.1-Consumidor.gov/Elicitação/Questionário/#possiveis-requisitos); [INT15](https://requisitos-de-software.github.io/2024.1-Consumidor.gov/Elicitação/introspec/#metodologia) |
| REQ18 | Deve ser possível anexar documentos para o cadastro de uma empresa | Requisito Funcional | [QUE11](https://requisitos-de-software.github.io/2024.1-Consumidor.gov/Elicitação/Questionário/#possiveis-requisitos); [INT15](https://requisitos-de-software.github.io/2024.1-Consumidor.gov/Elicitação/introspec/#metodologia) |
| REQ19 | Deve ser possível visualizar as reclamações feitas sobre uma empresa | Requisito Funcional | [QUE11](https://requisitos-de-software.github.io/2024.1-Consumidor.gov/Elicitação/Questionário/#possiveis-requisitos); [INT15](https://requisitos-de-software.github.io/2024.1-Consumidor.gov/Elicitação/introspec/#metodologia) |
| REQ20 | Deve ser possível visualizar como o cliente fez a compra | Requisito Funcional | [QUE11](https://requisitos-de-software.github.io/2024.1-Consumidor.gov/Elicitação/Questionário/#possiveis-requisitos); [INT15](https://requisitos-de-software.github.io/2024.1-Consumidor.gov/Elicitação/introspec/#metodologia) |
| REQ21 | Deve ser possível visualizar qual tipo de reclamação o cliente apresentou | Requisito Funcional | [QUE11](https://requisitos-de-software.github.io/2024.1-Consumidor.gov/Elicitação/Questionário/#possiveis-requisitos); [INT15](https://requisitos-de-software.github.io/2024.1-Consumidor.gov/Elicitação/introspec/#metodologia) |
| REQ22 | Deve ser possível visualizar os detalhes e anexos de uma reclamação sobre uma empresa | Requisito Funcional | [QUE11](https://requisitos-de-software.github.io/2024.1-Consumidor.gov/Elicitação/Questionário/#possiveis-requisitos); [INT15](https://requisitos-de-software.github.io/2024.1-Consumidor.gov/Elicitação/introspec/#metodologia) |
| REQ23 | Deve ser possível responder uma reclamação feita | Requisito Funcional | [QUE11](https://requisitos-de-software.github.io/2024.1-Consumidor.gov/Elicitação/Questionário/#possiveis-requisitos); [INT15](https://requisitos-de-software.github.io/2024.1-Consumidor.gov/Elicitação/introspec/#metodologia) |
| REQ24 | Deve ser possível visualizar estatísticas das reclamações sobre uma empresa | Requisito Funcional | [QUE11](https://requisitos-de-software.github.io/2024.1-Consumidor.gov/Elicitação/Questionário/#possiveis-requisitos); [INT15](https://requisitos-de-software.github.io/2024.1-Consumidor.gov/Elicitação/introspec/#metodologia) |
| REQ25 | Deve ser possível visualizar avaliação das reclamações | Requisito Funcional | [QUE11](https://requisitos-de-software.github.io/2024.1-Consumidor.gov/Elicitação/Questionário/#possiveis-requisitos); [INT15](https://requisitos-de-software.github.io/2024.1-Consumidor.gov/Elicitação/introspec/#metodologia) |
| REQ26 | O aplicativo deve funcionar tanto em dispositivos Android quanto iOS | Requisito Não Funcional |[INT10](https://requisitos-de-software.github.io/2024.1-Consumidor.gov/Elicitação/introspec/#metodologia)|
| REQ27 | O aplicativo deve apresentar uma interface simples e intuitiva | Requisito Não Funcional |[QUE15, QUE19](https://requisitos-de-software.github.io/2024.1-Consumidor.gov/Elicitação/Questionário/#possiveis-requisitos) ; [INT11](https://requisitos-de-software.github.io/2024.1-Consumidor.gov/Elicitação/introspec/#metodologia)|
| REQ28 | O aplicativo deve fornecer opções de acessibilidade (modo escuro, esquemas de cores, conteúdos em libras, etc.) | Requisito Não Funcional |[QUE03](https://requisitos-de-software.github.io/2024.1-Consumidor.gov/Elicitação/Questionário/#possiveis-requisitos); [INT12](https://requisitos-de-software.github.io/2024.1-Consumidor.gov/Elicitação/introspec/#metodologia)|
| REQ29 | O aplicativo deve fornecer feedback ao usuário em caso de erros/falhas | Requisito Não Funcional |[INT13](https://requisitos-de-software.github.io/2024.1-Consumidor.gov/Elicitação/introspec/#metodologia)|
| REQ30 | O aplicativo deve apresentar medidas de proteção | Requisito Não Funcional |[INT13](https://requisitos-de-software.github.io/2024.1-Consumidor.gov/Elicitação/introspec/#metodologia)|
| REQ31 | O aplicativo deve proteger os dados sensíveis do usuário | Requisito Não Funcional |[INT13](https://requisitos-de-software.github.io/2024.1-Consumidor.gov/Elicitação/introspec/#metodologia)|
| REQ32 | O aplicativo deve otimizar o carregamento de páginas/recursos | Requisito Não Funcional |[INT13](https://requisitos-de-software.github.io/2024.1-Consumidor.gov/Elicitação/introspec/#metodologia)|


<div align="center">
<figcaption align="left">Tabela 1: Requisitos identificados através da introspecção(Fonte: GALDINO, Henrique 2024)</figcaption>
</div>
<br/>

## Bibliografia

[1] PAGANINI, Diogo. Técnicas para Elicitação de Requisitos, 2019. Disponível em: <https://pt.linkedin.com/pulse/técnicas-para-elicitação-de-requisitos-diogo-paganini>

[2] PUC-Rio. Elicitação de Requisitos, acesso em 12 de abril de 2024. Disponível em: <https://www.maxwell.vrac.puc-rio.br/15760/15760_3.PDF>


## Histórico de Versão
| Versão | Data de execução | Data de revisão |  Descrição            | Autor(es)         | Revisor(es)  |
| :------: | :----------: | :--------: | :--------------------: | :-------------: | :----------: |
| `1.2` | 21/04/2024  | 22/04/2024 | Adição novos requisitos | [Rodrigo Gontijo](https://github.com/rodrigogontijoo) | [Guilherme Meister](https://github.com/gmeister18) |
| `1.1` | 16/04/2024  | 16/04/2024 | Correções de formatação da revisão | [Rodrigo Gontijo](https://github.com/rodrigogontijoo) | [Guilherme Meister](https://github.com/gmeister18) |
| `1.0` | 10/04/2024  | 10/04/2024 | Criação do artefato de introspecção | [Henrique Galdino](https://github.com/hgaldino05) | [Igor Thiago](https://github.com/alladin-51) |
<div align="center">
<figcaption align="left">Tabela 2: Histórico de versões(Fonte: GALDINO, Henrique 2024)</figcaption>
</div>
<br/>
