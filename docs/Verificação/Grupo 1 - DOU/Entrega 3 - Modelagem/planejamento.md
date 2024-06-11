# Planejamento da Verificação

## Introdução

A verificação é uma etapa crucial no desenvolvimento de projetos, visando analisar e avaliar os artefatos desenvolvidos dentro dos mesmos, observando se estão de acordo com o modelo esperado [¹](https://requisitos-de-software.github.io/2024.1-Consumidor.gov/Verificação/Grupo%201%20-%20DOU/Entrega%203%20-%20Modelagem/planejamento/#anchor_1). Este artefato contém o planejamento realizado a verificação dos artefatos para entrega 3 do [grupo 1 (Diário Oficial da União)](https://requisitos-de-software.github.io/2024.1-DiarioOficialdaUniao/), sendo eles [Cenários](https://requisitos-de-software.github.io/2024.1-DiarioOficialdaUniao/modelagem/cenarios/), [Léxicos](https://requisitos-de-software.github.io/2024.1-DiarioOficialdaUniao/modelagem/lexicos/), [Casos de Uso](https://requisitos-de-software.github.io/2024.1-DiarioOficialdaUniao/modelagem/useCase/) e [Especificação Suplementar](https://requisitos-de-software.github.io/2024.1-DiarioOficialdaUniao/modelagem/especificacao/).

## Objetivos

O objetivo é analisar e avaliar os artefatos feitos para a entrega 3, vendo se os conceitos ministrados ao decorrer da disciplina foram corretamente aplicados no desenvolvimento de cada um deles.

## Metodologia
 Segundo Fagan[²](https://requisitos-de-software.github.io/2024.1-Consumidor.gov/Verificação/Grupo%201%20-%20DOU/Entrega%203%20-%20Modelagem/planejamento/#anchor_2) um método de inspeção estabelece um processo com cinco passos, sendo eles:

- **Visão Geral**
- **Preparação**
- **Inspeção**
- **Refatoramento**
- **Monitoramento e Aprovação**

A metodologia utilizada segue até a **Inspeção**, cujo objetivo é averiguar se o modelo de requisitos está de acordo com o esperado e com a sua notação, verificando se existem defeitos no mesmo e quais correções/melhorias podem ser aplicadas durante revisões.




## Objetos de Verificação

- [Léxicos](https://requisitos-de-software.github.io/2024.1-DiarioOficialdaUniao/modelagem/lexicos/) - Versão ***1.4*** (17/05/2024)

## Checklists

### Checklist de Cenários

| ID | Descrição | Verificação | Observação 
| :--: | :-----: | :---------: | :--------: |
| 5 | O cenário possui: título, metas/objetivos, contexto, ator(es), recursos, exceções, restrições e episódios? | SIM | - | 
| 6 | Os títulos são auto-explicativos? | SIM | - | 
| 7 | O objetivo do cenário condiz com seu título? | SIM | - | 
| 8 | O contexto descreve o estado inicial do cenário? | SIM | - | 
| 9 | Os episódios seguem uma ordem lógica para atingir o objetivo? | SIM | - | 
| 10 | As situações de exceção são abordadas? | SIM | - |  
| 11 | Os passos do cenário são descritos? | SIM | - |  
| 12 | Os recursos necessários são explicitados?  | SIM | - |  
| 13 | Os atores envolvidos em cada cenário são identificados?  | SIM | - |  


<div align="center">
<figcaption align="center">Tabela 01: Checklist (Autor: Meister, Guilherme)</figcaption>
</div>
<br/>

### Checklist de Léxicos

| ID | Descrição |
| :--: | :-----: |
| 1 | O artefato apresenta as especificações dos léxicos? |
| 2 | O artefato apresenta relacionamento entre os léxicos? |
| 3 | O relacionamento entre os léxicos apresenta hiperlinks? |
| 4 | Os léxicos apresentados no artefato seguem a estrutura de dicionário (verbo, objeto, estado)? |
| 5 | Os léxicos apresentados no artefato apresentam *classificação*, *impacto*, *noção* e *sinônimos*? |
| 6 | Os léxicos apresentam noção e impacto corretamente? |
| 7 | Os léxicos estão classificados corretamente? | INCOMPLETO | O [Léxico 06](https://requisitos-de-software.github.io/2024.1-DiarioOficialdaUniao/modelagem/lexicos/#l06-configuracao-de-notificacoes) está classificado como *objeto* |
| 8 | Cada léxico apresenta zero ou mais sinônimos? |
| 9 | Cada léxico apresenta uma ou mais noções? |
| 10 | Cada léxico apresenta um ou mais impactos? |
| 11 | A circularidade foi aplicada entre os léxicos? |

<div align="center">
<figcaption align="center">Tabela 02: Checklist de léxicos (Autor: Henrique Galdino)</figcaption>
</div>
<br/>

### Checklist de Casos de Uso

| ID | Descrição |
| :--: | :-----: |
| 1 | O caso de uso desenvolvido corresponde a uma funcionalidade completa que agrega algum valor? |
| 2 | Os verbos são usados ​​no infinitivo em vez de substantivos? |
| 3 | Existem relações de “extend”, “generalization” e “include”? |
| 4 | O caso de uso reflete o usuário e suas interações com o sistema? |
| 5 | O usuário é identificado por um nome, como cliente, funcionário, aluno, etc.? |
| 6 | Os casos de uso representam requisitos funcionais? |
| 7 | Alguma técnica específica foi usada para desenvolver os casos de uso? |
| 8 | Os elementos de atores, sistema e objetivos estão presentes no caso de uso? |
| 9 | Existem fluxos principais, alternativos e de exceção? |
| 10 | Cada especificação de caso de uso contém apenas um fluxo principal? |
| 11 | Os fluxos principais demonstram como o usuário usaria principalmente a funcionalidade? |
| 12 | Os fluxos alternativos apresentam cenários alternativos ao fluxo principal? |
| 13 | Os fluxos de exceção mostram como o sistema reagirá a situações inesperadas? |

<div align="center">
<figcaption align="center">Tabela 03: Checklist de Casos de Uso (Autor: Júlio Cesar)</figcaption>
</div>
<br/>

### Checklist de Especificação Suplementar

| ID | Descrição | 
|:-:|:---:|
| 1 | O documento é orientado pelo padrão FURPS? |
| 2 | O documento aborda sobre a estética e o design na Usabilidade? | 
| 3 | O documento aborda e especifica sobre a facilidade de memorização na usabilidade? | 
| 4 | O documento aborda e especifica sobre a eficiência na usabilidade? |
| 5 | O documento aborda e especifica sobre a Satisfação na Usabilidade? | 
| 6 | O documento aborda e especifica sobre a disponibilidade na Confiabilidade? | 
| 7 | O documento aborda e especifica sobre a Segurança a falhas na Confiabilidade? | 
| 8 | O documento aborda e especifica sobre a segurança no armazenamento de dados na confiabilidade? | 
| 9 | O documento aborda e especifica a maturidade na Confiabilidade? | 
| 10 | O documento aborda e especifica a rapidez na resposta no Desempenho? | 
| 11 | O documento aborda e especifica o Armazenamento no Desempenho? | 
| 12 | O documento aborda e especifica sobre a compatibilidade na Suportabilidade? | **Incompleto** |  O documento fala sobre compatibilidade porém não na parte de suportabilidade |
| 13 | O documento aborda e especifica sobre a escalabilidade na Suportabilidade? |
| 14 | O documento aborda e especifica sobre o termo de uso nos Requisitos de licenciamento? | 
| 15 | O documento especifica em quais plataformas o aplicativo pode ser executado? | 

<div align="center">
<figcaption align="center">Tabela 03: Checklist (Autor: Igor Thiago)</figcaption>
</div>
<br/>

## Referências Bibliográficas

> <a id="1" href="#anchor_1">1.</a> SERRANO, et al. Requisitos - Aula 23. Disponível em: h<https://aprender3.unb.br/pluginfile.php/2845073/mod_resource/content/2/Requisitos%20-%20Aula%20023.pdf>. Acesso em: 06/06/2024.

> <a id="2" href="#anchor_2">1.</a> SERRANO, et al. RE - Aula 20 - Materiasi.zip. Disponível em: h<https://aprender3.unb.br/mod/resource/view.php?id=1218906>. Acesso em: 06/06/2024.

## Histórico de Versão

| Versão | Data de execução | Data de revisão |  Descrição                          | Autor(es)                                           | Revisor(es)                                           |
| :----: | :--------------: | :-------------: | :---------------------------------: | :-------------------------------------------------: | :---------------------------------------------------: |
| 1.0    | 06/06/2024       | 06/06/2024      | Criação do planejamento da verificação entrega 3   | [Henrique Galdino](https://github.com/hgaldino05)   | [Júlio César](https://github.com/Julio1099)         |

<div align="center">
<figcaption align="center">Tabela 05: Histórico de versões (Autor: Henrique Galdino)</figcaption>
</div>
<br/>
