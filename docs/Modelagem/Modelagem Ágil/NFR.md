# NFR Framework

## Introdução
Segundo Silva[¹](https://requisitos-de-software.github.io/2024.1-Consumidor.gov/Modelagem/Modelagem%20%C3%81gil/NFR/#referencias-bibliograficas),o NFR Framework é um framework de modelagem de requisitos, mais especificamente Requisitos Não-Funcionais, que utiliza das **Softgoals** (objetivos que não possui uma clara definição nem critérios de satisfação precisos) para auxiliar desenvolvedores na implementação de soluções personalizadas, com base nas características do sistema. 

Os softgoals são utilizados para representar Requisitos Não-Funcionais e podem estar inter-relacionados, expressando a influência de um softgoal em outro.

### Tipos de softgoals

Existem três tipos de softgoals, descritos a seguir, cujas representações podem ser vistas na Figura 1, retirada da dissertação de mestrado de Reinaldo Antônio da Silva: NFR4ES: Um Catálogo de Requisitos Não-Funcionais para Sistemas Embarcados [1]. Essa figura também servirá como legenda para os NFRs apresentados neste documento.

1. **Softgoals NFR**: Representam os Requisitos Não-Funcionais e podem ser organizados hierarquicamente no desenvolvimento do projeto.

2. **Softgoals de Operacionalização**: Representam as soluções de implementação para atender aos softgoals NFR ou outros softgoals de operacionalização. Incluem operações, processos, estruturas de dados e restrições no sistema para satisfazer as necessidades indicadas pelos softgoals.

3. **Softgoals de Afirmação**: Consideram as características do domínio, como prioridades e carga de trabalho, no processo de tomada de decisão. Servem como justificativa para apoiar ou negar a priorização e seleção de componentes, facilitando a revisão, a justificação e a melhoria do sistema, bem como o rastreamento das decisões de desenvolvimento.

<div align="center">
<font size="3"><p style="text-align: center"><b>Figura 1:</b> Representação dos tipos de softgoal.</p></font>

<img src="https://github.com/Requisitos-de-Software/2024.1-Consumidor.gov/blob/main/docs/assets/nfr/nfr-tipos.png?raw=true" style="width: 85%;">

<font size="3"><p style="text-align: center"><b>Fonte:</b> (SILVA, 2014).</a></p></font>
</div>

O processo de avaliação determina o nível de cumprimento dos requisitos não funcionais através de um conjunto de decisões. Em outras palavras, o procedimento de avaliação verifica se cada softgoal ou interdependência no SIG foi adequadamente atendido. Isso é feito atribuindo rótulos aos softgoals, sendo que os rótulos possíveis incluem "satisfeito", "parcialmente satisfeito", "não atendido", "parcialmente não atendido", "conflitante" e "indeterminado". 
A figura 2 ilustra um exemplo de cada rótulo, conforme apresentado no artigo de Reinaldo Antônio da Silva[¹](https://requisitos-de-software.github.io/2024.1-Consumidor.gov/Modelagem/Modelagem%20%C3%81gil/NFR/#referencias-bibliograficas). Essa figura também servirá como legenda para os NFRs que serão discutidos neste documento.

<div align="center">
<font size="3"><p style="text-align: center"><b>Figura 2:</b> Rótulos da propagação de impactos.</p></font>

<img src="https://github.com/Requisitos-de-Software/2024.1-Consumidor.gov/blob/main/docs/assets/nfr/nfr-impactos.png?raw=true" style="width: 85%;">

<font size="3"><p style="text-align: center"><b>Fonte:</b> (SILVA, 2014).</a></p></font>
</div>

## Metodologia

Neste documento, descreveremos 7 Requisitos Não Funcionais (NFRs) derivados do nosso documento de especificação suplementar, o qual se fundamentou no modelo FURPS+. Cada membro da equipe foi responsável por definir um NFR dentro de uma categoria do modelo FURPS+.

Para cada categoria, elaboramos um SIG (Softgoal Interdependency Graph), um diagrama que ilustra a propagação de impactos, e um cartão de especificação contendo informações detalhadas sobre o NFR, como sua descrição, categoria, possíveis conflitos, origem, critérios e outras informações relevantes.

## NFR

### NFR01 - Usabilidade

Usabilidade se refere à facilidade e eficácia com que um usuário pode interagir com um sistema, produto ou serviço para alcançar seus objetivos de forma eficiente e satisfatória.

#### Softgoal Interdependency Graph

O Softgoal Interdependency Graph do softgoal "Usabilidade" pode ser visto na figura X.

<div align="center">
<font size="3"><p style="text-align: center"><b>Figura X:</b> Softgoal Interdependency Graph do softgoal "Usabilidade".</p></font>

<img src="https://github.com/Requisitos-de-Software/2024.1-Consumidor.gov/blob/main/docs/assets/nfr/usabilidade.png?raw=true" style="width: 95%;">

<font size="3"><p style="text-align: center"><b>Autor:</b> CÉSAR, Júlio. 2024</p></font>
</div>

#### Propagação de Impactos

A propagação de impactos do softgoal "Usabilidade" pode ser vista na figura X.

<div align="center">
<font size="3"><p style="text-align: center"><b>Figura X:</b> Propagação de impactos do softgoal "Usabilidade"</p></font>

<img src="https://github.com/Requisitos-de-Software/2024.1-Consumidor.gov/blob/main/docs/assets/nfr/impacto-usabilidade.png?raw=true" style="width: 85%;">

<font size="3"><p style="text-align: center"><b>Fonte:</b> CÉSAR, Júlio. 2024</p></font>
</div>

#### Cartão de Especificação

Na tabela 1, temos o cartão de especificação do softgoal "Usabilidade".

<div align="center">
<p><b>Tabela 1:</b> Cartão de Especificação do Softgoal Usabilidade</p>
<table>
  <tr>
    <th>Info</th>
    <th>Detalhes</th>
  </tr>
  <tr>
    <td>ID NFR</td>
    <td>NFR01</td>
  </tr>
  <tr>
    <td>Classificação</td>
    <td>Usabilidade</td>
  </tr>
  <tr>
    <td>Descrição</td>
    <td>O requisito "Usabilidade" trata das características que permitem uma boa utilização do sistema e suas funcionalidades.</td>
  </tr>
  <tr>
    <td>Justificativa</td>
    <td>Ao apresentar um bom nível de usabilidade, o sistema permite que seus usuários desfrutem de suas funcionalidades sem problemas, garantindo uma boa experiência de uso para os mesmos.</td>
  </tr>
  <tr>
    <td>Origem</td>
    <td><a href="https://requisitos-de-software.github.io/2024.1-Consumidor.gov/Modelagem/especsuplementar/">Especificação suplementar</a> e <a href="https://requisitos-de-software.github.io/2024.1-Consumidor.gov/Elicitação/requisitos-elicitados/">requisitos elicitados</a></td>
</td>
  </tr>
  <tr>
    <td>Dependências</td>
    <td>Não foram identificadas dependências</td>
  </tr>
  <tr>
    <td>Prioridade</td>
    <td>ALTA</td>
  </tr>
  <tr>
    <td>Conflitos</td>
    <td>Não foram identificados conflitos.</td>
  </tr>
  <tr>
    <td>História</td>
    <td>26/05/2024</td>
  </tr>
</table>
<font size="3"><p style="text-align: center">Autor: CÉSAR, Julio. 2024</p></font>
</figure>
</div>

### NFR02 - Confiabilidade 

Confiabilidade se refere à capacidade de um sistema, produto ou serviço realizar suas funções de forma consistente e previsível ao longo do tempo, sob condições específicas.

#### Softgoal Interdependency Graph

O Softgoal Interdependency Graph do softgoal "Confiabilidade" pode ser visto na figura X.

<div align="center">
<font size="3"><p style="text-align: center"><b>Figura X:</b> Softgoal Interdependency Graph do softgoal "Confiabilidade".</p></font>

<img src="https://github.com/Requisitos-de-Software/2024.1-Consumidor.gov/blob/main/docs/assets/nfr/confiabilidade.png?raw=true" style="width: 95%;">

<font size="3"><p style="text-align: center"><b>Autor:</b> CÉSAR, Júlio. 2024</p></font>
</div>

#### Propagação de Impactos

A propagação de impactos do softgoal "Confiabilidade" pode ser vista na figura X.

<div align="center">
<font size="3"><p style="text-align: center"><b>Figura X:</b> Propagação de impactos do softgoal "Confiabilidade"</p></font>

<img src="https://github.com/Requisitos-de-Software/2024.1-Consumidor.gov/blob/main/docs/assets/nfr/impacto-confiabilidade.png?raw=true" style="width: 95%;" style="width: 85%;">

<font size="3"><p style="text-align: center"><b>Autor:</b> CÉSAR, Júlio. 2024</p></font>
</div>

#### Cartão de Especificação
Na tabela 2, temos o cartão de especificação do softgoal "Confiabilidade".

<div align="center">
<p><b>Tabela 2:</b> Cartão de Especificação do Softgoal "Confiabilidade"</p>
<table>
  <tr>
    <th>Info</th>
    <th>Detalhes</th>
  </tr>
  <tr>
    <td>ID NFR</td>
    <td>NFR02</td>
  </tr>
  <tr>
    <td>Classificação</td>
    <td>Confiabilidade</td>
  </tr>
  <tr>
    <td>Descrição</td>
    <td>O requisito "Confiabilidade" diz respeito a capacidade do sistema de manter sua estabilidade e funcionamento, garantindo sua utilização por parte do usuário.</td>
  </tr>
  <tr>
    <td>Justificativa</td>
    <td>Um sistema confiável é imprescindível para que o usuário apresente interesse em utilizar o mesmo, garantindo que seu funcionamento sempre esteja de acordo com o planejado</td>
  </tr>
  <tr>
    <td>Origem</td>
    <td><a href="https://requisitos-de-software.github.io/2024.1-Consumidor.gov/Modelagem/especsuplementar/">Especificação suplementar</a> e <a href="https://requisitos-de-software.github.io/2024.1-Consumidor.gov/Elicitação/requisitos-elicitados/">requisitos elicitados</a></td>
  </tr>
  <tr>
    <td>Dependências</td>
    <td>Não foram identificadas dependências</td>
  </tr>
  <tr>
    <td>Prioridade</td>
    <td>ALTA</td>
  </tr>
  <tr>
    <td>Conflitos</td>
    <td>Não foi identificado nenhum conflito</td>
  </tr>
  <tr>
    <td>História</td>
    <td>26/05/2024</td>
  </tr>
</table>
</table>
<font size="3"><p style="text-align: center">Autor: CÉSAR, Julio. 2024</p></font>
</figure>
</div>

### NFR03 - Performance

Performance se refere ao desempenho ou à capacidade de um sistema, produto ou serviço em cumprir suas funções de forma eficiente e rápida, atendendo às expectativas de desempenho dos usuários.

#### Softgoal Interdependency Graph

O Softgoal Interdependency Graph do softgoal "Performance" pode ser visto na figura X.

<div align="center">
<font size="3"><p style="text-align: center"><b>Figura X:</b> Softgoal Interdependency Graph do softgoal "Performance".</p></font>

<img src="https://github.com/Requisitos-de-Software/2024.1-Consumidor.gov/blob/main/docs/assets/nfr/performance.png?raw=true" style="width: 85%;">

<font size="3"><p style="text-align: center"><b>Autor:</b> CÉSAR, Júlio. 2024</p></font>
</div>

#### Propagação de Impactos

A propagação de impactos do softgoal "Performance" pode ser vista na figura X.

<div align="center">
<font size="3"><p style="text-align: center"><b>Figura X:</b> Propagação de impactos do softgoal "Performance"</p></font>

<img src="https://github.com/Requisitos-de-Software/2024.1-Consumidor.gov/blob/main/docs/assets/nfr/impacto-performance.png?raw=true" style="width: 85%;" style="width: 85%;">

<font size="3"><p style="text-align: center"><b>Autor:</b> CÉSAR, Júlio. 2024</p></font>
</div>

#### Cartão de Especificação

Na tabela 3, temos o cartão de especificação do softgoal "Performance".

<div align="center">
<p><b>Tabela 3:</b> Cartão de Especificação do Softgoal "Performance"</p>
<table>
  <tr>
    <th>Info</th>
    <th>Detalhes</th>
  </tr>
  <tr>
    <td>ID NFR</td>
    <td>NFR03</td>
  </tr>
  <tr>
    <td>Classificação</td>
    <td>Performance</td>
  </tr>
  <tr>
    <td>Descrição</td>
    <td>Performance diz ao desempenho do sistema e a capacidade de resposta do mesmo.</td>
  </tr>
  <tr>
    <td>Justificativa</td>
    <td>Um sistema com boa performance ajuda a melhorar a experiência do usuário, que pode realizar suas ações com maior eficiência e eficácia</td>
  </tr>
  <tr>
    <td>Origem</td>
    <td><a href="https://requisitos-de-software.github.io/2024.1-Consumidor.gov/Modelagem/especsuplementar/">Especificação suplementar</a> e <a href="https://requisitos-de-software.github.io/2024.1-Consumidor.gov/Elicitação/requisitos-elicitados/">requisitos elicitados</a></td>
  </tr>
  <tr>
    <td>Dependências</td>
    <td>Não foram identificadas dependências</td>
  </tr>
  <tr>
    <td>Prioridade</td>
    <td>ALTA</td>
  </tr>
  <tr>
    <td>Conflitos</td>
    <td>Não foram identificados conflitos.</td>
  </tr>
  <tr>
    <td>História</td>
    <td>26/05/2024</td>
  </tr>
</table>
<font size="3"><p style="text-align: center">Autor: CÉSAR, Julio. 2024</p></font>
</figure>
</div>

### NFR04 - Suportabilidade

Suportabilidade se refere à capacidade de um sistema, produto ou serviço de ser mantido, atualizado e adaptado ao longo do tempo, garantindo sua operacionalidade contínua e a capacidade de lidar com mudanças no ambiente ou nos requisitos do usuário.

#### Softgoal Interdependency Graph

O Softgoal Interdependency Graph do softgoal "Performance" pode ser visto na figura X.

<div align="center">
<font size="3"><p style="text-align: center"><b>Figura X:</b> Softgoal Interdependency Graph do softgoal "Performance".</p></font>

<img src="https://github.com/Requisitos-de-Software/2024.1-Consumidor.gov/blob/main/docs/assets/nfr/portabilidade.png?raw=true" style="width: 85%;">

<font size="3"><p style="text-align: center"><b>Autor:</b> CÉSAR, Júlio. 2024</p></font>
</div>

#### Propagação de Impactos

A propagação de impactos do softgoal "Performance" pode ser vista na figura X.

<div align="center">
<font size="3"><p style="text-align: center"><b>Figura X:</b> Propagação de impactos do softgoal "Performance"</p></font>

<img src="https://github.com/Requisitos-de-Software/2024.1-Consumidor.gov/blob/main/docs/assets/nfr/impacto-portabilidade.png?raw=true" style="width: 85%;" style="width: 85%;">

<font size="3"><p style="text-align: center"><b>Autor:</b> GALDINO, Henrique. 2024</p></font>
</div>

#### Cartão de Especificação

Na tabela 4, temos o cartão de especificação do softgoal "Suporte".

<div align="center">
<p><b>Tabela 4:</b> Cartão de Especificação do Softgoal "Suporte"</p>
<table>
  <tr>
    <th>Info</th>
    <th>Detalhes</th>
  </tr>
  <tr>
    <td>ID NFR</td>
    <td>NFR04</td>
  </tr>
  <tr>
    <td>Classificação</td>
    <td>Suportabilidade</td>
  </tr>
  <tr>
    <td>Descrição</td>
    <td>A suportabilidade diz respeito a manutenção, configuração e portabilidade do sistema.</td>
  </tr>
  <tr>
    <td>Justificativa</td>
    <td>Para a preservação do sistema, é imprescindível que a manutenção, configuração e portabilidade do mesmo esteja de acordo com o planejado, evitando que o usuário experiencie erros e falhas que possam prejudicar sua experiência de uso</td>
  </tr>
  <tr>
    <td>Origem</td>
    <td><a href="https://requisitos-de-software.github.io/2024.1-Consumidor.gov/Modelagem/especsuplementar/">Especificação suplementar</a> e <a href="https://requisitos-de-software.github.io/2024.1-Consumidor.gov/Elicitação/requisitos-elicitados/">requisitos elicitados</a></td>
  </tr>
  <tr>
    <td>Dependências</td>
    <td>Não foram identificadas restrições ou dependências específicas, mas a atualização da documentação deve ser planejada e coordenada com as versões do aplicativo.</td>
  </tr>
  <tr>
    <td>Prioridade</td>
    <td>O requisito de "Suporte" é de alta prioridade, para garantir a funcionalidade contínua e a relevância do sistema ao longo do tempo.</td>
  </tr>
  <tr>
    <td>Conflitos</td>
    <td>Não foi identificado nenhum conflito.</td>
  </tr>
  <tr>
    <td>História</td>
    <td>26/05/2024</td>
  </tr>
</table>
<font size="3"><p style="text-align: center">Autor: CÉSAR, Julio. 2024</p></font>
</figure>
</div>

### NFR05 - Implementação

Os requisitos de implementação são aqueles que representam os requisitos relacionados a implementação e construção do sistema.

#### Softgoal Interdependency Graph

O Softgoal Interdependency Graph do softgoal "Implementação" pode ser visto na figura X.

<div align="center">
<font size="3"><p style="text-align: center"><b>Figura X:</b> Softgoal Interdependency Graph do softgoal "Implementação".</p></font>

<img src="https://github.com/Requisitos-de-Software/2024.1-Consumidor.gov/blob/main/docs/assets/nfr/implementacao.png?raw=true" style="width: 85%;">

<font size="3"><p style="text-align: center"><b>Autor:</b> CÉSAR, Júlio. 2024</p></font>
</div>

#### Propagação de Impactos

A propagação de impactos do softgoal "Implementação" pode ser vista na figura X.

<div align="center">
<font size="3"><p style="text-align: center"><b>Figura X:</b> Propagação de impactos do softgoal "Implementação"</p></font>

<img src="https://github.com/Requisitos-de-Software/2024.1-Consumidor.gov/blob/main/docs/assets/nfr/impacto-implementacao.png?raw=true" style="width: 85%;">

<font size="3"><p style="text-align: center"><b>Autor:</b> CÉSAR, Júlio. 2024</p></font>
</div>

#### Cartão de Especificação

Na tabela 5, temos o cartão de especificação do Softgoal "Implementação".

<div align="center">
<p><b>Tabela 5:</b> Cartão de Especificação do Softgoal "Implementação"</p>
<table>
  <tr>
    <th>Info</th>
    <th>Detalhes</th>
  </tr>
  <tr>
    <td>ID NFR</td>
    <td>RNF05</td>
  </tr>
  <tr>
    <td>Classificação</td>
    <td>Implementação</td>
  </tr>
  <tr>
    <td>Descrição</td>
    <td>Implementação diz respeito a construção e execução do sistema, ou seja, aquilo que é necessário para que o sistema seja executado (implementado) em um dispositivo</td>
  </tr>
  <tr>
    <td>Justificativa</td>
    <td>Informar os "pré-requisitos" do sistema é fundamental para que os usuários possam checar se possuem dispositivos compatíveis ou se o armazenamento e permissões estão de acordo com o necessário para o aplicativo</td>
  </tr>
  <tr>
    <td>Origem do Requisito</td>
    <td><a href="https://requisitos-de-software.github.io/2024.1-Consumidor.gov/Modelagem/especsuplementar/">Especificação suplementar</a> e <a href="https://requisitos-de-software.github.io/2024.1-Consumidor.gov/Elicitação/requisitos-elicitados/">requisitos elicitados</a></td>
  </tr>
  <tr>
    <td>Dependências</td>
    <td>Não foram identificadas dependências</td>
  </tr>
  <tr>
    <td>Prioridade</td>
    <td>ALTA</td>
  </tr>
  <tr>
    <td>Conflitos</td>
    <td>Não foi identificado nenhum conflito.</td>
  </tr>
  <tr>
    <td>História</td>
    <td>26/05/2024</td>
  </tr>
</table>
<font size="3"><p style="text-align: center">Autor: CÉSAR, Julio. 2024</p></font>
</figure>
</div>

### NFR06 - Documentação

Documentação se refere a documentação do sistema do sistema em si, ou seja, arquivos e registros inclusos que explicam o aplicativo, seu funcionamento e seus termos.

#### Softgoal Interdependency Graph

O Softgoal Interdependency Graph do softgoal "Documentação" pode ser visto na figura X.

<div align="center">
<font size="3"><p style="text-align: center"><b>Figura X:</b> Softgoal Interdependency Graph do softgoal "Documentação".</p></font>

<img src="https://github.com/Requisitos-de-Software/2024.1-Consumidor.gov/blob/main/docs/assets/nfr/documentacao.png?raw=true" style="width: 85%;">

<font size="3"><p style="text-align: center"><b>Autor:</b> CÉSAR, Júlio. 2024</p></font>
</div>

#### Propagação de Impactos

A propagação de impactos do softgoal "Implementação" pode ser vista na figura X.

<div align="center">
<font size="3"><p style="text-align: center"><b>Figura X:</b> Propagação de impactos do softgoal "Documentação"</p></font>

<img src="https://github.com/Requisitos-de-Software/2024.1-Consumidor.gov/blob/main/docs/assets/nfr/impacto-documentacao.png?raw=true" style="width: 85%;" style="width: 85%;">

<font size="3"><p style="text-align: center"><b>Autor:</b> CÉSAR, Júlio. 2024</p></font>
</div>

#### Cartão de Especificação

Na tabela 6, temos o cartão de especificação do Softgoal "Documentação".

<div align="center">
<p><b>Tabela 6:</b> Cartão de Especificação do Softgoal "Documentação"</p>

<table>
  <tr>
    <th>Info</th>
    <th>Detalhes</th>
  </tr>
  <tr>
    <td>ID NFR</td>
    <td>NFR06</td>
  </tr>
  <tr>
    <td>Classificação</td>
    <td>Documentação</td>
  </tr>
  <tr>
    <td>Descrição</td>
    <td>Documentação diz respeito aos documentos e arquivos presentes e/ou disponibilizados pela aplicação para maior conhecimento do mesmo por parte de seus usuários</td>
  </tr>
  <tr>
    <td>Justificativa</td>
    <td>A documentação é essencial, pois visa garantir que os usuários tenham conhecimento do funcionamento do aplicativo, como trata os dados coletados, direitos/deveres e outros tópicos importantes</td>
  </tr>
  <tr>
    <td>Origem do Requisito</td>
    <td><a href="https://requisitos-de-software.github.io/2024.1-Consumidor.gov/Modelagem/especsuplementar/">Especificação suplementar</a> e <a href="https://requisitos-de-software.github.io/2024.1-Consumidor.gov/Elicitação/requisitos-elicitados/">requisitos elicitados</a></td>
  </tr>
  <tr>
    <td>Dependências</td>
    <td>Não foram identificadas dependências</td>
  </tr>
  <tr>
    <td>Prioridade</td>
    <td>MÉDIA</td>
  </tr>
  <tr>
    <td>Conflitos</td>
    <td>Não foi identificado nenhum conflito</td>
  </tr>
  <tr>
    <td>História</td>
    <td>27/05/2024</td>
  </tr>
</table>

<font size="3"><p style="text-align: center">Autor: CÉSAR, Julio. 2024</p></font>
</figure>
</div>

## Referências Bibliográficas

> [1] SILVA, Reinaldo Antônio da. NFR4ES: Um Catálogo de Requisitos Não-Funcionais para Sistemas Embarcados, 2019. Disponível em: [https://aprender3.unb.br/pluginfile.php/2845051/mod_resource/content/2/DISSERTA%C3%87%C3%83O%20Reinaldo%20Ant%C3%B4nio%20da%20Silva.pdf](https://aprender3.unb.br/pluginfile.php/2845051/mod_resource/content/2/DISSERTA%C3%87%C3%83O%20Reinaldo%20Ant%C3%B4nio%20da%20Silva.pdf). Acesso em: 23 de maio de 2024.

## Bibliografia

> SERRANO, et al. Requisitos – Aula 17, 2024. Disponível em: [https://aprender3.unb.br/pluginfile.php/2845052/mod_resource/content/1/Requisitos%20-%20Aula%20019a.pdf](https://aprender3.unb.br/pluginfile.php/2845052/mod_resource/content/1/Requisitos%20-%20Aula%20019a.pdf). Acesso em: 23 de maio de 2024.

> YRJÖNEN, Anton; MERILLINA, Janne. Extending the NFR Framework with Measurable Non-Functional Requirements, 2009. Disponível em: [https://ceur-ws.org/Vol-553/paper2.pdf](https://ceur-ws.org/Vol-553/paper2.pdf). Acesso em: 23 de maio de 2024.

> CASTRO, Jaelson. Requisitos Não-Funcionais, 2014. Disponível em: [https://www.cin.ufpe.br/~if716/arquivos20152/experimentoBruno/Aula2/Aula2-Parte2-NFR%20Framework.pdf](https://www.cin.ufpe.br/~if716/arquivos20152/experimentoBruno/Aula2/Aula2-Parte2-NFR%20Framework.pdf). Acesso em: 23 de maio de 2024.

## Histórico de Versão

| Versão | Data de execução | Data de revisão |  Descrição                          | Autor(es)                                           | Revisor(es)                                           |
| :----: | :--------------: | :-------------: | :---------------------------------: | :-------------------------------------------------: | :---------------------------------------------------: |
| 1.0    | 22/05/2024       | 23/05/2024      | Criação do artefato NFR Framework   | [Henrique Galdino](https://github.com/hgaldino05)   | [Igor Thiago](https://github.com/alladin-51)         |
