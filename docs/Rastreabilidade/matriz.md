# Matriz de Rastreabilidade

## Introdução

Diversas técnicas são utilizadas para indicar a rastreabilidade dos requisitos elicitados ao decorrer do desenvolvimento de um projeto, entre elas as ***matrizes de rastreabilidade***.

Matrizes de rastreabilidade podem ser tabelas, planilhas e/ou outras ferramentas que associam requisitos com artefatos os quais eles estão relacionados, os quais podem ser documentos, artefatos do desenvolvimento ou até mesmo outros requisitos, permitindo identificar as origens e dependências dos mesmos e visualizar estas informações de forma simples e organizada.

## Metodologia

A matriz de rastreabilidade elaborada apresenta uma relação dos requisitos elicitados, trazendo também as seguintes informações sobre os mesmos:

- **ID**: identifica o requisito    
- **Tipo**: define como Funcional ou Não Funcional
- **Descrição**: descrição do requisito
- **Implementação**: define se ele já está implementado ou não
- **Pré-rastreabilidade**: apresenta a origem do requisito (documentos, técnicas, etc)
- **Artefatos**: apresenta os artefatos associados ao requisito
- **Elos**: associação entre os requisitos e os artefatos

## Matriz

A tabela 01 traz a Matriz de Rastreabilidade criada para o projeto, a qual segue a seguinte legenda:

- ***RNF: Requisito funcional***
- ***RF: Requisito não funcional***
- ***QUE: Requisito de Questionário***
- ***ST: Requisito de Storytelling***
- ***ADD: Requisito de Análise de Documentos***
- ***INT: Requisito de Introspecção***
- ***CDU: Casos de Uso***
- ***CEN: Cenários***
- ***ESP: Especificação Suplementar***
- ***LEX: Léxicos***
- ***BDP: Backlog do Produto***
- ***HUS: Histórias de Usuário***
- ***NFR: NFR Framework***

