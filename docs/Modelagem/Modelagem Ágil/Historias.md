# Histórias de Usuário

## Introdução
História do usuário é uma descrição curta de uma funcionalidade do sistema projetado contada do ponto de vista do usuário final, é um instrumento utilizado do processo de elicitação de requisitos e serve para facilitar o entendimento dos desenvolvedores acerca do produto que será desenvolvido já que responde de maneira rápida o que o usuário final precisa.

## Padrão de história de usuário
A história do usuário adotará o seguinte padrão

| Propriedades | Descrição |
|------|:-------:
| ID | US1 |
| Título | Nome da história |
| Descrição | Eu, como XXX, quero que XXX, para XXX |
| Critérios de aceitação | - Deve ser implementado XXX |
| Prioridade | Alta, média ou baixa |

<div style="text-align: center">
<p> Tabela 1: Modelo de história do usuário. (Autor: DIOGO, Matheus. 2024).</p>
</div>

## História do Usuário
A seguir estão as tabelas que descrevem as histórias de usuário elicitadas pelo grupo.

### US1 - Login no aplicativo

| Propriedades | Descrição |
|------|:-------:
| ID | US1 |
| Título | Criação de conta e login |
| Descrição | Eu, como usuário, quero poder fazer o login no aplicativo pela conta do gov.br, para que eu possa usar o aplicativo |
| Critérios de aceitação | - O aplicativo deve fornecer a opção de fazer o login com uma conta do gov.br |
| Prioridade | Alta |

### US2 - Pesquisar empresa

| Propriedades | Descrição |
|------|:-------:
| ID | US2 |
| Título | Pesquisar empresa pelo nome |
| Descrição | Eu, como cliente, quero pesquisar uma empresa pelo nome para que eu possa encontrar informações sobre ela. |
| Critérios de aceitação | - O aplicativo deve permitir a pesquisa de empresas pelo nome. |
| Prioridade | Alta |

### US3 - Ver dados sobre uma empresa

| Propriedades | Descrição |
|------|:-------:
| ID | US3 |
| Título | Ver dados sobre uma empresa |
| Descrição | Eu, como cliente, quero ver os dados de uma empresa para que eu possa obter informações detalhadas sobre ela. |
| Critérios de aceitação | <ol><li>- O aplicativo deve exibir os dados oficiais da empresa (CNPJ, contatos, endereço, etc.). <li>- O aplicativo deve exibir os dados sobre as reclamações da empresa (notas, avaliações, comentários, etc.).<li>- O aplicativo deve exibir gráficos e indicadores sobre a empresa, como tempo médio de resposta e confiabilidade. <ul></ol> |
| Prioridade | Alta |

### US4 - Fazer reclamação

| Propriedades | Descrição |
|------|:-------:
| ID | US4 |
| Título | Fazer reclamação sobre uma empresa |
| Descrição | Eu, como cliente, quero poder fazer uma reclamação sobre uma empresa, para que possa ter meu problema resolvido. |
| Critérios de aceitação | <ol><li>- O aplicativo deve permitir que o usuário informe o meio que a compra foi feita.<li>- O aplicativo deve permitir que o usuário informe a categoria da informação.<li>- O aplicativo deve permitir que o usuário informe detalhes sobre a reclamação.<li>- O aplicativo deve permitir que o usuário informe suas expectativas quanto a resolução da reclamação.<ul></ol> |
| Prioridade | Alta |

### US5 - Anexar arquivos na reclamação

| Propriedades | Descrição |
|------|:-------:
| ID | US5 |
| Título | Anexar arquivos na reclamação |
| Descrição | Eu, como usuário, quero anexar arquivos relacionados à minha reclamação para que eu possa fornecer evidências do problema. |
| Critérios de aceitação | - O aplicativo deve permitir o upload de arquivos como prints, nota fiscal, ordem de serviço, etc. |
| Prioridade | Alta |

### US6 - Visualizar reclamações feitas no app

| Propriedades | Descrição |
|------|:-------:
| ID | US6 |
| Título | Visualizar reclamações feitas no app |
| Descrição | Eu, como usuário, quero visualizar as reclamações que fiz no app para que eu possa acompanhar todas as minhas interações. |
| Critérios de aceitação | - O aplicativo deve exibir uma lista de todas as reclamações feitas pelo usuário. |
| Prioridade | Alta |

### US7 - Acompanhar status de uma reclamação

| Propriedades | Descrição |
|------|:-------:
| ID | US7 |
| Título | Acompanhar status de uma reclamação |
| Descrição | Eu, como usuário, quero acompanhar o status de uma reclamação feita para que eu possa saber seu andamento. |
| Critérios de aceitação | - O aplicativo deve exibir o status atual de cada reclamação feita pelo usuário. |
| Prioridade | Alta |

### US8 - Receber notificações sobre o status das reclamações

| Propriedades | Descrição |
|------|:-------:
| ID | US8 |
| Título | Receber notificações sobre o status das reclamações |
| Descrição | Eu, como usuário, quero receber notificações sobre o status das minhas reclamações para que eu esteja sempre atualizado. |
| Critérios de aceitação | - O aplicativo deve enviar notificações quando houver atualizações no status das reclamações. |
| Prioridade | Baixa |

### US9 - Visualizar reclamações de outros usuários

