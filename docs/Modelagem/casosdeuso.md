# Casos de Uso

## Introdução

O diagrama de casos, também chamado de diagrama comportamental, na notação da UML, tem como proposta documentar a maneira como o sistema deve se comportar do ponto de vista do usuário externo, utilizando dos léxicos levantados para elaboração dos casos de uso, dessa forma descrevendo um conjunto de ações do sistema.

## Metodologia 
  
Para criação do artefato realizamos a criação de um diagrama de casos de uso UML com o intuito de mostrar como o sistema deve se comportar. Foi utilizada o <a href="https://www.lucidchart.com/pages/pt">LucidChart</a>, para criar o diagramação no geral. 

## Componentes e símbolos

Um diagrama de casos de uso possui os seguintes elementos em sua composição:

| Nome | Função | Elemento
|------|------|:-------:
| Atores | Representam os usuários e sistemas, ou um tipo dele, normalmente são representados por bonecos de palito | <img src="https://github.com/Requisitos-de-Software/2024.1-Consumidor.gov/blob/main/assets/img/modelagem/ator-removebg-preview.png?raw=true" width="100">
| Caso de uso | É uma atuação ou funcionalidade realizada pelo ator.Geralmente são definidos por um objeto na forma oval horizontal | <img src="https://github.com/Requisitos-de-Software/2024.1-Consumidor.gov/blob/main/assets/img/modelagem/Casoa-removebg-preview.png?raw=true" width="200">
| Cenário | Nesse elemento, é descrito os eventos que acontecem quando um usuário manuseia o sistema. | <img src="https://github.com/Requisitos-de-Software/2024.1-Consumidor.gov/blob/main/assets/img/modelagem/Cenario-removebg-preview.png?raw=true" width="200">
| Comunicação (ou ação) | Consiste em uma ação que o usuário irá realizar sobre o caso de uso | <img src="https://github.com/Requisitos-de-Software/2024.1-Consumidor.gov/blob/main/assets/img/modelagem/Comunicacao-removebg-preview.png?raw=true" width="270">

<div style="text-align: center">
<p> Tabela 1: Elementos do diagrama de casos de uso. (Fonte: MEISTER, Guilherme. 2024).</p>
</div>

## Diagrama de casos de uso

Segue o diagrama de casos de uso feito.

<img src="https://github.com/Requisitos-de-Software/2024.1-Consumidor.gov/blob/main/docs/assets/Diagrama%20de%20caso%20de%20uso.png?raw=true"/>

## Especificação dos Casos de uso

Os casos de usos mais importantes e mais utilizados no aplicativo estão representados na Figura 2. Uma melhor visualização da imagem pode ser encontrada em <a >casos de uso Consumidor.gov.</a></p>

<p align="justify">A Figura 2 apresenta o diagrama de casos de uso do aplicativo Consumidor.gov.</p>

<img src="" width="100%">

<div align="center">
<p> <b>Figura 2</b>: Elemento comunicação (Fonte: FERREIRA, Matheus 2024). </p>
</div>

<p align="justify">A seguir, a especificação dos casos de uso identificados com 'UC' (Use case) seguido por uma enumeração.</p>

### UC01. 

| UC01 | Pesquisar empresa |
| :-----: | :-----: |
| **Atores** | Usuário |
| **Frequência de uso** | Alta |
| **Requisitos** | Abrir a página principal do app |
| **Condição de entrada** | O usuário utiliza a barra de pesquisa para encontrar a empresa desejada |
| **Fluxo principal** | <b>Fluxo 1: O Usuário clica em pesquisar empresa</b> <ol> <li> O sistema abre uma barra de pesquisa <li> De acordo com as palvaras digitadas, o app mostra as empresas disponíveis <li> O usuário escolhe uma opção <ul> </ol> <b> Fluxo 2: O usuário clica em abrir uma empresa</b> <ol> <li> O sistema abre os indicadores da empresa </ol> <b> Fluxo 3: O usuário navega entre os dados da empresa </b> <ol> <li> O Sistema oferece indicadores do ano atual e dentre todos os anos <ul> <li> O usuários podem obter todas as informações sobre o feedback da empresa </ol> |
| **Fluxos alternativos** | Não há |
| **Fluxos de exceção** |  - Falha de conexão à internet. <br> - Aplicativo travou |
| **Pós condições** | O usuário tem a opção de abrir reclamação |
| **Data da criação** | 17/05/24 |
| **Rastreabilidade** | ST04  |

 <a href="https://github.com/Requisitos-de-Software/2024.1-Consumidor.gov/blob/main/assets/UC1%20(1).pdf">Arquivo **PDF** aqui</a>

