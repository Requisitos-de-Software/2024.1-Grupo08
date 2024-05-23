# Introspecção

## Introdução

A introspecção é uma técnica que consiste em analisar e identificar, a partir do ponto de vista do usuário, quais características e funcionalidades um sistema deve apresentar. Esta técnica é muito usada para constatar inicialmente quais requisitos podem ser associados ao sistema, e serve como base para a elicitação dos mesmos.

## Metodologia

Após conversas entre os membros da equipe, foram relatadas diversas situações nas quais os mesmos poderiam ter feito uso da plataforma Consumidor.gov, e como as funcionalidades do app poderiam ter ajudado a contornar os problemas enfrentados. Para o uso da técnica de  introspecção, foi imaginado um possível contexto no qual um usuário poderia fazer uso do aplicativo Consumidor.gov, e a partir disso, foram identificados os requisitos que seriam necessários para que este pudesse tentar resolver o problema enfrentado, sendo que o membro Henrique Galdino ficou responsável por esta tarefa.


## **Ponto de vista - Consumidor**
O contexto imaginado foi o seguinte:

- Henrique comprou um produto pela internet e o mesmo não foi entregue no prazo estipulado, e tentou entrar em contato com a empresa responsável, mas não obteve nenhum tipo de resposta nos meios informados na seção de Atendimento ao cliente. Henrique então decidiu utilizar o aplicativo ***Consumidor.gov*** para tentar resolver o problema. 
- Dentro do app, pode encontrar a empresa e registrar uma reclamação, adicionando os detalhes do ocorrido e anexando prints das tentativas de contato com a empresa. Após a reclamação ser registrada, a empresa foi notificada e entrou em contato com Henrique, dando início a tentativa de resolução do problema.

A partir deste contexto, Henrique identificou alguns requisitos, que podem ser vistos na **tabela 1**, identificados com o código ***INT*** e numerados de **1** até **13**, contendo **descrição** e **tipo** (funcional ou não-funcional) do requisito.

### Requisitos identificados
| Identificador  |     Descrição    | Tipo  |
| :-: | :----------------------------------------: | :---: |
| INT01 | Deve ser possível fazer login utilizando o gov.br | Requisito Funcional |
| INT02 | Deve ser possível pesquisar uma empresa pelo nome | Requisito Funcional |
| INT03 | Deve ser possível visualizar o "perfil" uma empresa | Requisito Funcional |
| INT04 | Deve ser possível visualizar contatos da empresa no perfil (email, telefone, redes sociais) | Requisito Funcional |
| INT05 | Deve ser possível informar como/onde foi feita a compra (internet, loja física, telefone, etc.) | Requisito Funcional |
| INT06 | Deve ser possível escolher qual a categoria da reclamação (atendimento, cobrança, entrega, etc.) | Requisito Funcional |
| INT07 | Deve ser possível fornecer detalhes sobre a reclamação | Requisito Funcional |
| INT08 | Deve ser possível informar o que espera da empresa (reembolso, resposta, justificativa, etc.) | Requisito Funcional |
| INT09 | Deve ser possível anexar arquivos relacionados a reclamação (prints, nota fiscal, ordem de serviço, etc.) | Requisito Funcional |
| INT10 | Deve ser possível visualizar as reclamações feitas | Requisito Funcional |
| INT11 | Deve ser possível acompanhar o status de uma reclamação feita | Requisito Funcional |
| INT12 | Deve ser possível notificar atualizações sobre o status de uma reclamação feita | Requisito Funcional |
| INT13 | Deve ser possível visualizar as reclamações feitas por outros usuários | Requisito Funcional |
| INT14 | Deve ser possível visualizar os detalhes de uma reclamação feita por outro usuário (status, avaliação, tempo de resposta, etc.) | Requisito Funcional |
| INT15 | Deve ser possível avaliar uma reclamação (nível de satisfação/nota) | Requisito Funcional |
| INT16 | Deve ser possível comparar as estatísticas de empresas diferentes | Requisito Funcional |
| INT17 | O aplicativo deve funcionar tanto em dispositivos Android quanto iOS sem utilizar muito espaço de armazenamento | Requisito Não Funcional |
| INT18 | O aplicativo deve apresentar uma interface simples e intuitiva | Requisito Não Funcional |
| INT19 | O aplicativo deve fornecer opções de acessibilidade (modo escuro, esquemas de cores, conteúdos em libras, etc.) | Requisito Não Funcional |
| INT20 | O aplicativo deve fornecer feedback ao usuário em caso de erros/falhas | Requisito Não Funcional |
| INT21 | O aplicativo deve apresentar medidas de proteção | Requisito Não Funcional |
| INT22 | O aplicativo deve proteger os dados sensíveis do usuário | Requisito Não Funcional |

<div align="center">
<figcaption align="left">Tabela 1: Requisitos identificados através da introspecção do ponto de vista do consumidor (Autor: GALDINO, Henrique 2024)</figcaption>
</div>
<br/>

## **Ponto de vista - Empresa**
O contexto imaginado foi o seguinte:

- Rodrigo é dono de uma rede de restaurantes com uma grande quantidade de clientes. Recentemente, ele percebeu que muitos clientes estão reclamando sobre a demora no atendimento das unidades presenciais e na entrega de produtos via delivery. Procurando entender melhor o problema e buscar soluções para o mesmo, Rodrigo decidiu utilizar o aplicativo ***Consumidor.gov*** para facilitar o contato com a clientela e garantir que suas reclamações sejam ouvidas pela empresa.
- Dentro do ***Consumidor.gov***, Rodrigo pode encontrar todas reclamações feitas contra a sua empresa, podendo visualizar melhor os detalhes dos problemas enfrentados pelos consumidores e o que eles esperam como possível solução. Além disso, ele pode responder as reclamações, prestando suporte para os incidentes relatados e buscando melhorar a prestação dos serviços ofertados pela empresa. Com isso, Rodrigo consegue melhorar o atendimento da empresa e garantir a satisfação de seus fiéis clientes.

A partir deste contexto, Rodrigo identificou alguns requisitos, que podem ser vistos na **tabela 2**, identificados com o código ***INT*** e numerados de **23** até **39**, contendo **descrição** e **tipo** (funcional ou não-funcional) do requisito.

### Requisitos identificados
| Identificador  |     Descrição    | Tipo  |
| :-: | :----------------------------------------: | :---: |
| INT23 | Deve ser possível fazer login utilizando o gov.br | Requisito Funcional |
| INT24 | Deve ser possível cadastrar os dados da empresa | Requisito Funcional |
| INT25 | Deve ser possível fazer upload da logomarca da empresa | Requisito Funcional |
| INT26 | Deve ser possível anexar documentos no cadastro | Requisito Funcional |
| INT27 | Deve ser possível visualizar as reclamações feitas | Requisito Funcional |
| INT28 | Deve ser possível visualizar como o cliente fez a compra | Requisito Funcional |
| INT29 | Deve ser possível visualizar qual tipo de problema o cliente teve | Requisito Funcional |
| INT30 | Deve ser possível visualizar os detalhes e anexos de uma reclamação | Requisito Funcional |
| INT31 | Deve ser possível responder uma reclamação feita | Requisito Funcional |
| INT32 | Deve ser possível visualizar estatísticas das reclamações | Requisito Funcional |
| INT33 | Deve ser possível visualizar avaliação das reclamações | Requisito Funcional |
| INT34 | O aplicativo deve funcionar tanto em dispositivos Android quanto iOS | Requisito Não Funcional |
| INT35 | O aplicativo deve apresentar uma interface simples e intuitiva | Requisito Não Funcional |
| INT36 | O aplicativo deve fornecer opções de acessibilidade (modo escuro, esquemas de cores, conteúdos em libras, etc.) | Requisito Não Funcional |
| INT37 | O aplicativo deve fornecer feedback ao usuário em caso de erros/falhas | Requisito Não Funcional |
| INT38 | O aplicativo deve apresentar medidas de proteção | Requisito Não Funcional |
| INT39 | O aplicativo deve proteger os dados sensíveis do usuário | Requisito Não Funcional 

<div align="center">
<figcaption align="left">Tabela 2: Requisitos identificados através da introspecção do ponto de vista da empresa (Autor: GONTIJO, Rodrigo 2024)</figcaption>
</div>
<br/>

## Bibliografia

[1] PAGANINI, Diogo. Técnicas para Elicitação de Requisitos, 2019. Disponível em: <https://pt.linkedin.com/pulse/técnicas-para-elicitação-de-requisitos-diogo-paganini>

[2] PUC-Rio. Elicitação de Requisitos, acesso em 12 de abril de 2024. Disponível em: <https://www.maxwell.vrac.puc-rio.br/15760/15760_3.PDF>


## Histórico de Versão
| Versão | Data de execução | Data de revisão |  Descrição            | Autor(es)         | Revisor(es)  |
| :------: | :----------: | :--------: | :--------------------: | :-------------: | :----------: |
| `1.3` | 22/04/2024  | 22/04/2024 | Correções ortográficas | [Henrique Galdino](https://github.com/hgaldino05), [Rodrigo Gontijo](https://github.com/rodrigogontijoo) | [Guilherme Meister](https://github.com/gmeister18), [Igor Thiago](https://github.com/alladin-51) |
| `1.2` | 21/04/2024  | 22/04/2024 | Introspecção de empresa | [Rodrigo Gontijo](https://github.com/rodrigogontijoo) | [Guilherme Meister](https://github.com/gmeister18) |
| `1.1` | 16/04/2024  | 16/04/2024 | Correções de formatação da revisão | [Rodrigo Gontijo](https://github.com/rodrigogontijoo) | [Guilherme Meister](https://github.com/gmeister18) |
| `1.0` | 10/04/2024  | 10/04/2024 | Criação do artefato de introspecção | [Henrique Galdino](https://github.com/hgaldino05) | [Igor Thiago](https://github.com/alladin-51) |


<div align="center">
<figcaption align="left">Tabela 2: Histórico de versões(Autor: GALDINO, Henrique 2024)</figcaption>
</div>
<br/>