| Propriedades | Descrição |
|------|:-------:
| ID | US9 |
| Título | Visualizar reclamações de outros usuários |
| Descrição | Eu, como usuário, quero visualizar reclamações feitas por outros usuários para que eu possa ver problemas semelhantes. |
| Critérios de aceitação |<ol><li>- O aplicativo deve exibir uma lista de reclamações feitas por outros usuários.<li>- O aplicativo deve exibir os detalhes de cada reclamação (tipo, detalhes, anexos, etc.).<ul></ol> |
| Prioridade | Média |

### US10 - Avaliar uma reclamação

| Propriedades | Descrição |
|------|:-------:
| ID | US10 |
| Título | Avaliar uma reclamação |
| Descrição | Eu, como usuário, quero avaliar uma reclamação para que eu possa dar feedback sobre a resolução do problema. |
| Critérios de aceitação | - O aplicativo deve permitir que o usuário avalie uma reclamação com um nível de satisfação/nota. |
| Prioridade | Média |

### US11 - Cadastrar dados de uma empresa

| Propriedades | Descrição |
|------|:-------:
| ID | US11 |
| Título | Cadastrar dados de uma empresa |
| Descrição | Eu, como administrador, quero cadastrar os dados de uma empresa para que ela esteja disponível no sistema. |
| Critérios de aceitação |<ol><li>- O aplicativo deve permitir o cadastro de dados como nome, CNPJ, contatos, etc.<li>- O aplicativo deve permitir o upload de uma imagem da logomarca da empresa.<li>- O aplicativo deve permitir o upload de documentos relevantes.<ul></ol>|
| Prioridade | Alta |

### US12 - Responder uma reclamação 

| Propriedades | Descrição |
|------|:-------:
| ID | US12 |
| Título | Responder uma reclamação feita |
| Descrição | Eu, como administrador, quero responder uma reclamação feita para que eu possa fornecer uma solução ao cliente. |
| Critérios de aceitação | - O aplicativo deve permitir que o administrador responda a reclamações dos clientes. |
| Prioridade | Alta |

### US13 - Funcionamento em Android e iOS

| Propriedades | Descrição |
|------|:-------:
| ID | US13 |
| Título | Funcionamento em Android e iOS |
| Descrição | Eu, como usuário, quero que o aplicativo funcione tanto em dispositivos Android quanto iOS para que eu possa usá-lo em qualquer dispositivo. |
| Critérios de aceitação | - O aplicativo deve ser compatível com as plataformas Android e iOS. |
| Prioridade | Alta |

### US14 - Interface simples e intuitiva

| Propriedades | Descrição |7
|------|:-------:
| ID | US14 |
| Título | Interface simples e intuitiva |
| Descrição | Eu, como usuário, quero que o aplicativo apresente uma interface simples e intuitiva para que eu possa usá-lo facilmente. |
| Critérios de aceitação | - O aplicativo deve ter uma interface de usuário clara e fácil de navegar. |
| Prioridade | Alta |

### US15 - Opções de acessibilidade 

| Propriedades | Descrição |
|------|:-------:
| ID | US15 |
| Título | Opções de acessibilidade |
| Descrição | Eu, como usuário com necessidades especiais, quero que o aplicativo forneça opções de acessibilidade (modo escuro, esquemas de cores, conteúdos em libras, etc.) para que eu possa usá-lo confortavelmente. |
| Critérios de aceitação | - O aplicativo deve incluir opções de acessibilidade como modo escuro, ajustes de cores e conteúdos em libras. |
| Prioridade | Média |

### US16 - Feedback em caso de erros

| Propriedades | Descrição |
|------|:-------:
| ID | US16 |
| Título | Feedback em caso de erros |
| Descrição | Eu, como usuário, quero que o aplicativo forneça feedback em caso de erros/falhas para que eu saiba o que está acontecendo e como corrigir. |
| Critérios de aceitação | - O aplicativo deve exibir mensagens de erro claras e instruções para correção. |
| Prioridade | Alta |

### US17 - Medidas de proteção 

| Propriedades | Descrição |
|------|:-------:
| ID | US17 |
| Título | Medidas de proteção |
| Descrição | Eu, como usuário, quero que o aplicativo apresente medidas de proteção para que meus dados estejam seguros. |
| Critérios de aceitação | - O aplicativo deve implementar medidas de segurança como criptografia de dados e autenticação de usuário. |
| Prioridade | Alta |

### US18 - Otimização de carregamento

| Propriedades | Descrição |
|------|:-------:
| ID | US18 |
| Título | Otimização de carregamento |
| Descrição | Eu, como usuário, quero que o aplicativo otimize o carregamento de páginas/recursos para que minha experiência seja rápida e eficiente. |
| Critérios de aceitação | - O aplicativo deve carregar páginas e recursos de forma rápida e eficiente. |
| Prioridade | Média |

## Bibliografia
<div text-align="justify">
[1] LONGO, Hugo. A Utilização de Histórias de Usuários no Levantamento de Requisitos Ágeis, disponível no <a href="https://periodicos.ufsc.br/index.php/ijkem/article/view/81819/46487">link</a>. Acessado em 18 de maio. de 2024. </div>


## Histórico de Versões
| Data | Versão | Descrição | Autor(es) | Data de revisão | Revisor(es) |
| :--:       | :----: | :-------: | :---: | :-------------: | :-----: |
| 18/05/2024 | `1.0`  | Criação do artefato | [Guilherme Meister](https://github.com/gmeister18) e [Matheus Ferreira](https://github.com/matferreira1) | 10/04/2024 | [Henrique Galdino](https://github.com/hgaldino05) e [Rodrigo ](https://github.com/rodrigogontijoo) |