<div style="text-align: center">
<p> Tabela 2: Especificação do caso de uso: Pesquisar empresa. (Fonte: MEISTER, Guilherme. 2024).</p>
</div>

### UC02.

| UC02 | Fazer reclamação |
| :-----: | :-----: |
| **Atores** | Usuário |
| **Frequência de uso** | Alta |
| **Requisitos** | Disponibilidade da empresa no app |
| **Condição de entrada** | O usuário seleciona encontra a empresa e abre reclamação |
| **Fluxo principal** | <b>Fluxo 1: O Usuário clica na empresa desejada </b> <ol> <li> O sistema responde mostrando indicadores da empresa <li>É exibida a opção de fazer reclamação  </ol> <b> Fluxo 2: O usuário clica em QUERO RECLAMAR </b> <ol> <li> O sistema abre a página para registrar reclamação <li> O usuário tem que responder as seguintes perguntas <ul> <li> Procurou a empresa? <li> Como comprou? <li> Área <li> Assunto <li> Problema </ol> <b> Fluxo 3: O usuário clica em Próximo </b> <ol> <li> O sistema abre a página para informações adicionais <ul> <li> Nota Fiscal <li> Data de compra <li> Ordem de compra <li> Marca/modelo </ol> <b>Fluxo 4: O usuário clica próximo </b> <ol> <li> O sistema mostra espaços para cadastro de ultimas informações <ul> <li> Descreva a Reclamação <li> Pedido à empresa <li> incluir anexo </ol> <b> Fluxo 5: O usuário clica em Próximo </b> <ol> <li> O sistema mostra o resumo da reclamação <li> usuário confirma. |
| **Fluxos alternativos** | Não há |
| **Fluxos de exceção** | - Falha de conexão à internet. <br> - Aplicativo travou |
| **Pós condições** | Não há |
| **Data da criação** | 17/05/24 |
| **Rastreabilidade** | ST01 ST03 |

<a href="https://github.com/Requisitos-de-Software/2024.1-Consumidor.gov/blob/main/assets/UC2.pdf">Arquivo **PDF** aqui</a>

<div style="text-align: center">
<p> Tabela 2: Especificação do caso de uso: Abrir reclamação. (Fonte: MEISTER, Guilherme. 2024).</p>
</div>

### UC03.

| UC03 | Visualizar reclamações de outros usuários |
|  :-----: |  :-----: |
| **Atores** | Usuário |
| **Frequência de uso** | Alta |
| **Requisitos** | disponibilidade da reclamações recentes no app |
| **Condição de entrada** | O usuário seleciona reclamações de outros usuários |
| **Fluxo principal** | <b>Fluxo 1: O Usuário clica em reclamações de outros usuários </b> <ol> <li> O sistema responde mostrando as ultimas reclamações <li> O usuário pode visualizar a reclamação com mais detalhes </ol> <b> Fluxo 2: O usuário clica na reclamação de outro cliente </b> <ol> <li> O sistema abre a página com os detalhes da reclamção </ol> <b> Fluxo 3: O usuário clica em filtrar </b> <ol> <li> O sistema abre um pop-up com opção de filtragem <ul> <li> Palavra chave <li> Fornecedor |
| **Fluxos alternativos** | Não há |
| **Fluxos de exceção** | - Falha de conexão à internet. <br> - Aplicativo travou |
| **Pós condições** | Não há |
| **Data da criação** | 17/05/24 |
| **Rastreabilidade** | QUE04 ST05 ST07 |

formato **PDF** <a href="https://github.com/Requisitos-de-Software/2024.1-Consumidor.gov/blob/main/assets/UC1%20(1).pdf">aqui</a>

<div style="text-align: center">
<p> Tabela 3: Especificação do caso de uso: Visualizar reclamações de outros usuários. (Fonte: FERREIRA, Matheus. 2024).</p>
</div>

### UC04.

