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

<img src="URL_DA_IMAGEM" style="width: 85%;">

<font size="3"><p style="text-align: center"><b>Fonte:</b> (CHUNG et al., 2000).</a></p></font>
</div>

O processo de avaliação determina o nível de cumprimento dos requisitos não funcionais através de um conjunto de decisões. Em outras palavras, o procedimento de avaliação verifica se cada softgoal ou interdependência no SIG foi adequadamente atendido. Isso é feito atribuindo rótulos aos softgoals, sendo que os rótulos possíveis incluem "satisfeito", "parcialmente satisfeito", "não atendido", "parcialmente não atendido", "conflitante" e "indeterminado". 
A figura 2 ilustra um exemplo de cada rótulo, conforme apresentado no artigo de Reinaldo Antônio da Silva[¹](https://requisitos-de-software.github.io/2024.1-Consumidor.gov/Modelagem/Modelagem%20%C3%81gil/NFR/#referencias-bibliograficas). Essa figura também servirá como legenda para os NFRs que serão discutidos neste documento.

<div align="center">
<font size="3"><p style="text-align: center"><b>Figura 2:</b> Rótulos da propagação de impactos.</p></font>

<img src="URL_DA_IMAGEM" style="width: 85%;">

<font size="3"><p style="text-align: center"><b>Fonte:</b> (CHUNG et al., 2000).</a></p></font>
</div>

## Metodologia

Neste documento, descreveremos 12 Requisitos Não Funcionais (NFRs) derivados do nosso documento de especificação suplementar, o qual se fundamentou no modelo FURPS+. Cada membro da equipe foi responsável por definir um NFR dentro de uma categoria do modelo FURPS+.

Para cada categoria, elaboramos um SIG (Softgoal Interdependency Graph), um diagrama que ilustra a propagação de impactos, e um cartão de especificação contendo informações detalhadas sobre o NFR, como sua descrição, categoria, possíveis conflitos, origem, critérios e outras informações relevantes.

## NFR

### NFR01 - Usabilidade

Usabilidade se refere à facilidade e eficácia com que um usuário pode interagir com um sistema, produto ou serviço para alcançar seus objetivos de forma eficiente e satisfatória.

#### Softgoal Interdependency Graph

O Softgoal Interdependency Graph do softgoal "Usabilidade" pode ser visto na figura X.

<div align="center">
<font size="3"><p style="text-align: center"><b>Figura X:</b> Softgoal Interdependency Graph do softgoal "Usabilidade".</p></font>

<img src="URL_DA_IMAGEM" style="width: 85%;">

<font size="3"><p style="text-align: center"><b>Autor:</b> Seu Nome, Ano</p></font>
</div>

#### Propagação de Impactos

A propagação de impactos do softgoal "Usabilidade" pode ser vista na figura X.

<div align="center">
<font size="3"><p style="text-align: center"><b>Figura X:</b> Propagação de impactos do softgoal "Usabilidade"</p></font>

<img src="URL_DA_IMAGEM" style="width: 85%;">

<font size="3"><p style="text-align: center"><b>Fonte:</b> Seu Nome, Ano</p></font>
</div>

#### Cartão de Especificação

Na tabela 1, temos o cartão de especificação do softgoal "Usabilidade".

<div align="center">
<p><b>Tabela 1:</b> Cartão de Especificação do Softgoal Usabilidade</p>
<table>
  <tr>
    <th>Tópico</th>
    <th>Informação</th>
  </tr>
  <tr>
    <td>ID do NFR</td>
    <td>NFR01</td>
  </tr>
  <tr>
    <td>Classificação</td>
    <td>Usabilidade</td>
  </tr>
  <tr>
    <td>Descrição</td>
    <td>O requisito "Usabilidade" refere-se à capacidade do sistema de entregar uma boa usabilidade para os usuários do aplicativo.</td>
  </tr>
  <tr>
    <td>Justificativa</td>
    <td>Uma boa Usabilidade é fundamental para garantir que os usuários possam utilizar o aplicativo com eficiência e garantir a satisfação do usuário, aumentando a acessibilidade e reduzindo erros.</td>
  </tr>
  <tr>
    <td>Origem do Requisito</td>
    <td><a href="https://requisitos-de-software.github.io/2024.1-Consumidor.gov/Modelagem/especsuplementar/">Especificação suplementar</a> e <a href="https://requisitos-de-software.github.io/2024.1-Consumidor.gov/Elicitação/requisitos-elicitados/">requisitos elicitados</a></td>
</td>
  </tr>
  <tr>
    <td>Dependências</td>
    <td>Não foram identificadas restrições ou dependências específicas, mas a atualização da documentação deve ser planejada e coordenada com as versões do aplicativo.</td>
  </tr>
  <tr>
    <td>Prioridade</td>
    <td>O requisito de "Usabilidade" é de alta prioridade, uma vez que influencia diretamente a satisfação do usuário e a eficácia do aplicativo.</td>
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

<img src="URL_DA_IMAGEM" style="width: 85%;">

<font size="3"><p style="text-align: center"><b>Autor:</b> Seu Nome, Ano</p></font>
</div>

#### Propagação de Impactos

A propagação de impactos do softgoal "Confiabilidade" pode ser vista na figura X.

<div align="center">
<font size="3"><p style="text-align: center"><b>Figura X:</b> Propagação de impactos do softgoal "Confiabilidade"</p></font>

<img src="URL_DA_IMAGEM" style="width: 85%;">

<font size="3"><p style="text-align: center"><b>Autor:</b> Seu Nome, Ano</p></font>
</div>

#### Cartão de Especificação
Na tabela 2, temos o cartão de especificação do softgoal "Confiabilidade".

<div align="center">
<p><b>Tabela 2:</b> Cartão de Especificação do Softgoal "Confiabilidade"</p>
<table>
  <tr>
    <th>Tópico</th>
    <th>Informação</th>
  </tr>
  <tr>
    <td>ID do NFR</td>
    <td>NFR02</td>
  </tr>
  <tr>
    <td>Classificação</td>
    <td>Confiabilidade</td>
  </tr>
  <tr>
    <td>Descrição</td>
    <td>O requisito "Confiabilidade" refere-se à capacidade do sistema de funcionar consistentemente, estável e sem falhas, garantindo uma experiência positiva do usuário e a credibilidade do aplicativo.</td>
  </tr>
  <tr>
    <td>Justificativa</td>
    <td>A Confiabilidade é fundamental para manter a satisfação do usuário, evitar interrupções inesperadas e garantir o funcionamento correto do aplicativo. Ela é essencial para a credibilidade do aplicativo.</td>
  </tr>
  <tr>
    <td>Origem do Requisito</td>
    <td><a href="https://requisitos-de-software.github.io/2024.1-Consumidor.gov/Modelagem/especsuplementar/">Especificação suplementar</a> e <a href="https://requisitos-de-software.github.io/2024.1-Consumidor.gov/Elicitação/requisitos-elicitados/">requisitos elicitados</a></td>
  </tr>
  <tr>
    <td>Dependências</td>
    <td>Não foram identificadas dependências específicas, mas a manutenção e atualização do aplicativo devem ser coordenadas com as versões lançadas.</td>
  </tr>
  <tr>
    <td>Prioridade</td>
    <td>O requisito de "Confiabilidade" é de alta prioridade devido ao seu impacto direto na satisfação do usuário e na credibilidade do aplicativo.</td>
  </tr>
  <tr>
    <td>Conflitos</td>
    <td>Não foi identificado nenhum conflito com outros requisitos.</td>
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

<img src="URL_DA_IMAGEM" style="width: 85%;">

<font size="3"><p style="text-align: center"><b>Autor:</b> Seu Nome, Ano</p></font>
</div>

#### Propagação de Impactos

A propagação de impactos do softgoal "Performance" pode ser vista na figura X.

<div align="center">
<font size="3"><p style="text-align: center"><b>Figura X:</b> Propagação de impactos do softgoal "Performance"</p></font>

<img src="URL_DA_IMAGEM" style="width: 85%;">

<font size="3"><p style="text-align: center"><b>Autor:</b> Seu Nome, Ano</p></font>
</div>

#### Cartão de Especificação

Na tabela 3, temos o cartão de especificação do softgoal "Performance".

<div align="center">
<p><b>Tabela 3:</b> Cartão de Especificação do Softgoal "Performance"</p>
<table>
  <tr>
    <th>Tópico</th>
    <th>Informação</th>
  </tr>
  <tr>
    <td>ID do NFR</td>
    <td>NFR03</td>
  </tr>
  <tr>
    <td>Classificação</td>
    <td>Performance</td>
  </tr>
  <tr>
    <td>Descrição</td>
    <td>Performance refere-se ao desempenho e tempo de resposta do sistema.</td>
  </tr>
  <tr>
    <td>Justificativa</td>
    <td>É crucial que o sistema responda de maneira rápida e eficiente para garantir uma experiência satisfatória para o usuário.</td>
  </tr>
  <tr>
    <td>Origem do Requisito</td>
    <td><a href="https://requisitos-de-software.github.io/2024.1-Consumidor.gov/Modelagem/especsuplementar/">Especificação suplementar</a> e <a href="https://requisitos-de-software.github.io/2024.1-Consumidor.gov/Elicitação/requisitos-elicitados/">requisitos elicitados</a></td>
  </tr>
  <tr>
    <td>Dependências</td>
    <td>Não foram identificadas dependências específicas.</td>
  </tr>
  <tr>
    <td>Prioridade</td>
    <td>Alta prioridade, uma vez que influencia diretamente na satisfação do usuário.</td>
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

<img src="URL_DA_IMAGEM" style="width: 85%;">

<font size="3"><p style="text-align: center"><b>Autor:</b> Seu Nome, Ano</p></font>
</div>

#### Propagação de Impactos

A propagação de impactos do softgoal "Performance" pode ser vista na figura X.

<div align="center">
<font size="3"><p style="text-align: center"><b>Figura X:</b> Propagação de impactos do softgoal "Performance"</p></font>

<img src="URL_DA_IMAGEM" style="width: 85%;">

<font size="3"><p style="text-align: center"><b>Autor:</b> Seu Nome, Ano</p></font>
</div>

#### Cartão de Especificação

Na tabela 4, temos o cartão de especificação do softgoal "Suporte".

<div align="center">
<p><b>Tabela 4:</b> Cartão de Especificação do Softgoal "Suporte"</p>
<table>
  <tr>
    <th>Tópico</th>
    <th>Informação</th>
  </tr>
  <tr>
    <td>Identificador</td>
    <td>NFR04</td>
  </tr>
  <tr>
    <td>Classificação</td>
    <td>Suportabilidade</td>
  </tr>
  <tr>
    <td>Descrição</td>
    <td>O suporte de um sistema é relacionado ao nível de manutenção, configuração, compatibilidade e capacidade de expansão do sistema. Esses aspectos são cruciais para garantir que o sistema seja mantido, atualizado e capaz de atender às necessidades dos usuários.</td>
  </tr>
  <tr>
    <td>Justificativa</td>
    <td>É fundamental assegurar uma alta capacidade de suporte para garantir que o sistema permaneça funcional, seguro e eficiente ao longo do tempo. A manutenção adequada, a compatibilidade com diferentes dispositivos e sistemas operacionais, e a capacidade de expansão são aspectos essenciais para atender às demandas dos usuários e manter a relevância do sistema.</td>
  </tr>
  <tr>
    <td>Origem do Requisito</td>
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

### NFR05 - Restrições de Design

Restrições de design são limitações ou condições específicas que influenciam o processo de criação e desenvolvimento de um produto, sistema ou serviço.

#### Softgoal Interdependency Graph

O Softgoal Interdependency Graph do softgoal "Design" pode ser visto na figura X.

<div align="center">
<font size="3"><p style="text-align: center"><b>Figura X:</b> Softgoal Interdependency Graph do softgoal "Design".</p></font>

<img src="URL_DA_IMAGEM" style="width: 85%;">

<font size="3"><p style="text-align: center"><b>Autor:</b> Seu Nome, Ano</p></font>
</div>

#### Propagação de Impactos

A propagação de impactos do softgoal "Design" pode ser vista na figura X.

<div align="center">
<font size="3"><p style="text-align: center"><b>Figura X:</b> Propagação de impactos do softgoal "Design"</p></font>

<img src="URL_DA_IMAGEM" style="width: 85%;">

<font size="3"><p style="text-align: center"><b>Autor:</b> Seu Nome, Ano</p></font>
</div>

#### Cartão de Especificação

Na tabela 5, temos o cartão de especificação do Softgoal "Restrições de Design".

<div align="center">
<p><b>Tabela 5:</b> Cartão de Especificação do Softgoal "Restrições de Design"</p>
<table>
  <tr>
    <th>Tópico</th>
    <th>Informação</th>
  </tr>
  <tr>
    <td>Identificador</td>
    <td>RNF05</td>
  </tr>
  <tr>
    <td>Classificação</td>
    <td>Restrições de Design</td>
  </tr>
  <tr>
    <td>Descrição</td>
    <td>O requisito "Restrições de Design" refere-se a limitações ou condições específicas que devem ser consideradas durante o processo de criação e desenvolvimento do aplicativo.</td>
  </tr>
  <tr>
    <td>Justificativa</td>
    <td>As Restrições de Design são fundamentais para garantir uma experiência de usuário coesa e consistente, seguindo padrões estabelecidos e mantendo uma identidade visual unificada.</td>
  </tr>
  <tr>
    <td>Origem do Requisito</td>
    <td><a href="https://requisitos-de-software.github.io/2024.1-Consumidor.gov/Modelagem/especsuplementar/">Especificação suplementar</a> e <a href="https://requisitos-de-software.github.io/2024.1-Consumidor.gov/Elicitação/requisitos-elicitados/">requisitos elicitados</a></td>
  </tr>
  <tr>
    <td>Dependências</td>
    <td>Não foram identificadas restrições ou dependências específicas, mas a manutenção da documentação deve ser coordenada com as versões do aplicativo.</td>
  </tr>
  <tr>
    <td>Prioridade</td>
    <td>O requisito de "Restrições de Design" é de alta prioridade devido ao seu impacto direto na consistência visual e na experiência do usuário.</td>
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

### NFR06 - Implementação

Implementação é o processo de colocar em prática um plano ou conceito. Em termos de desenvolvimento de software ou engenharia de sistemas, implementação refere-se à fase em que o código é escrito e as soluções são construídas de acordo com as especificações e requisitos previamente definidos.

#### Softgoal Interdependency Graph

O Softgoal Interdependency Graph do softgoal "Implementação" pode ser visto na figura X.

<div align="center">
<font size="3"><p style="text-align: center"><b>Figura X:</b> Softgoal Interdependency Graph do softgoal "Implementação".</p></font>

<img src="URL_DA_IMAGEM" style="width: 85%;">

<font size="3"><p style="text-align: center"><b>Autor:</b> Seu Nome, Ano</p></font>
</div>

#### Propagação de Impactos

A propagação de impactos do softgoal "Implementação" pode ser vista na figura X.

<div align="center">
<font size="3"><p style="text-align: center"><b>Figura X:</b> Propagação de impactos do softgoal "Implementação"</p></font>

<img src="URL_DA_IMAGEM" style="width: 85%;">

<font size="3"><p style="text-align: center"><b>Autor:</b> Seu Nome, Ano</p></font>
</div>

#### Cartão de Especificação

Na tabela 6, temos o cartão de especificação do Softgoal "Implementação".

<div align="center">
<p><b>Tabela 6:</b> Cartão de Especificação do Softgoal "Restrições de Design"</p>

<table>
  <tr>
    <th>Tópico</th>
    <th>Informação</th>
  </tr>
  <tr>
    <td>Identificador</td>
    <td>NFR06</td>
  </tr>
  <tr>
    <td>Classificação</td>
    <td>Implementação</td>
  </tr>
  <tr>
    <td>Descrição</td>
    <td>Implementação é transformar ideias em ações. É o elo entre planejamento e resultados concretos. Requer organização, recursos e comprometimento para atingir objetivos em projetos, políticas ou estratégias.</td>
  </tr>
  <tr>
    <td>Justificativa</td>
    <td>A implementação é essencial para concretizar os planos e garantir que as ideias se transformem em ações tangíveis.</td>
  </tr>
  <tr>
    <td>Origem do Requisito</td>
    <td><a href="https://requisitos-de-software.github.io/2024.1-Consumidor.gov/Modelagem/especsuplementar/">Especificação suplementar</a> e <a href="https://requisitos-de-software.github.io/2024.1-Consumidor.gov/Elicitação/requisitos-elicitados/">requisitos elicitados</a></td>
  </tr>
  <tr>
    <td>Dependências</td>
    <td></td>
  </tr>
  <tr>
    <td>Prioridade</td>
    <td></td>
  </tr>
  <tr>
    <td>Conflitos</td>
    <td></td>
  </tr>
  <tr>
    <td>História</td>
    <td></td>
  </tr>
</table>

<font size="3"><p style="text-align: center">Autor: CÉSAR, Julio. 2024</p></font>
</figure>
</div>

### NFR07 - Requisitos de Interface

Interface refere-se ao ponto de interação entre dois sistemas, componentes ou entidades, onde ocorre a troca de informações, comandos ou interações. Em computação e tecnologia, uma interface pode ser tanto física quanto digital.

#### Softgoal Interdependency Graph

O Softgoal Interdependency Graph do softgoal "Interface" pode ser visto na figura X.

<div align="center">
<font size="3"><p style="text-align: center"><b>Figura X:</b> Softgoal Interdependency Graph do softgoal "Interface".</p></font>

<img src="URL_DA_IMAGEM" style="width: 85%;">

<font size="3"><p style="text-align: center"><b>Autor:</b> Seu Nome, Ano</p></font>
</div>

#### Propagação de Impactos

A propagação de impactos do softgoal "Interface" pode ser vista na figura X.

<div align="center">
<font size="3"><p style="text-align: center"><b>Figura X:</b> Propagação de impactos do softgoal "Interface"</p></font>

<img src="URL_DA_IMAGEM" style="width: 85%;">

<font size="3"><p style="text-align: center"><b>Autor:</b> Seu Nome, Ano</p></font>
</div>

#### Cartão de Especificação

Na tabela 7, temos o cartão de especificação do Softgoal "Interface".

<div align="center">
<p><b>Tabela 7:</b> Cartão de Especificação do Softgoal "Restrições de Design"</p>

<table>
  <tr>
    <th>Tópico</th>
    <th>Informação</th>
  </tr>
  <tr>
    <td>Identificador</td>
    <td>NFR07</td>
  </tr>
  <tr>
    <td>Classificação</td>
    <td>Interface</td>
  </tr>
  <tr>
    <td>Descrição</td>
    <td>Uma interface é a fronteira onde a interação ocorre entre dois sistemas, ou entre um sistema e seus usuários.</td>
  </tr>
  <tr>
    <td>Justificativa</td>
    <td>A interface é a ponte entre os usuários e os sistemas, e sua implementação é crucial para proporcionar uma experiência de usuário fluida e intuitiva.</td>
  </tr>
  <tr>
    <td>Origem do Requisito</td>
    <td><a href="https://requisitos-de-software.github.io/2024.1-Consumidor.gov/Modelagem/especsuplementar/">Especificação suplementar</a> e <a href="https://requisitos-de-software.github.io/2024.1-Consumidor.gov/Elicitação/requisitos-elicitados/">requisitos elicitados</a></td>
  </tr>
  <tr>
    <td>Dependências</td>
    <td></td>
  </tr>
  <tr>
    <td>Prioridade</td>
    <td></td>
  </tr>
  <tr>
    <td>Conflitos</td>
    <td></td>
  </tr>
  <tr>
    <td>História</td>
    <td></td>
  </tr>
</table>

<font size="3"><p style="text-align: center">Autor: CÉSAR, Julio. 2024</p></font>
</figure>

</div>

### NFR08 - Requisitos de Físicos

Os requisitos físicos são aqueles que representam os requisitos relacionados a hardware do sistema.

#### Softgoal Interdependency Graph

O Softgoal Interdependency Graph do softgoal "Físicos" pode ser visto na figura X.

<div align="center">
<font size="3"><p style="text-align: center"><b>Figura X:</b> Softgoal Interdependency Graph do softgoal "Físicos".</p></font>

<img src="URL_DA_IMAGEM" style="width: 85%;">

<font size="3"><p style="text-align: center"><b>Autor:</b> Seu Nome, Ano</p></font>
</div>

#### Propagação de Impactos

A propagação de impactos do softgoal "Físicos" pode ser vista na figura X.

<div align="center">
<font size="3"><p style="text-align: center"><b>Figura X:</b> Propagação de impactos do softgoal "Físicos"</p></font>

<img src="URL_DA_IMAGEM" style="width: 85%;">

<font size="3"><p style="text-align: center"><b>Autor:</b> Seu Nome, Ano</p></font>
</div>

#### Cartão de Especificação

Na tabela 8, temos o cartão de especificação do Softgoal "Físicos".

<div align="center">
<p><b>Tabela 8:</b> Cartão de Especificação do Softgoal "Restrições de Design"</p>

<table>
  <tr>
    <th>Tópico</th>
    <th>Informação</th>
  </tr>
  <tr>
    <td>Identificador</td>
    <td>NFR08</td>
  </tr>
  <tr>
    <td>Classificação</td>
    <td>Físicos</td>
  </tr>
  <tr>
    <td>Descrição</td>
    <td>
Os requisitos físicos referem-se às características tangíveis e materiais que um produto, sistema ou processo deve possuir para atender às necessidades práticas e funcionais.</td>
  </tr>
  <tr>
    <td>Justificativa</td>
    <td>A implementação dos requisitos físicos é essencial para garantir que o produto ou sistema atenda às necessidades práticas e funcionais dos usuários.</td>
  </tr>
  <tr>
    <td>Origem do Requisito</td>
    <td><a href="https://requisitos-de-software.github.io/2024.1-Consumidor.gov/Modelagem/especsuplementar/">Especificação suplementar</a> e <a href="https://requisitos-de-software.github.io/2024.1-Consumidor.gov/Elicitação/requisitos-elicitados/">requisitos elicitados</a></td>
  </tr>
  <tr>
    <td>Dependências</td>
    <td></td>
  </tr>
  <tr>
    <td>Prioridade</td>
    <td></td>
  </tr>
  <tr>
    <td>Conflitos</td>
    <td></td>
  </tr>
  <tr>
    <td>História</td>
    <td></td>
  </tr>
</table>

<font size="3"><p style="text-align: center">Autor: CÉSAR, Julio. 2024</p></font>
</figure>
</div>

### NFR09 - Requisitos de Documentação


Documentação refere-se ao conjunto de registros, informações e instruções que descrevem um sistema, processo, produto ou serviço.

#### Softgoal Interdependency Graph

O Softgoal Interdependency Graph do softgoal "Documentação" pode ser visto na figura X.

<div align="center">
<font size="3"><p style="text-align: center"><b>Figura X:</b> Softgoal Interdependency Graph do softgoal "Documentação".</p></font>

<img src="URL_DA_IMAGEM" style="width: 85%;">

<font size="3"><p style="text-align: center"><b>Autor:</b> Seu Nome, Ano</p></font>
</div>

#### Propagação de Impactos

A propagação de impactos do softgoal "Documentação" pode ser vista na figura X.

<div align="center">
<font size="3"><p style="text-align: center"><b>Figura X:</b> Propagação de impactos do softgoal "Documentação"</p></font>

<img src="URL_DA_IMAGEM" style="width: 85%;">

<font size="3"><p style="text-align: center"><b>Autor:</b> Seu Nome, Ano</p></font>
</div>

#### Cartão de Especificação

Na tabela 9, temos o cartão de especificação do Softgoal "Documentação".

<div align="center">
<p><b>Tabela 9:</b> Cartão de Especificação do Softgoal "Restrições de Design"</p>

<table>
  <tr>
    <th>Tópico</th>
    <th>Informação</th>
  </tr>
  <tr>
    <td>Identificador</td>
    <td>NFR09</td>
  </tr>
  <tr>
    <td>Classificação</td>
    <td>Documentação</td>
  </tr>
  <tr>
    <td>Descrição</td>
    <td>A documentação é o conjunto de registros escritos, gráficos ou audiovisuais que descrevem detalhadamente um produto, processo ou sistema.</td>
  </tr>
  <tr>
    <td>Justificativa</td>
    <td>A implementação da documentação é vital para garantir a compreensão clara e precisa do produto, processo ou sistema.</td>
  </tr>
  <tr>
    <td>Origem do Requisito</td>
    <td><a href="https://requisitos-de-software.github.io/2024.1-Consumidor.gov/Modelagem/especsuplementar/">Especificação suplementar</a> e <a href="https://requisitos-de-software.github.io/2024.1-Consumidor.gov/Elicitação/requisitos-elicitados/">requisitos elicitados</a></td>
  </tr>
  <tr>
    <td>Dependências</td>
    <td></td>
  </tr>
  <tr>
    <td>Prioridade</td>
    <td></td>
  </tr>
  <tr>
    <td>Conflitos</td>
    <td></td>
  </tr>
  <tr>
    <td>História</td>
    <td></td>
  </tr>
</table>

<font size="3"><p style="text-align: center">Autor: CÉSAR, Julio. 2024</p></font>
</figure>
</div>

## Referências Bibliográficas

> [1] DA SILVA, Reinaldo Antônio. NFR4ES: Um Catálogo de Requisitos Não-Funcionais para Sistemas Embarcados, 2019. Disponível em: [https://aprender3.unb.br/pluginfile.php/2845051/mod_resource/content/2/DISSERTA%C3%87%C3%83O%20Reinaldo%20Ant%C3%B4nio%20da%20Silva.pdf](https://aprender3.unb.br/pluginfile.php/2845051/mod_resource/content/2/DISSERTA%C3%87%C3%83O%20Reinaldo%20Ant%C3%B4nio%20da%20Silva.pdf). Acesso em: 23 de maio de 2024.

## Bibliografia

> SERRANO, et al. Requisitos – Aula 17, 2024. Disponível em: [https://aprender3.unb.br/pluginfile.php/2845052/mod_resource/content/1/Requisitos%20-%20Aula%20019a.pdf](https://aprender3.unb.br/pluginfile.php/2845052/mod_resource/content/1/Requisitos%20-%20Aula%20019a.pdf). Acesso em: 23 de maio de 2024.

> YRJÖNEN, Anton; MERILLINA, Janne. Extending the NFR Framework with Measurable Non-Functional Requirements, 2009. Disponível em: [https://ceur-ws.org/Vol-553/paper2.pdf](https://ceur-ws.org/Vol-553/paper2.pdf). Acesso em: 23 de maio de 2024.

> CASTRO, Jaelson. Requisitos Não-Funcionais, 2014. Disponível em: [https://www.cin.ufpe.br/~if716/arquivos20152/experimentoBruno/Aula2/Aula2-Parte2-NFR%20Framework.pdf](https://www.cin.ufpe.br/~if716/arquivos20152/experimentoBruno/Aula2/Aula2-Parte2-NFR%20Framework.pdf). Acesso em: 23 de maio de 2024.

## Histórico de Versão

| Versão | Data de execução | Data de revisão |  Descrição                          | Autor(es)                                           | Revisor(es)                                           |
| :----: | :--------------: | :-------------: | :---------------------------------: | :-------------------------------------------------: | :---------------------------------------------------: |
| 1.0    | 22/05/2024       | 23/05/2024      | Criação do artefato NFR Framework   | [Henrique Galdino](https://github.com/hgaldino05)   | [Igor Thiago](https://github.com/alladin-51)         |
