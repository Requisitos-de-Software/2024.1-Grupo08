# Especificação Suplementar

A **Especificação Suplementar** é um documento responsável pela observação e identificação de requisitos pertencentes ao sistema, os quais não foram primeiramente elicitados, sendo estes diretamente relacionados a critérios como:

- ***Funcionalidade***
- ***Usabilidade***
- ***Confiabilidade***
- ***Performance***
- ***Suportabilidade***

Esta documentação, costuma ser elaborada através do uso da metodologia *FURPS+*.


## FURPS+
A metodologia FURPS+ é utilizada para classificar requisitos pertencentes a um sistema, sendo estes divididos em cinco categorias principais, sendo elas:

- **F**: *Funtionality (Funcionalidade)* - Requisitos relacionados a funcionalidades do sistema.
- **U**: *Usability (Usabilidade)* - Requisitos relacionados a usabilidade do sistema, principalmente em relação a interface e intuitividade do mesmo.
- **R**: *Reliability (Confiabilidade)* - Requisitos relacionados a confiabilidade do sistema, como por exemplo, a capacidade de prevenção de falhas ou delimitação de tempo necessário para recuperação.
- **P**: *Performance (Performance)* - Requisitos relacionados a performance do sistema, como por exemplo, tempo de resposta, capacidade de processamento ou consumo de armazenamento.
- **S**: *Supportability (Suportabilidade)* - Requisitos relacionados a suportabilidade do sistema, como por exemplo, facilidade de manutenção, adaptabilidade, facilidade de configuração e compatibilidade entre dispositivos/sistemas operacionais.
- **+**: *Outros* - Outros requisitos que devem ser considerados durante o desenvolvimento como requisitos físicos (hardware), requisitos de implementação, restrições de design e requisitos de interface.


## *'F' - Funcionalidade*

