# Introspecção

## Introdução

A introspecção é uma técnica que consiste em analisar e identificar, a partir do ponto de vista do usuário, quais características e funcionalidades um sistema deve apresentar. Esta técnica é muito usada para constatar inicialmente quais requisitos podem ser associados ao sistema, e serve como base para a elicitação dos mesmos.

## Metodologia

Após conversas entre os membros da equipe, foram relatadas diversas situações nas quais os mesmos poderiam ter feito uso da plataforma Consumidor.gov, e como as funcionalidades do app poderiam ter ajudado a contornar os problemas enfrentados. Para o uso da técnica de  introspecção, foi imaginado um possível contexto no qual um usuário poderia fazer uso do aplicativo Consumidor.gov, e a partir disso, foram identificados os requisitos que seriam necessários para que este pudesse tentar resolver o problema enfrentado, sendo que o membro Henrique Galdino ficou responsável por esta tarefa.


## **Ponto de vista - Consumidor**
O contexto imaginado foi o seguinte:

- Henrique comprou um produto pela internet e o mesmo não foi entregue no prazo estipulado, e tentou entrar em contato com a empresa responsável, mas não obteve nenhum tipo de resposta nos meios informados na seção de Atendimento ao cliente. Henrique então decidiu utilizar o aplicativo ***Consumidor.gov*** para tentar resolver o problema. 
- Dentro do app, pode encontrar a empresa e registrar uma reclamação, adicionando os detalhes do ocorrido e anexando prints das tentativas de contato com a empresa. Após a reclamação ser registrada, a empresa foi notificada e entrou em contato com Henrique, dando início a tentativa de resolução do problema.

A partir deste contexto, Henrique identificou alguns requisitos, que podem ser vistos na **tabela 1**, identificados com o código ***INT*** e numerados de **1** até **16**, junto com a **descrição** do requisito.

### Requisitos identificados
| Identificador  |     Descrição    |
| :-: | :----------------------------------------: |
| INT01 | Deve ser possível fazer login utilizando o gov.br |
| INT02 | Deve ser possível pesquisar uma empresa pelo nome |
| INT03 | Deve ser possível visualizar o "perfil" uma empresa |
| INT04 | Deve ser possível visualizar contatos da empresa no perfil (email, telefone, redes sociais) |
| INT05 | Deve ser possível informar como/onde foi feita a compra (internet, loja física, telefone, etc.) |
| INT06 | Deve ser possível escolher qual a categoria da reclamação (atendimento, cobrança, entrega, etc.) |
| INT07 | Deve ser possível fornecer detalhes sobre a reclamação |
| INT08 | Deve ser possível informar o que espera da empresa (reembolso, resposta, justificativa, etc.) |
| INT09 | Deve ser possível anexar arquivos relacionados a reclamação (prints, nota fiscal, ordem de serviço, etc.) |
| INT10 | Deve ser possível visualizar as reclamações feitas |
| INT11 | Deve ser possível acompanhar o status de uma reclamação feita |
| INT12 | Deve ser possível notificar atualizações sobre o status de uma reclamação feita |
| INT13 | Deve ser possível visualizar as reclamações feitas por outros usuários |
| INT14 | Deve ser possível visualizar os detalhes de uma reclamação feita por outro usuário (status, avaliação, tempo de resposta, etc.) |
| INT15 | Deve ser possível avaliar uma reclamação (nível de satisfação/nota) |
| INT16 | Deve ser possível comparar as estatísticas de empresas diferentes |

<div align="center">
<figcaption align="left">Tabela 1: Requisitos identificados através da introspecção do ponto de vista do consumidor (Autor: GALDINO, Henrique 2024)</figcaption>
</div>
<br/>

## **Ponto de vista - Empresa**
O contexto imaginado foi o seguinte:

- Rodrigo é dono de uma rede de restaurantes com uma grande quantidade de clientes. Recentemente, ele percebeu que muitos clientes estão reclamando sobre a demora no atendimento das unidades presenciais e na entrega de produtos via delivery. Procurando entender melhor o problema e buscar soluções para o mesmo, Rodrigo decidiu utilizar o aplicativo ***Consumidor.gov*** para facilitar o contato com a clientela e garantir que suas reclamações sejam ouvidas pela empresa.
- Dentro do ***Consumidor.gov***, Rodrigo pode encontrar todas reclamações feitas contra a sua empresa, podendo visualizar melhor os detalhes dos problemas enfrentados pelos consumidores e o que eles esperam como possível solução. Além disso, ele pode responder as reclamações, prestando suporte para os incidentes relatados e buscando melhorar a prestação dos serviços ofertados pela empresa. Com isso, Rodrigo consegue melhorar o atendimento da empresa e garantir a satisfação de seus fiéis clientes.

