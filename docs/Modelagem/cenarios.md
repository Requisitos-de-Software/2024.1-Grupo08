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
| Objetivo   | - Pesquisar empresa pelo nome|
| Contexto   | - Local: Aba "Home". <br> - Tempo: Menos de 30 segundos. <br> - Pré-condições: ter um dispositivo com acesso a internet|
| Recursos   | - Celular <br> - Aplicativo
| Ator       | - Usuário|
| Episódios  | - Usuário clica na barra de pesquisa <br> - Usuário digita o nome da empresa <br> - Usuário seleciona a empresa|
|Restrições  | - Usuário não achar a empresa |
| Exceção    | - Dispositivo sem energia <br> - Falta de internet <br> - Aplicativo travou

<div style="text-align: center">
<p>Tabela 2: Cenário 01: Pesquisar empresa pelo nome. (Fonte: THIAGO, Igor. 2024).</p>
</div>

## C02: Cadastrar reclamação

| Elemento   | Descrição                                                                                                                                                        |
| ---------- | ---------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| Objetivo   | - Cadastrar uma reclamação de uma empresa|
| Contexto   | - Local: Aba "Home". <br> - Tempo: Menos de 5 minutos. <br> - Pré-condições: ter um dispositivo com acesso a internet|
| Recursos   | - Celular <br> - Aplicativo
| Ator       | - Usuário|
| Episódios  | - Usuário pesquisa uma empresa <br> - Usuário seleciona a empresa <br> - Usuário clica no botão escrito "QUERO RECLAMAR" <br> - Usuário preenche as informações do cadastro <br> - Usuário clica no botão "Enviar"|
|Restrições  | - Usuário não achar a empresa <br> - Usuário não tem as informações necessárias para o cadastro|
| Exceção    | - Dispositivo sem energia <br> - Falta de internet <br> - Aplicativo travou

<div style="text-align: center">
<p>Tabela 3: Cenário 02: Cadastrar reclamação. (Fonte: THIAGO, Igor. 2024).</p>
</div>

## C03: Visualizar reclamações de outros usuários

| Elemento   | Descrição                                                                                                                                                        |
| ---------- | ---------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| Objetivo   | - Visualizar reclamações de outros usuários|
| Contexto   | - Local: Aba "Visualizar reclamações de outros usuários" <br> - Tempo: Menos de 1 minuto. <br> - Pré-condições: ter um dispositivo com acesso a internet|
| Recursos   | - Celular <br> - Aplicativo
| Ator       | - Usuário|
| Episódios  | - Usuário clica no botão escrito "Visualizar reclamações de outros usuários" <br> - Usuário clica no botão "Filtro" <br> - Usuário digita o nome da empresa que deseja filtrar as reclamações <br> - Usuário seleciona a reclamação que deseja visualizar|
|Restrições  | - Usuário não achar a empresa |
| Exceção    | - Dispositivo sem energia <br> - Falta de internet <br> - Aplicativo travou

<div style="text-align: center">
<p>Tabela 4: Cenário 03: Visualizar reclamações de outros usuários. (Fonte: THIAGO, Igor. 2024).</p>
</div>

## C04: Visualizar minhas reclamações 

| Elemento   | Descrição                                                                                                                                                        |
| ---------- | ---------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| Objetivo   | - Visualizar as reclamações já feitas pelo usuário|
| Contexto   | - Local: Aba "Minhas Reclamações" <br> - Tempo: Menos de 1 minuto. <br> - Pré-condições: ter um dispositivo com acesso a internet|
| Recursos   | - Celular <br> - Aplicativo
| Ator       | - Usuário|
| Episódios  | - Usuário clica no na aba "minhas reclamações" <br> - Usuário seleciona a reclamação que deseja acompanhar o andamento
|Restrições  | - Usuário não ter feito reclamações |
| Exceção    | - Dispositivo sem energia <br> - Falta de internet <br> - Aplicativo travou

<div style="text-align: center">
<p>Tabela 5: Cenário 04: Visualizar minhas reclamações. (Fonte: THIAGO, Igor. 2024).</p>
</div>

## C05: Visualizar Dados Gerais

