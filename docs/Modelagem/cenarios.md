# Cenários

## Introdução

Os cenários são conhecidos como uma estratégia para a compreensão da interface entre o ambiente e o sistema, bem como um meio de extrair e especificar o comportamento do software descrevendo as situações do ambiente, de acordo com as principais ações realizadas fora do sistema de software. Os cenários também ajudam a esclarecer a inter-relação entre requisitos funcionais e não funcionais.

## Metodologia


Há cinco maneiras de descrever cenários: texto narrativo, texto estruturado, diagramas, imagens e animações ou simulações. Neste documento, optamos por utilizar o texto estruturado para apresentar os cenários. Esse formato utiliza uma linguagem natural semi-estruturada, o que facilita o entendimento de cada cenário e a validação dos requisitos pelo cliente. Esse modelo pode ser observado na Tabela 1 a seguir.

| Elemento   | Descrição                                                                                    |
| ---------- | -------------------------------------------------------------------------------------------- |
| Objetivo   | Finalidade do cenário                                                                        |
| Contexto   | Descrição de pré-condições, local (físico) e tempo                                           |
| Recursos   | Objetos passivos com os quais os atores interagem                                            |
| Ator       | Pessoa ou estrutura organizacional                                                           |
| Episódios  | Ação realizada por um ou vários atores com participação de outros atores utilizando recursos |
| Restrições | Imposição que restrinja um episódio de um cenário                                            |
| Exceção    | Tratamento para uma situação excepcional ou de erro                                          |

<div style="text-align: center">
<p> Tabela 1: Modelo texto estruturado para descrição de cenários.</p>
</div>



## C01: Pesquisar empresa pelo nome

| Elemento   | Descrição                                                                                                                                                        |
| ---------- | ---------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| Objetivo   |- Pesquisar empresa pelo nome|
| Contexto   | - Local: em casa <br> - Tempo: dia <br> - Pré-condições: ter um dispositivo com acesso a internet|
| Recursos   | - Celular <br> - Aplicativo
| Ator       | - Usuário|
| Episódios  | - Usuário clica na barra de pesquisa <br> - Usuário digita o nome da empresa <br> - Usuário seleciona a empresa|
|Restrições  | - Usuário não achar a empresa |
| Exceção    | - Dispositivo sem energia <br> - Falta de internet <br> - Aplicativo travou


## C02: Cadastrar reclamação

| Elemento   | Descrição                                                                                                                                                        |
| ---------- | ---------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| Objetivo   |Cadastrar uma reclamação de uma empresa|
| Contexto   | - Local: em casa <br> - Tempo: dia <br> - Pré-condições: ter um dispositivo com acesso a internet|
| Recursos   | - Celular <br> - Aplicativo
| Ator       | - Usuário|
| Episódios  | - Usuário pesquisa uma empresa <br> - Usuário seleciona a empresa <br> - Usuário clica no botão escrito "QUERO RECLAMAR" <br> - Usuário preenche as informações do cadastro <br> - Usuário clica no botão "Enviar"|
|Restrições  | - Usuário não achar a empresa <br> - Usuário não tem as informações necessárias para o cadastro|
| Exceção    | - Dispositivo sem energia <br> - Falta de internet <br> - Aplicativo travou


## Histórico de Versão
| Versão | Data de execução | Data de revisão |  Descrição            | Autor(es)         | Revisor(es)  |
| :------: | :----------: | :--------: | :--------------------: | :-------------: | :----------: |
| `1.0` | 20/05/2024  | 20/05/2024| Criação dos cenários | [Igor Thiago](https://github.com/Alladin-51), [Rodrigo ](https://github.com/rodrigogontijoo)  | [Júlio Cesar](https://github.com/Julio1099) |