A partir deste contexto, Rodrigo identificou alguns requisitos, que podem ser vistos na **tabela 2**, identificados com o código ***INT*** e numerados de **17** até **27**, junto com a **descrição** do requisito.

### Requisitos identificados
| Identificador  |     Descrição    |
| :-: | :----------------------------------------: | 
| INT17 | Deve ser possível fazer login utilizando o gov.br |
| INT18 | Deve ser possível cadastrar os dados da empresa |
| INT19 | Deve ser possível fazer upload da logomarca da empresa |
| INT20 | Deve ser possível anexar documentos no cadastro |
| INT21 | Deve ser possível visualizar as reclamações feitas |
| INT22 | Deve ser possível visualizar como o cliente fez a compra |
| INT23 | Deve ser possível visualizar qual tipo de problema o cliente teve |
| INT24 | Deve ser possível visualizar os detalhes e anexos de uma reclamação |
| INT25 | Deve ser possível responder uma reclamação feita |
| INT26 | Deve ser possível visualizar estatísticas das reclamações |
| INT27 | Deve ser possível visualizar avaliação das reclamações |

<div align="center">
<figcaption align="left">Tabela 2: Requisitos identificados através da introspecção do ponto de vista da empresa (Autor: GONTIJO, Rodrigo 2024)</figcaption>
</div>
<br/>

## Requisitos Não Funcionais
Além dos requisitos funcionais, foram identificados alguns requisitos não funcionais que são importantes para o funcionamento do aplicativo. Estes requisitos são comuns para ambos os pontos de vista (consumidor e empresa), que podem ser vistos na **tabela 3**, numerados de **28** a **45**, junto com a **descrição** do requisito.

| Identificador  |     Descrição    |
| :-: | :----------------------------------------: |
| INT28 | O aplicativo deve funcionar tanto em dispositivos Android quanto iOS |
| INT29 | O aplicativo deve ser otimizado para os dispositivos compatíveis (funcionamento, proporções/dimensões de telas e componentes) |
| INT30 | O aplicativo deve estar preparado para alterações/atualizações |
| INT31 | O aplicativo (e suas diferentes versões) deve estar sujeito a testes  |
| INT32 | O aplicativo deve apresentar interfaces simples, com uma quantidade moderada de componentes e informações |
| INT33 | O aplicativo deve apresentar interfaces intuitivas, que permitam o usuário realizar ações em até 5 "cliques" |
| INT34 | O aplicativo deve carregar telas e componentes em no menos de 20 segundos |
| INT35 | O aplicativo deve realizar suas funções (login, upload de arquivos, envio de reclamação, etc.) em menos de 20 segundos |
| INT36 | O aplicativo deve seguir um padrão no que diz respeito a estilização e dimensionamento de interfaces e componentes |
| INT37 | O aplicativo deve seguir as normas e padrões do gov.br |
| INT38 | O aplicativo deve fornecer opções de acessibilidade (modo escuro, esquemas de cores, conteúdos em libras, etc.) |
| INT39 | O aplicativo deve responder imediatamente às ações do usuário (mesmo que seja necessário carregamento de interfaces, componentes e/ou funções) |
| INT40 | O aplicativo deve estar disponível a qualquer momento (com exceção de desativação proposital ou acidental) |
| INT41 | O aplicativo deve fornecer feedback ao usuário em caso de erros/falhas |
| INT42 | O aplicativo deve apresentar medidas de proteção contra invasões/acessos sem autorização|
| INT43 | O aplicativo deve proteger os dados sensíveis do usuário |
| INT44 | O aplicativo deve apresentar guias de utilização |
| INT45 | O aplicativo deve apresentar Termos de Uso |


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
<figcaption align="left">Tabela 4: Histórico de versões(Autor: GALDINO, Henrique 2024)</figcaption>
</div>
<br/>