| Elemento   | Descrição                                                                                                                                                        |
| ---------- | ---------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| Objetivo   | - Visualizar dados gerais do aplicativo (Total de reclamações finalizadas, Total de Usuários Cadastrados e Total de Empresas Cadastradas). |
| Contexto   | - Local: Aba "Home". <br> - Tempo: Menos de 30 segundos.<br> - Pré-condições: Usuário estar logado. |
| Recursos   | - Internet. <br> - Smartphone com a Consumidor.gov instalado. |
| Ator       | - Usuário do Consumidor.gov.|
| Episódios  | - O usuário acessa a seção "Home". <br> - Usuário clica em "Dados Gerais".  |
| Restrições | - O aplicativo deve as estatíscas.|
| Exceção    | - Dispositivo sem energia. <br> - Falha de conexão à internet. <br> - Aplicativo travou.

<div style="text-align: center">
<p>Tabela 6: Cenário 05: Visualizar Dados Gerais. (Fonte: GONTIJO, Rodrigo. 2024).</p>
</div>

## C06: Visualizar meus Dados

| Elemento   | Descrição                                                                                                                                                        |
| ---------- | ---------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| Objetivo   | - Visualizar os dados do usuário cadastrado|
| Contexto   | - Local: Aba "Menu" <br> - Tempo: Menos de 1 minuto.  <br> - Pré-condições: Usuário estar logado.|
| Recursos   | - Internet. <br> - Smartphone com a Consumidor.gov instalado. |
| Ator       | - Usuário do Consumidor.gov.|
| Episódios  | - Usuário acessa a seção "Menu" <br> O usuário clica em "Meus Dados". |
| Restrições | - Os dados devem estar cadastrados via gov.br |
| Exceção    | - Dispositivo sem energia. <br> - Falha de conexão à internet. <br> - Aplicativo travou.

<div style="text-align: center">
<p>Tabela 7: Cenário 06: Visualizar meus Dados. (Fonte: GONTIJO, Rodrigo. 2024).</p>
</div>

## C07: Responder Reclamação

| Elemento   | Descrição                                                                                                                                                        |
| ---------- | ---------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| Objetivo   | - Responder uma reclamação feita por um usuário. |
| Contexto   | - Local: Plataforma consumidor.gov para empresas <br> - Tempo: Menos de 10 minutos. <br> - Pré-condições: Empresa estar logada. <br> Um usuário ter feito uma reclamação sobre sua empresa.|
| Recursos   | - Internet. <br> - Smartphone com a Consumidor.gov instalado. |
| Ator       | - Empresa.|
| Episódios  | - A empresa seleciona uma reclamação. <br> - A empresa responde a reclamação.|
| Restrições | - A reclamação nao deve estar finalizada ou avaliada. |
| Exceção    | - Dispositivo sem energia. <br> - Falha de conexão à internet. <br> - Aplicativo travou.

<div style="text-align: center">
<p>Tabela 8: Cenário 07: Responder Reclamação. (Fonte: GONTIJO, Rodrigo. 2024).</p>
</div>

## C08: Avaliar Empresa

| Elemento   | Descrição                                                                                                                                                        |
| ---------- | ---------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| Objetivo   | - Avaliar uma reclamação concluída de uma empresa. |
| Contexto   | - Local: Aba "Minhas Reclamações". <br> - Tempo: Menos de 5 minutos.<br> - Pré-condições: Usuário estar logado. <br> Usuário deve ter feito uma reclamação e ter sido respondido.|
| Recursos   | - Internet. <br> - Smartphone com a Consumidor.gov instalado. |
| Ator       | - Usuário do Consumidor.gov.|
| Episódios  | - O usuário acessa a seção "Minhas Reclamações". <br> O usuário escolhe uma reclamação. <br> O usuário escolhe avaliar resposta.|
| Restrições | - A reclamação deve estar finalizada. |
| Exceção    | - Dispositivo sem energia. <br> - Falha de conexão à internet. <br> - Aplicativo travou.

<div style="text-align: center">
<p>Tabela 9: Cenário 08: Avaliar Empresa. (Fonte: GONTIJO, Rodrigo. 2024).</p>
</div>


## Bibliografia

> [1] CENÁRIOS: Rastreamento de Cenários. [S. l.]. Disponível em: <http://www-di.inf.puc-rio.br/~julio/bnncap3.pdf>.


## Histórico de Versão
| Versão | Data de execução | Data de revisão |  Descrição            | Autor(es)         | Revisor(es)  |
| :------: | :----------: | :--------: | :--------------------: | :-------------: | :----------: |
| `1.0` | 20/05/2024  | 20/05/2024| Criação dos cenários | [Igor Thiago](https://github.com/Alladin-51), [Rodrigo ](https://github.com/rodrigogontijoo)  | [Júlio Cesar](https://github.com/Julio1099) |


