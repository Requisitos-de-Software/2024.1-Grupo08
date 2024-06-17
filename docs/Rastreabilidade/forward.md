# Forward From

## Introdução

<!-- A rastreabilidade é a capacidade de descrever e acompanhar a vida de um requisito, desde sua origem, passando por seu desenvolvimento e especificação, até sua posterior implantação e uso. Ela é essencial para garantir que todos os requisitos tenham sido atendidos e para gerenciar mudanças nos requisitos ao longo do ciclo de vida do projeto.

A rastreabilidade é crucial para a gerência por requisitos e para a detecção de conflitos, além de ser essencial para o gerenciamento do desenvolvimento e controle de riscos. Ela ajuda a detectar requisitos não alocados a componentes e a gerenciar as mudanças e a evolução do sistema.

A rastreabilidade pode ser implementada por meio de elos ou ligações entre requisitos inter-relacionados, suas fontes, e os componentes que os implementam. Técnicas comuns incluem o uso de referências cruzadas e matrizes de rastreabilidade, frequentemente suportadas por ferramentas de software. -->

O "forward-from" (para frente, a partir de) é uma aborgadem de pós-rastreabilidade que envolve a coleta de informações de rastreabilidade entre os requisitos e os artefatos gerados nas atividades de desenvolvimento subsequentes.

No contexto da rastreabilidade entre requisitos, o "forward-from" consiste no mapeamento das dependências entre os requisitos. Isso significa identificar se um requisito refina outro requisito, generaliza ou substitui algum requisito anterior. Por exemplo, um requisito pode ser uma evolução de outro requisito existente, incorporando novas funcionalidades ou modificando as existentes. Essa relação de dependência é importante para entender como os requisitos se relacionam entre si e para garantir que todos sejam adequadamente atendidos durante o desenvolvimento do software.


## Metodologia

A metodologia adotada foi o *Meta-modelo de Toranzo*[¹](), que propõe quatro níveis de classificação para as informações rastreadas, sendo eles:

- **Ambiental**: informações oriundas do ambiente em que está inserida a organização e como podem afetar o desenvolvimento do sistema
- **Organizacional**: informações relacionadas a organização (metas, padrões e objetivos) e seus respectivos impactos nos requisitos do sistema
- **Gerecial**: informações que permitem associar requisitos com tarefas, auxiliando na gestão do projeto
- **Desenvolvimento**: informações relacionadas aos artefatos gerados durante o desenvolvimento (diagramas, testes, etc.)

Dentro deste Meta-modelo, o suporte à rastreabilidade identifica diferentes tipos de elos, sendo eles:

- **Satisfação**: indica a classe de origem que depende da satisfação da classe de destino
- **Recurso**: indica a classe de origem que depende de recurso(s) da classe de destino
- **Responsabilidade**: indica a partipação de pessoas sobre os artefatos (responsabilidades e ações)
- **Representação**: representação ou modelagem dos requisitos em outras linguagens
- **Alocado**: classe de origem relacionada a classe de destino, representando subsistema
- **Agregação**: indica composição de elementos

## Mapeamento dos Requisitos

Os requisitos funcionais e não funcionais previmente elicitados foram coletados para formar tabelas. Dessa forma, foi necessário verificar a implementação dos requisitos, ou efetuar a criação dos protótipos caso não tivessem implementados na aplicação. Cada requisito foi analisado por determinado aluno, cobrindo assim todos os requisitos elicitados.

A Tabela 1 apresenta a legenda utilizada para identificar os diferentes tipos de artefatos.

| Legenda | Artefato                  |
| ------- | ------------------------- |
| US      | História de Usuário       |
| ST      | Storytelling              |
| CDU     | Casos de Uso              |
| CEN     | Cenários                  |
| LEX     | Especificação Suplementar |
| INT     | Introspecção              |
| QUE     | Questionário              |
| ADD     | Análise de Documentos     |
| RF      | Requisitos Funcionais     |
| RNF     | Requisitos não Funcionais |

<div>
<p> Tabela 1: Legenda (Fonte: MEISTER, Guilherme. 2024).</p>
</div>

O mapeamento dos requisitos para os artefatos proporciona uma visão abrangente e estruturada do desenvolvimento do software, como é visto a seguir, permitindo que a equipe compreenda as relações entre os elementos e tome decisões embasadas durante todo o processo.

 ID do requisito funcional | Descrição do requisito |
| :-: | :-: |
| Épico | Épico de referência |
| Tema | Tema do Backlog |
| História de Usuário | História de usuário |
| Léxico  | Léxico relacionado |
| Casos de uso | Caso de uso relacionado |
| Cenários | Cenário relacionado |
| Artefatos de elicitação | Artefatos que elicitaram o requisito |

<div>
<p> Tabela 2: Modelo para requisito funcional (Fonte: MEISTER, Guilherme. 2024).</p>
</div>

| ID do requisito não funcional | Descrição do requisito |
| :-: | :-: |
| NFR | Softgoals relacionado |
| Especificação Suplementar | Critério da especificação |                  

<div>
<p> Tabela 3: Modelo para requisito não funcional (Fonte: MEISTER, Guilherme. 2024).</p>
</div>

## Bibliografia

[1] SERRANO, Milene; SERRANO, Maurício. Requisitos - Aula 26. 2019. Acessado em: 12 de junho de 2024

[2] POHL, Klaus; RUPP, Chris. Requirements Engineering Fundamental. Acessado em 12 de junho de 2024

[3] SAYÃO, Miriam; LEITE, Julio. Rastreabilidade de Requisitos. PUC-Rio: Departamento de Informática, ISSN 0103-9741, Rio de Janeiro, 2005. Disponível em: <https://aprender3.unb.br/pluginfile.php/2845099/mod_resource/content/3/05_20_sayao.pdf>. Acesso em: 12 de jun de 2024.

## Histórico de Versões

| <p align="center">Data</p> | <p align="center">Versão</p> | <p align="center">Descrição</p> | <p align="center">Autor(es)</p> | <p align="center">Data de revisão</p> | <p align="center">Revisor(es)</p> |
| :-: | :-: | :-: | :-: | :-: | :-: |
| 12/06/2024 | `1.0` | Criação do artefato | [Guilherme Meister](https://github.com/gmeister18) | 13/06/2024 |  [Henrique Galdino](https://github.com/hgaldino05) |