| ID | REQUISITO | DESCRIÇÃO | IMPLEMENTAÇÃO | PRÉ-RASTREABILIDADE | ARTEFATOS | ELOS |
| :-: | :--: | :--: | :--: | :--: | :--: | :--: |
| M1 | RF1 | Deve ser possível fazer login utilizando o gov.br |  |  |  |  |
| M2 | RF2 | Deve ser possível pesquisar uma empresa pelo nome	 |  |  |  |  |
| M3 | RF3 | Deve ser possível ver dados sobre uma empresa (CNPJ, contatos, estatísticas, etc.)	 |  |  |  |  |
| M4 | RF4 | Deve ser exibidos gráficos/indicadores relacionados aos dados sobre uma empresa (Tempo médio de resposta, confiabilidade, etc.)	 |  |  |  |  |
| M5 | RF5 | Deve ser possível informar as circunstâncias da compra do produto/serviço (internet, loja física, telefone, etc.)	 |  |  |  |  |
| M6 | RF6 | Deve ser possível escolher qual a categoria da reclamação (atendimento, cobrança, entrega, etc.)	 |  |  |  |  |
| M7 | RF7 | Deve ser possível fornecer detalhes sobre a reclamação	 |  |  |  |  |
| M8 | RF8 | Deve ser possível informar o que espera da empresa (reembolso, resposta, justificativa, etc.)	 |  |  |  |  |
| M9 | RF9 | Deve ser possível anexar arquivos relacionados a reclamação (prints, nota fiscal, ordem de serviço, etc.)	 |  |  |  |  |
| M10 | RF10 | Deve ser possível visualizar as reclamações feitas no app	 |  |  |  |  |
| M11 | RF11 | Deve ser possível acompanhar o status de uma reclamação feita	 |  |  |  |  |
| M12 | RF12 | Deve ser possível receber notificações sobre o status de reclamações	 |  |  |  |  |
| M13 | RF13 | Deve ser possível visualizar reclamações feitas por outros usuários	 |  |  |  |  |
| M14 | RF14 | Deve ser possível visulizar detalhes de uma reclamação de outro usuário (status, avaliação, tempo de resposta, etc.)	 |  |  |  |  |
| M15 | RF15 | Deve ser possível avaliar uma reclamação (nível de satisfação/nota)	 |  |  |  |  |
| M16 | RF16 | Deve ser possível cadastrar os dados de uma empresa	 |  |  |  |  |
| M17 | RF17 | Deve ser possível fazer upload da logomarca para o cadastro de uma empresa	 |  |  |  |  |
| M18 | RF18 | Deve ser possível anexar documentos para o cadastro de uma empresa	 |  |  |  |  |
| M19 | RF19 | Deve ser possível visualizar as reclamações feitas sobre uma empresa	 |  |  |  |  |
| M20 | RF20 | Deve ser possível visualizar como o cliente fez a compra	 |  |  |  |  |
| M21 | RF21 | Deve ser possível visualizar qual tipo de reclamação o cliente apresentou	 |  |  |  |  |
| M22 | RF22 | Deve ser possível visualizar os detalhes e anexos de uma reclamação sobre uma empresa	 |  |  |  |  |
| M23 | RF23 | Deve ser possível responder uma reclamação feita	 |  |  |  |  |
| M24 | RF24 | Deve ser possível visualizar estatísticas das reclamações sobre uma empresa	 |  |  |  |  |
| M25 | RF25 | Deve ser possível visualizar avaliação das reclamações	 |  |  |  |  |
| M26 | RNF1 | O aplicativo deve funcionar tanto em dispositivos Android quanto iOS	 |  |  |  |  |
| M27 | RNF2 | Novos usuários devem ser capazes de realizar as tarefas básicas (ex.:acessar conta, fazer reclamação) em menos de 5 minutos	 |  |  |  |  |
| M28 | RNF3 | O aplicativo deve fornecer opções de acessibilidade (ex: modo escuro, esquemas de cores, conteúdos em libras)	 |  |  |  |  |
| M29 | RNF4 | O aplicativo deve fornecer feedback ao usuário em caso de erros/falhas	 |  |  |  |  |
| M30 | RNF5 | Todos os dados sensíveis devem ser devidamente protegidos utilizando criptografia	 |  |  |  |  |
| M31 | RNF6 | O aplicativo deve validar a entrada do usuário(gov.br) para prevenção de ataques	 |  |  |  |  |
| M32 | RNF7 | O aplicativo deve iniciar o carregamento de telas/componentes em até 2 segundos	 |  |  |  |  |
| M33 | RNF8 | As ações principais do site (ex.:fazer reclamação, ver reclamação) devem ser executadas em no máximo 5 passos	 |  |  |  |  |
| M34 | RNF9 | O aplicativo não deve ficar indisponível por mais de 24 horas (exceto sob aviso prévio)	 |  |  |  |  |
| M35 | RNF10 | O aplicativo deve carregar interfaces e/ou componentes dentro de 20 segundos	 |  |  |  |  |
| M36 | RNF11 | O aplicativo deve apresentar opções de suporte ao usuário (instruções de uso, FAQ, Fale conosco, fórum de dúvidas, etc.)	 |  |  |  |  |
| M37 | RNF12 | O aplicativo deve apresentar termo de uso	 |  |  |  |  |
| M38 | RNF13 | O aplicativo deve seguir as normas e padrões do gov.br	 |  |  |  |  |
| M39 | RNF14 | O aplicativo deve estabelecer e seguir um padrão de cores e tamanhos para suas interfaces/componentes	 |  |  |  |  |

<div align="center">
<figcaption align="center">Tabela 01: Matriz de Rastreabilidade (Autor: Henrique Galdino)</figcaption>
</div>
<br/>


## Histórico de Versão

| Versão | Data de execução | Data de revisão |  Descrição                          | Autor(es)                                           | Revisor(es)                                           |
| :----: | :--------------: | :-------------: | :---------------------------------: | :-------------------------------------------------: | :---------------------------------------------------: |
| 1.2    | 19/06/2024       | 19/06/2024      | Informações da matriz   | Guilherme Meister, Henrique Galdino, Igor Thiago, Júlio César, Matheus Ferreira, Rodrigo Gontijo   | Guilherme Meister, Henrique Galdino, Igor Thiago, Júlio César, Matheus Ferreira, Rodrigo Gontijo |
| 1.1    | 13/06/2024       | 13/06/2024      | Criação da matriz   | [Henrique Galdino](https://github.com/hgaldino05)   | [Júlio César](https://github.com/Julio1099)         |
| 1.0    | 12/06/2024       | 12/06/2024      | Criação do artefato | [Henrique Galdino](https://github.com/hgaldino05)   | [Júlio César](https://github.com/Julio1099)         |

<div align="center">
<figcaption align="center">Tabela 02: Histórico de versões (Autor: Henrique Galdino)</figcaption>
</div>
<br/>