| UC04 | Visualizar minhas reclamações|
| :-----: | :-----:|
| **Atores** | Usuário |
| **Frequência de uso** | Alta |
| **Requisitos** | usuário já deve ter realizado uma reclamação no app |
| **Condição de entrada** | O usuário seleciona minhas reclamações |
| **Fluxo principal** | <b>Fluxo 1: O Usuário clica em minhas reclamações </b> <ol> <li> O sistema responde mostrando as reclamações feitas pelo usuário <li> O usuário pode visualizar o andamento da reclamação  </ol> <b> Fluxo 2: O usuário clica na reclamação </b> <ol> <li> O sistema abre a página com os detalhes da reclamção <ul> <li> área <li> Assunto <li> Problema <li> Gestor <li> Data de abertura </ol> <b> Fluxo 3: O usuário clica em interagir com o fornecedor </b> <ol> <li> O sistema abre uma página com opção de digitar uma mensagem à empresa |
| **Fluxos alternativos** | Não há |
| **Fluxos de exceção** | - Falha de conexão à internet. <br> - Aplicativo travou. |
| **Pós condições** | Não há |
| **Data da criação** | 17/05/24 |
| **Rastreabilidade** | ST02 QUE07 QUE06 |

formato **PDF** <a href="https://github.com/Requisitos-de-Software/2024.1-Consumidor.gov/blob/main/assets/UC1%20(1).pdf">aqui</a>

<div style="text-align: center">
<p> Tabela 4: Especificação do caso de uso: Visualizar minhas reclamações. (Fonte: GALDINO, Henrique. 2024).</p>
</div>

### UC05.

| UC05 | Visualizar Dados Gerais|
| :-----: | :-----: |
| **Atores** | Usuário |
| **Frequência de uso** | Baixa |
| **Requisitos** | usuário deve clicar na opção |
| **Condição de entrada** | O usuário seleciona dados gerais |
| **Fluxo principal** | <b>Fluxo 1: O Usuário clica em dados gerais </b> <ol> <li> O sistema responde mostrando dados sobre o app coletados desde 2014 <li> O usuário pode visualizar os dados:  <ul> <li> Total de Reclamações finalizadas <li> Total de usuários cadastrados <li> Total de empresas cadastradas |
| **Fluxos alternativos** | Não há |
| **Fluxos de exceção** | - Falha de conexão à internet. <br> - Aplicativo travou. |
| **Pós condições** | Não há |
| **Data da criação** | 17/05/24 |
| **Rastreabilidade** | QUE05 QUE04 |

formato **PDF** <a href="https://github.com/Requisitos-de-Software/2024.1-Consumidor.gov/blob/main/assets/UC1%20(1).pdf">aqui</a>

<div style="text-align: center">
<p> Tabela 5: Especificação do caso de uso: Visualizar Dados Gerais. (Fonte: THIAGO, Igor. 2024).</p>
</div>

### UC06.

| UC06 | Visualizar meus Dados |
| :-----: | :-----: |
| **Atores** | Usuário |
| **Frequência de uso** | Média |
| **Requisitos** | usuário deve ter um cadastro no app |
| **Condição de entrada** | O usuário seleciona meus Dados |
| **Fluxo principal** | <b>Fluxo 1: O Usuário clica em Menu </b> <ol> <li> O sistema responde mostrando a opção de visualizar dados de usuário <li> O usuário pode visualizar seu respectivos dados:  <ul> <li> nome <li> CPF <li> Data de nascimento </ol> <b>Fluxo 2: O Usuário clica em endereço </b> <ol> <li> O sistema responde mostrando dados de endereço do usuário </ol> <b>Fluxo 3: O Usuário clica em contato </b> <ol> <li> O sistema responde mostrando dados de contato do usuário |
| **Fluxos alternativos** | Não há |
| **Fluxos de exceção** | - Falha de conexão à internet. <br> - Aplicativo travou. |
| **Pós condições** | Não há |
| **Data da criação** | 17/05/24 |
| **Rastreabilidade** | ST09 |

formato **PDF** <a href="https://github.com/Requisitos-de-Software/2024.1-Consumidor.gov/blob/main/assets/UC1%20(1).pdf">aqui</a>

<div style="text-align: center">
<p> Tabela 6: Especificação do caso de uso: Visualizar meus Dados. (Fonte: CÉSAR, Julio. 2024).</p>
</div>

