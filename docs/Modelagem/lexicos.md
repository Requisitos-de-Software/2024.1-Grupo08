# Léxicos

## Introdução

Léxicos são conjuntos de termos específicos usados em uma área particular, como medicina ou programação, para descrever conceitos e trocar informações de maneira precisa. Eles incluem vocabulário técnico e especializado que é essencial para a comunicação eficaz dentro desses contextos específicos, estabelecendo uma linguagem compartilhada entre os profissionais e membros da comunidade. O integrante responsável pela criação dos léxicos deste projeto é [Júlio Cesar](https://github.com/Julio1099).

## Metodologia

Para criar os léxicos, empregamos a metodologia do Léxico Ampliado da Linguagem (LAL)¹, com os conceitos detalhados na Tabela 1, enquanto o modelo adotado está disponível na Tabela 2.

### Tabela 1 - Léxicos do tipo LAL

| Tipo do símbolo | Noção | Impacto |
|-----------------|-------|-------|
| Sujeito | Quem é o sujeito | Ações que executa |
| Verbo | Quem realiza, quando acontece e quais os procedimentos | Quais os reflexos das ações no ambiente e novos estados decorrentes |
| Objeto | Definir o objeto e identificar outros objetos com os quais ele se relaciona | Ações que podem ser aplicadas ao objeto  |
| Estado | O que indica e ações que levaram a esse estado | Identificar outros estados que podem ocorrer a partir do estado que se descreve  |

<font size="3"><p style="text-align: center">Fonte: SAYÃO e CARVALHO<a id="anchor_1" href="#REF1">1</a>.</p></font>

### Tabela 2 - Exemplo de símbolo de um léxico do tipo LAL

| Tipo do Símbolo | Noção     | Impactos   |
|-----------------|-----------|------------|
| **Sujeito**     | Cliente que interage com o sistema de reservas de passagens aéreas; pode ser passageiro frequente, turista ocasional ou agente de viagens  | Cliente faz reserva de voo para uma data específica<br/>Cliente cancela reserva de voo previamente agendada <br/>Cliente faz check-in online para o voo <br/>Cliente solicita reembolso devido a alterações no voo <br/>Cliente atualiza suas informações pessoais no sistema |

<font size="3"><p style="text-align: center">Fonte: SAYÃO e CARVALHO<a id="anchor_1" href="#REF1">1</a>.</p></font>

A tabela 3 mostra o template criado com base nos Léxicos do projeto [Bilheteria Digital](https://github.com/Requisitos-de-Software/2023.1-BilheteriaDigital/blob/main/docs/modelagem/lexicos.md) e que será usado para definir os léxicos deste projeto.

### Tabela 3 - Template Léxicos

| Léxico | Descrição |
|-----|-----------|
| Classificação | Estado/Objeto/Verbo |
| Impacto | Descrição de ações e de seus efeitos |
| Noção | Símbolo. |
| Sinônimos | Dicionário de palavras |

<font size="3"><p style="text-align: center">Fonte: [CÉSAR, Julio. 2024](https://github.com/Julio1099).</p></font>
</figure>

## Léxicos

### L01: Pesquisar Empresa

O usuário busca uma empresa específica dentro do aplicativo.

#### Tabela 4 - Léxico 01:  Pesquisar Empresa (L01)

| L01 | Descrição |
|-----------------|-------|
| Classificação | Verbo |
| Impacto | O usuário busca uma empresa específica dentro do aplicativo |
| Noção | O usuário utiliza a barra de pesquisa para encontrar a empresa desejada <br> O sistema exibe uma lista de empresas correspondentes à pesquisa <br> O usuário seleciona a empresa desejada |
| Sinônimos | Buscar Empresa, Procurar Empresa |

<font size="3"><p style="text-align: center">Fonte: [CÉSAR, Julio. 2024](https://github.com/Julio1099).</p></font>
</figure>

### L02: Abrir Reclamação

O usuário registra uma reclamação contra uma empresa no aplicativo.

#### Tabela 5 - Léxico 02: Abrir Reclamação (L02)

| L02 | Descrição |
|-----------------|-------|
| Classificação | Verbo |
| Impacto | O usuário registra uma reclamação contra uma empresa no aplicativo |
| Noção | O usuário seleciona uma empresa específica <br> O sistema oferece a opção "Quero reclamar" <br> O usuário preenche as configurações necessárias para registrar a reclamação |
| Sinônimos | Registrar Reclamação, Iniciar Reclamação |

<font size="3"><p style="text-align: center">Fonte: [CÉSAR, Julio. 2024](https://github.com/Julio1099).</p></font>
</figure>

### L03: Visualizar Reclamações de Outros Usuários

O usuário visualiza as reclamações registradas por outros usuários no aplicativo.

#### Tabela 6 - Léxico 03: Visualizar Reclamações de Outros Usuários (L03)

| L03 | Descrição |
|-----------------|-------|
| Classificação | Verbo |
| Impacto | O usuário visualiza as reclamações registradas por outros usuários no aplicativo |
| Noção | O usuário seleciona a opção "Reclamações de Outros Usuários" <br> O sistema exibe as últimas reclamações registradas <br> O usuário pode filtrar as reclamações por fornecedor desejado |
| Sinônimos | Ver Reclamações, Visualizar Queixas de Outros Usuários |

<font size="3"><p style="text-align: center">Fonte: [CÉSAR, Julio. 2024](https://github.com/Julio1099).</p></font>
</figure>

### L04: Visualizar Minhas Reclamações

O usuário visualiza as reclamações que ele próprio registrou no aplicativo.

#### Tabela 7 - Léxico 04: Visualizar Minhas Reclamações (L04)

| L04 | Descrição |
|-----------------|-------|
| Classificação | Verbo |
| Impacto | O usuário visualiza as reclamações que ele próprio registrou no aplicativo |
| Noção | O usuário seleciona a opção "Minhas Reclamações" <br> O sistema exibe as reclamações feitas pelo usuário <br> O usuário pode visualizar o andamento das reclamações e interagir com a empresa |
| Sinônimos | Ver Minhas Queixas, Visualizar Minhas Reclamações |

<font size="3"><p style="text-align: center">Fonte: [CÉSAR, Julio. 2024](https://github.com/Julio1099).</p></font>
</figure>

### L05: Visualizar Dados Gerais

O usuário visualiza dados gerais sobre o aplicativo, como total de reclamações finalizadas e total de usuários cadastrados.

#### Tabela 8 - Léxico 05: Visualizar Dados Gerais (L05)

| L05 | Descrição |
|-----------------|-------|
| Classificação | Verbo |
| Impacto | O usuário visualiza dados gerais sobre o aplicativo |
| Noção | O usuário seleciona a opção "Dados Gerais" <br> O sistema exibe informações sobre o aplicativo, coletadas desde 2014 <br> O usuário pode visualizar dados como total de reclamações finalizadas, total de usuários cadastrados e total de empresas cadastradas |
| Sinônimos | Ver Estatísticas, Visualizar Informações Gerais |

<font size="3"><p style="text-align: center">Fonte: [CÉSAR, Julio. 2024](https://github.com/Julio1099).</p></font>
</figure>

### L06: Visualizar Meus Dados

O usuário visualiza seus próprios dados cadastrais no aplicativo, incluindo nome, CPF e data de nascimento.

#### Tabela 9 - Léxico 06: Visualizar Meus Dados (L06)

| L06 | Descrição |
|-----------------|-------|
| Classificação | Verbo |
| Impacto | O usuário visualiza seus próprios dados cadastrais no aplicativo |
| Noção | O usuário acessa o menu e seleciona a opção "Meus Dados" <br> O sistema exibe os dados cadastrais do usuário, incluindo nome, CPF e data de nascimento <br> O usuário pode visualizar também seus dados de endereço e contato |
| Sinônimos | Ver Meu Perfil, Visualizar Dados Pessoais |

<font size="3"><p style="text-align: center">Fonte: [CÉSAR, Julio. 2024](https://github.com/Julio1099).</p></font>
</figure>

### L07: Responder Reclamação

A empresa responde a uma reclamação recebida de um usuário no aplicativo.

#### Tabela 10 - Léxico 07: Responder Reclamação (L07)

| L07 | Descrição |
|-----------------|-------|
| Classificação | Verbo |
| Impacto | A empresa responde a uma reclamação recebida de um usuário no aplicativo |
| Noção | A empresa recebe a reclamação de um usuário <br> O sistema oferece a opção de responder à reclamação |
| Sinônimos | Responder a Queixa, Dar Retorno à Reclamação |

<font size="3"><p style="text-align: center">Fonte: [CÉSAR, Julio. 2024](https://github.com/Julio1099).</p></font>
</figure>

### L08: Avaliar Empresa

O usuário avalia a resposta de uma empresa à reclamação que ele fez.

#### Tabela 11 - Léxico 08: Avaliar Empresa (L08)

| L08 | Descrição |
|-----------------|-------|
| Classificação | Verbo |
| Impacto | O usuário avalia a resposta de uma empresa à reclamação que ele fez |
| Noção | O usuário acessa a seção "Minhas Reclamações" <br> O sistema exibe a opção de avaliar a resposta do fornecedor <br> O usuário pode avaliar a resolução da reclamação, seu grau de satisfação e deixar um comentário |
| Sinônimos | Avaliar Resposta da Empresa, Dar Feedback sobre Resposta |

<font size="3"><p style="text-align: center">Fonte: [CÉSAR, Julio. 2024](https://github.com/Julio1099).</p></font>
</figure>

## Referências Bibliográficas

>SERRANO, Milene. Requisitos – Aula 10. 2017. Apresentação de slides. Disponível em: [https://aprender3.unb.br/pluginfile.php/2523091/mod_resource/content/1/Aula%2010.pdf](https://aprender3.unb.br/pluginfile.php/2523091/mod_resource/content/1/Aula%2010.pdf). Acesso em: 15/05/2024.

> <a id="REF1" href="#anchor_1">1.</a> SAYÃO, Miriam, CARVALHO, Gustavo. Construção do léxico de aplicações. Information and Human Language Technology, 4th Workshop, Ribeirão Preto, 2006. Disponível em: <http://www-di.inf.puc-rio.br/~julio/bnncap3.pdf/>. Acesso em: 15/05/2024.

## Histórico de Versões

| Versão | Data       | Descrição                                    | Autor(es)                                        | Revisor(es)                                      |
| ------ | ---------- | -------------------------------------------- | ------------------------------------------------ | ------------------------------------------------ |
| `1.0`  | 16/05/2024 | Criação dos léxicos.                           | [Júlio Cesar](https://github.com/Julio1099) | |