Os requisitos de funcionalidade são aqueles que representam os requisitos não funcionais de um sistema. Estes requisitos foram previamente identificados durante a fase de elicitação, utilizando as técnicas abaixo:
Estes requisitos podem ser vistos na página de [Requisitos Elicitados](https://requisitos-de-software.github.io/2024.1-Consumidor.gov/Elicitação/requisitos-elicitados/).


## *'U' - Usabilidade*

Os requisitos de usabilidade são aqueles que representam os requisitos relacionados a usabilidade do sistema. Estes requisitos foram previamente identificados durante a fase de elicitação, e podem ser vistos na tabela 1 situada abaixo, que mostra **identificador, descrição e origem** dos mesmos:

| Identificador | Descrição | Origem |
| :------: | :----------: | :--------: |
| RUS1 | O aplicativo deve apresentar uma interface simples e intuitiva, que facilite a utilização por parte dos usuários | [RNF2, RNF8](https://requisitos-de-software.github.io/2024.1-Consumidor.gov/Elicitação/requisitos-elicitados/) |
| RUS2 | O aplicativo deve apresentar recursos de acessibilidade (contraste/modo escuro, paleta de cores para daltônicos, recursos de aúdio, etc.) | [RNF3](https://requisitos-de-software.github.io/2024.1-Consumidor.gov/Elicitação/requisitos-elicitados/) |
| RUS3 | O aplicativo deve responder imediatamente às ações do usuário (mesmo que seja necessário carregamento de interface ou componentes) | [RNF7, RNF13](https://requisitos-de-software.github.io/2024.1-Consumidor.gov/Elicitação/requisitos-elicitados/) |
| RUS4 | O aplicativo deve apresentar navegação simples entre suas interfaces | [RNF2, RNF8](https://requisitos-de-software.github.io/2024.1-Consumidor.gov/Elicitação/requisitos-elicitados/) |
| RUS4 | O aplicativo deve apresentar um padrão para suas interfaces, mantendo a estilização de cores e componentes entre as mesmas | [RNF18, RNF19](https://requisitos-de-software.github.io/2024.1-Consumidor.gov/Elicitação/requisitos-elicitados/) |
| RUS5 | O aplicativo deve apresentar feedback para o usuário em caso de erros ou falhas | [RNF4](https://requisitos-de-software.github.io/2024.1-Consumidor.gov/Elicitação/requisitos-elicitados/) |
| RUS6 | O aplicativo deve permitir realizar uma reclamação com no máximo 5 cliques | [RNF8](https://requisitos-de-software.github.io/2024.1-Consumidor.gov/Elicitação/requisitos-elicitados/) |

<div align="center">
<figcaption align="left">Tabela 1: Requisitos de Usabilidade (Autor: MEISTER, GUILHERME 2024)</figcaption>
</div>
<br/>

## *'R' - Confiabilidade*

Os requisitos de confiabilidade são aqueles que representam os requisitos relacionados a confiabilidade, segurança e estabilidade do sistema. Estes requisitos foram previamente identificados durante a fase de elicitação, e podem ser vistos na tabela 2 situada abaixo, que mostra **identificador, descrição e origem** dos mesmos:

| Identificador | Descrição | Origem |
| :------: | :----------: | :--------: |
| RCO1 | O aplicativo deve estar acessível 24 horas por dia, 7 dias por semana (salvo manutenção ou desativação previamente agendada e informada) | [RNF9](https://requisitos-de-software.github.io/2024.1-Consumidor.gov/Elicitação/requisitos-elicitados/) |
| RCO2 | Em caso de falha ou queda, o sistema deve ser recuperado em até 24 horas após ser reportada | [RNF9, RNF10](https://requisitos-de-software.github.io/2024.1-Consumidor.gov/Elicitação/requisitos-elicitados/) |
| RCO3 | O aplicativo deve seguir a Lei Geral de Proteção de Dados (LGPD)  | [RNF5](https://requisitos-de-software.github.io/2024.1-Consumidor.gov/Elicitação/requisitos-elicitados/) |
| RCO4 | O aplicativo deve estar protegido de tentativas de acesso não autorizados (interligado ao sistema Gov.br)   | [RNF5, RNF6](https://requisitos-de-software.github.io/2024.1-Consumidor.gov/Elicitação/requisitos-elicitados/) |

<div align="center">
<figcaption align="left">Tabela 2: Requisitos de Confiabilidade (Autor: THIAGO, Igor 2024)</figcaption>
</div>
<br/>

## *'P' - Performance*

Os requisitos de performance são aqueles que representam os requisitos relacionados ao desempenho e tempo de resposta do sistema, o qual foi baseado em uma média dos valores obtidos durante a utilização do Consumidor.gov pela equipe. Estes requisitos foram previamente identificados durante a fase de elicitação, e podem ser vistos na tabela 3 situada abaixo, que mostra **identificador, descrição e origem** dos mesmos:

| Identificador | Descrição | Origem |
| :------: | :----------: | :--------: |
| RPE1 | O aplicativo deve apresentar tempo de resposta de no máximo 2 segundos para qualquer ação do usuário | [RNF7](https://requisitos-de-software.github.io/2024.1-Consumidor.gov/Elicitação/requisitos-elicitados/) |
| RPE2 | O aplicativo deve apresentar tempo de carregamento de interface médio de 5 segundos | [RNF11](https://requisitos-de-software.github.io/2024.1-Consumidor.gov/Elicitação/requisitos-elicitados/) |
| RPE3 | O aplicativo deve apresentar tempo de carregamento de componentes médio de 10 segundos | [RNF11](https://requisitos-de-software.github.io/2024.1-Consumidor.gov/Elicitação/requisitos-elicitados/) |
| RPE4 | O aplicativo deve realizar autenticação (login) no tempo médio de 10 segundos | [RNF12](https://requisitos-de-software.github.io/2024.1-Consumidor.gov/Elicitação/requisitos-elicitados/) |
| RPE5 | O aplicativo deve carregar conteúdos (interfaces e seus componentes) e funções em no máximo 20 segundos | [RNF11, RNF12](https://requisitos-de-software.github.io/2024.1-Consumidor.gov/Elicitação/requisitos-elicitados/) |

<div align="center">
<figcaption align="left">Tabela 3: Requisitos de Performance (Autor: CÉSAR, Júlio 2024)</figcaption>
</div>
<br/>

## *'S' - Suportabilidade*

Os requisitos de suportabilidade são aqueles que representam os requisitos relacionados a manutenção, configuração, compatibilidade e capacidade de expansão do sistema. Estes requisitos foram previamente identificados durante a fase de elicitação, e podem ser vistos na tabela 4 situada abaixo, que mostra **identificador, descrição e origem** dos mesmos:

| Identificador | Descrição | Origem |
| :------: | :----------: | :--------: |
| RSU1 | O aplicativo deve estar disponível para Android (Play Store) e iOS (App Store) | [RNF1](https://requisitos-de-software.github.io/2024.1-Consumidor.gov/Elicitação/requisitos-elicitados/) |
| RSU2 | O aplicativo deve ser compatível com diferentes dispositivos (smartphones e tablets) Android e iOS, ajustando-se para cada um no que diz respeito a dimensões/proporções e capacidade de funcionamento | [RNF1](https://requisitos-de-software.github.io/2024.1-Consumidor.gov/Elicitação/requisitos-elicitados/) |
| RSU3 | O aplicativo deve apresentar código bem estruturado e organizado, com o objetivo de facilitar a manutenção e a aplicação de atualizações |[RNF20](https://requisitos-de-software.github.io/2024.1-Consumidor.gov/Elicitação/requisitos-elicitados/) |
| RSU4 | O aplicativo deve estar apto a receber atualizações a qualquer momento, seja para implementação de novas funcionalidades quanto para correção de falhas/erros no código | [RNF17](https://requisitos-de-software.github.io/2024.1-Consumidor.gov/Elicitação/requisitos-elicitados/) |
| RSU5 | O aplicativo deve ser testado periodicamente, a fim de checar a integridade do sistema e de suas funções | [RNF16](https://requisitos-de-software.github.io/2024.1-Consumidor.gov/Elicitação/requisitos-elicitados/) |
| RSU6 | As atualizações do aplicativo devem ser devidamente testadas antes de publicadas na Play Store e/ou App Store | [RNF16, RNF17](https://requisitos-de-software.github.io/2024.1-Consumidor.gov/Elicitação/requisitos-elicitados/) |

<div align="center">
<figcaption align="left">Tabela 4: Requisitos de Suportabilidade (Autor: FERREIRA, Matheus 2024)</figcaption>
</div>
<br/>

## *'+' - Outros*

Os demais requisitos são aqueles que representam os requisitos que não se encaixam nas categorias anteriores, mas devem ser considerados durante o desenvolvimento como requisitos físicos (hardware), requisitos de implementação, restrições de design e requisitos de interface. 

### Requisitos de Implementação
Os requisitos de implementação são aqueles que representam os requisitos relacionados a implementação e construção do sistema. Estes requisitos foram previamente identificados durante a fase de elicitação e nas lojas de aplicativos, e podem ser vistos na tabela 5 situada abaixo, que mostra **identificador, descrição e origem** dos mesmos:

| Identificador | Descrição | Origem |
| :------: | :----------: | :--------: |
| RIM1 | O aplicativo deve funcionar em dispositivos cuja versão Android seja **5.0** ou superior e cuja versão iOS seja **9.0** ou superior. | [RNF1](https://requisitos-de-software.github.io/2024.1-Consumidor.gov/Elicitação/requisitos-elicitados/); [Play Store](https://play.google.com/store/apps/details?id=br.com.consumidor&hl=pt_BR&gl=US) e [App Store](https://apps.apple.com/br/app/consumidor-gov-br/id1492523966) |
| RIM2 | O aplicativo necessita de no mínimo **34 MB** na memória do dispositivo | [Play Store](https://play.google.com/store/apps/details?id=br.com.consumidor&hl=pt_BR&gl=US) e [App Store](https://apps.apple.com/br/app/consumidor-gov-br/id1492523966) |
| RIM3 | O aplicativo deve informar ao usuário as permissões que devem ser concedidas ao aplicativo para seu funcionamento | [Play Store](https://play.google.com/store/apps/details?id=br.com.consumidor&hl=pt_BR&gl=US) e [App Store](https://apps.apple.com/br/app/consumidor-gov-br/id1492523966) |

<div align="center">
<figcaption align="left">Tabela 5: Requisitos de Implementação (Autor: GONTIJO, Rodrigo 2024)</figcaption>
</div>
<br/>

### Requisitos de Interface
Os requisitos de interface são aqueles que representam os requisitos relacionados a interface do sistema. Estes requisitos foram previamente identificados durante a fase de elicitação e na, e podem ser vistos na tabela 6 situada abaixo, que mostra **identificador, descrição e origem** dos mesmos:

| Identificador | Descrição | Origem |
| :------: | :----------: | :--------: |
| RIN1 | O aplicativo deve apresentar interfaces com opções de acessibilidade audiovisuais, como descrição de texto e imagens, modo alto contraste e modo escuro | [RNF3](https://requisitos-de-software.github.io/2024.1-Consumidor.gov/Elicitação/requisitos-elicitados/) |
| RIN2 | O aplicativo deve apresentar uma tela  "home", contendo os atalhos para as funcionalidades do mesmo | [RNF2](https://requisitos-de-software.github.io/2024.1-Consumidor.gov/Elicitação/requisitos-elicitados/) |

<div align="center">
<figcaption align="left">Tabela 6: Requisitos de Interface (Autor: GALDINO, Henrique 2024)</figcaption>
</div>

### Requisitos Físicos
Os requisitos físicos são aqueles que representam os requisitos relacionados a hardware do sistema. Estes requisitos foram previamente identificados durante a fase de elicitação e nas lojas de aplicativos, e podem ser vistos na tabela 7 situada abaixo, que mostra **identificador, descrição e origem** dos mesmos:

| Identificador | Descrição | Origem |
| :------: | :----------: | :--------: |
| RFI1 | O aplicativo deve funcionar em dispositivos com capacidade de conexão a redes Wi-Fi e conexão a redes móveis (**3G**,**4G** e **5G**) | [RNF1](https://requisitos-de-software.github.io/2024.1-Consumidor.gov/Elicitação/requisitos-elicitados/) |
| RFI2 | O aplicativo deve funcionar em dispositivos móveis (smartphones e tablets) e computadores/notebooks | [Play Store](https://play.google.com/store/apps/details?id=br.com.consumidor&hl=pt_BR&gl=US) e [App Store](https://apps.apple.com/br/app/consumidor-gov-br/id1492523966) |

<div align ="center">
<figcaption align="left">Tabela 7: Requisitos Físicos (Autor: GALDINO, Henrique 2024)</figcaption>
</div>

### Restrições de Design
As restrições de design são aquelas que representam as restrições relacionadas ao design do sistema. Estes requisitos foram previamente identificados durante a fase de elicitação, e podem ser vistos na tabela 8 situada abaixo, que mostra **identificador e descrição** dos mesmos:

| Identificador | Descrição | Origem |
| :------: | :----------: | :--------: |
| RDD1 | O aplicativo deve seguir os padrões designados pelo sistema Gov.br | [RNF18](https://requisitos-de-software.github.io/2024.1-Consumidor.gov/Elicitação/requisitos-elicitados/) |
| RDD2 | O aplicativo deve manter um padrão de cores e fontes para todas suas interfaces e componentes | [RNF19](https://requisitos-de-software.github.io/2024.1-Consumidor.gov/Elicitação/requisitos-elicitados/) |

<div align="center">
<figcaption align="left">Tabela 8: Restrições de Design (Autor: GALDINO, Henrique 2024)</figcaption>
</div>

### Requisitos de Documentação
Os requisitos de documentação são aqueles que representam os requisitos relacionados a documentação do sistema. Estes requisitos foram previamente identificados durante a fase de elicitação, e podem ser vistos na tabela 9 situada abaixo, que mostra **identificador e descrição** dos mesmos:

| Identificador | Descrição | Origem |
| :------: | :----------: | :--------: |
| RDO1 | O aplicativo deve apresentar um manual ou guia de uso para o usuário | [RNF15](https://requisitos-de-software.github.io/2024.1-Consumidor.gov/Elicitação/requisitos-elicitados/) |
| RDO2 | O aplicativo deve apresentar um seção "Fale Conosco" ou "SAC" | [RNF14](https://requisitos-de-software.github.io/2024.1-Consumidor.gov/Elicitação/requisitos-elicitados/) |
| RDO3 | O aplicativo deve apresentar um seção "FAQ - Dúvidas Frequentes" | [RNF14](https://requisitos-de-software.github.io/2024.1-Consumidor.gov/Elicitação/requisitos-elicitados/) |
| RDO4 | O aplicativo deve disponibilizar os Termos de Uso e Orientações de Uso para o usuário | [RNF15](https://requisitos-de-software.github.io/2024.1-Consumidor.gov/Elicitação/requisitos-elicitados/) |

<div align="center">
<figcaption align="left">Tabela 9: Requisitos de Documentação (Autor: GALDINO, Henrique 2024)</figcaption>
</div>

## Bibliografia

SERRANO, et al. Requisitos – Aula 13, 2024. Disponível em: <https://aprender3.unb.br/pluginfile.php/2845007/mod_resource/content/1/Requisitos%20-%20Aula%20013a.pdf>

FURPS+, 2008. Acesso em 16 de maio de 2024. Disponível em: <https://qualidadebr.wordpress.com/2008/07/10/furps/#:~:text=FURPS%2B%20é%20um%20sistema%20para,Rational%20Unified%20Process%20(RUP)%3A>

## Histórico de Versão
| Versão | Data de execução | Data de revisão |  Descrição            | Autor(es)         | Revisor(es)  |
| :------: | :----------: | :--------: | :--------------------: | :-------------: | :----------: |
| `1.7` | 25/05/2024  | 25/05/2024 | Correção conforme feedback | [Henrique Galdino](https://github.com/hgaldino05) | [Igor Thiago](https://github.com/alladin-51) |
| `1.6` | 18/05/2024  | 19/05/2024 | Adição requisitos '+'| [Rodrigo Gontijo](https://github.com/rodrigogontijoo), [Henrique Galdino](https://github.com/hgaldino05) | [Igor Thiago](https://github.com/alladin-51) |
| `1.5` | 18/05/2024  | 18/05/2024 | Adição requisitos Suportabilidade| [Rodrigo Gontijo](https://github.com/rodrigogontijoo), [Henrique Galdino](https://github.com/hgaldino05) | [Igor Thiago](https://github.com/alladin-51) |
| `1.4` | 18/05/2024  | 18/05/2024 | Adição requisitos Performance| [Matheus Ferreira](https://github.com/matferreira1), [Henrique Galdino](https://github.com/hgaldino05) | [Rodrigo Gontijo](https://github.com/rodrigogontijoo) |
| `1.3` | 17/05/2024  | 18/05/2024 | Adição requisitos Performance| [Júlio César](https://github.com/Julio1099), [Henrique Galdino](https://github.com/hgaldino05) | [Rodrigo Gontijo](https://github.com/rodrigogontijoo) |
| `1.2` | 17/05/2024  | 17/05/2024 | Adição requisitos Confiabilidade| [Igor Thiago](https://github.com/alladin-51), [Henrique Galdino](https://github.com/hgaldino05) | [Rodrigo Gontijo](https://github.com/rodrigogontijoo) |
| `1.1` | 17/05/2024  | 17/05/2024 | Adição requisitos Usabilidade | [Guilherme Meister](https://github.com/gmeister18), [Henrique Galdino](https://github.com/hgaldino05) | [Igor Thiago](https://github.com/alladin-51) |
| `1.0` | 16/05/2024  | 16/05/2024 | Criação do artefato de Especificação Suplementar | [Henrique Galdino](https://github.com/hgaldino05) | [Igor Thiago](https://github.com/alladin-51) |

<div align="center">
<figcaption align="left">Tabela 10: Histórico de versões(Autor: GALDINO, Henrique 2024)</figcaption>
</div>
<br/>