### UC07.

| UC07 | Responder Reclamação |
| :-----: | :-----: |
| **Atores** | Empresa |
| **Frequência de uso** | Alta |
| **Requisitos** | Empresa deve ter um cadastro no app |
| **Condição de entrada** | A empresa recebe uma reclamação advinda de um usuário |
| **Fluxo principal** | <ol> <li> A empresa recebe a reclamação <li> O  sistema da a opção de responder |
| **Fluxos alternativos** | Não há |
| **Fluxos de exceção** | - Falha de conexão à internet. <br> - Aplicativo travou. |
| **Pós condições** | Não há |
| **Data da criação** | 17/05/24 |
| **Rastreabilidade** | INT28 INT30 |

<div style="text-align: center">
<p> Tabela 7: Especificação do caso de uso: Responder Reclamação. (Fonte: GONTIJO, Rodrigo. 2024).</p>
</div>

### UC08.

| UC08 | Avaliar Empresa |
| :-----: | :-----: |
| **Atores** | Usuário |
| **Frequência de uso** | Alta |
| **Requisitos** | usuário deve ter feito uma reclamação |
| **Condição de entrada** | O usuário abre a seção da reclamação já finalizada |
| **Fluxo principal** |  <b>Fluxo 1: O Usuário clica em Minhas reclamações </b> <ol> <li> O sistema responde mostrando o andamento do processo da reclamação <li> O usuário tem a opção de avaliar a resposta do fornecedor </ol> <b>Fluxo 2: O Usuário clica em avaliar resposta </b> <ol> <li> O sistema responde mostrando um pop-up com campos para: <ul> <li> considerar a resolução da reclamação <li> avaliar seu grau de satisfação <li> fazer um comentário |
| **Fluxos alternativos** | Não há |
| **Fluxos de exceção** | - Falha de conexão à internet. <br> - Aplicativo travou. |
| **Pós condições** | Não há |
| **Data da criação** | 17/05/24 |
| **Rastreabilidade** | QUE07  |


<div style="text-align: center">
<p> Tabela 8: Especificação do caso de uso: Avaliar Empresa. (Fonte: MEISTER, Guilherme. 2024).</p>
</div>



## Bibliografia
<div text-align="justify">
[1] Ferramenta Lucidchart, disponível no <a href="https://www.lucidchart.com/pages/pt">link</a>. Acessado em 05 de maio. de 2024.
</div>

## Histórico de Versões
| Data | Versão | Descrição | Autor(es) | Data de revisão | Revisor(es) |
| :--:       | :----: | :-------: | :---: | :-------------: | :-----: |
| `1.5` | 18/05/2024  | 18/05/2024 | Finalização da página | [Guilherme Meister](https://github.com/gmeister18) | [Igor Thiago](https://github.com/alladin-51) |
| `1.4` | 18/05/2024  | 18/05/2024 | Adição das UC01, UC02 E UC07| [Rodrigo Gontijo](https://github.com/rodrigogontijoo), [Guilherme Meister](https://github.com/gmeister18) | [Igor Thiago](https://github.com/alladin-51) |
| `1.3` | 17/05/2024  | 18/05/2024 | Adição das UC04 E UC06 | [Júlio César](https://github.com/Julio1099), [Henrique Galdino](https://github.com/hgaldino05) | [Rodrigo Gontijo](https://github.com/rodrigogontijoo) |
| `1.2` | 17/05/2024  | 17/05/2024 | Adição das UC03 E UC05| [Igor Thiago](https://github.com/alladin-51), [Matheus Ferreira](https://github.com/matferreira1) | [Rodrigo Gontijo](https://github.com/rodrigogontijoo) |
| `1.1` | 15/05/2024  | 17/05/2024 | Adição Diagrama| [Guilherme Meister](https://github.com/gmeister18), [Henrique Galdino](https://github.com/hgaldino05) | [Igor Thiago](https://github.com/alladin-51) |
| `1.0` | 03/05/2024  | Criação do artefato | [Guilherme Meister](https://github.com/gmeister18) e [Matheus Ferreira](https://github.com/matferreira1) | 10/04/2024 | [Henrique Galdino](https://github.com/hgaldino05) e [Rodrigo ](https://github.com/rodrigogontijoo) |
