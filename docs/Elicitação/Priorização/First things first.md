# First Things First

## Introdução

A técnica First Things First (FTF) é uma abordagem estratégica para priorizar os requisitos de software. Ela enfatiza a importância de considerar cuidadosamente os benefícios, custos e riscos associados a cada requisito, a fim de direcionar os recursos para as áreas mais críticas. Ao fazer isso, a FTF busca maximizar os benefícios obtidos enquanto minimiza os custos e os riscos no desenvolvimento do software.

## Metodologia

As pessoas que participaram da elaboração dessa técnica estão descritas abaixo e listadas na tabela 1:

- **Mediador**: Encarregado de apresentar os requisitos mencionados.
- **Usuário**: Encarregado de avaliar os ganhos e as consequências negativas na realização de cada requisito.
- **Programador**: Encarregado de identificar os gastos e as possíveis adversidades na realização de cada requisito.


Cada linha da tabela representava um requisito elicitado. Após Henrique Galdino, o mediador, apresentar o requisito, Matheus Assis, o usuário, classificava de 1 a 9 o benefício relativo (onde 1 indica um benefício menor e 9 o máximo) e a penalidade relativa (onde 1 significa que não há penalidade se o requisito não for implementado e 9 indica uma grande desvantagem).

Em seguida, Igor Thiago, o desenvolvedor, classificava de 1 a 9 o custo relativo (considerando a complexidade da implementação, a interface de usuário necessária, a capacidade potencial de reutilização de telas ou código e os testes e documentações necessários) e o risco relativo (onde 1 significa muito fácil de programar e 9 indica sérias preocupações sobre viabilidade, disponibilidade de pessoal com o conhecimento necessário ou uso de ferramentas e tecnologias desconhecidas).

Após o preenchimento dessa tabela para todos os requisitos elicitados, foram calculados:

O valor total: (benefício relativo * peso relativo) + (penalidade relativa * peso relativo). Foi usado o peso relativo dos benefícios igual a 2 e o peso relativo das penalidades igual a 1, para dar maior importância aos benefícios.

O valor %: (valor total / soma de todos os valores totais) * 100 %

O custo %: (custo relativo / soma de todos os custos relativos) * 100 %

O risco %: (risco relativo / soma de todos os riscos relativos) * 100 %

A prioridade: valor % / ((custo % * peso custo) + (risco % * peso risco)). Foi usado o peso relativo do custo igual a 1 e o peso relativo do risco igual a 0,5.


| Peso relativo | Valor |
|---------------|-------|
| Benefício     | 2     |
| Penalidade    | 1     |
| Custo         | 1     |
| Risco         | 0.5   |

<div style="text-align: center;"><p>Tabela 1 - Peso relativo (Fonte: CÉSAR, Julio. 2024).</p></div>



| Nome                                              | Função        |
| ------------------------------------------------- | ------------- |
| [Henrique Galdino](https://github.com/hgaldino05)  | Mediador      |
| <span style = "color: orange">Matheus Assis</span> | Usuário       |
| [Igor Thiago](https://github.com/Alladin-51)  | Desenvolvedor |


<div style="text-align: center;"><p>Tabela 2 - Participantes (Fonte: CÉSAR, Julio. 2024).</p></div>

A tabela abaixo apresenta os resultados da priorização de requisitos, demonstrando o valor total, o percentual de valor, o custo relativo, o percentual de custo, o risco relativo, o percentual de risco e a prioridade de cada funcionalidade.


| Funcionalidades                            | Valor Benefício | Penalidade Relativa | Valor Total | Valor (%) | Custo Relativo | Custo % | Risco Relativo | Risco % | Prioridade |
| ------------------------------------------ | --------------- | -------------------- | ----------- | --------- | -------------- | ------- | -------------- | ------- | ---------- |
| REQ07 - fornecer detalhes reclamação       | 9               | 9                    | 27          | 7.35      | 3              | 4.22    | 3              | 3.84    | 1.19       |
| REQ02 - pesquisar empresa pelo nome        | 9               | 9                    | 27          | 7.35      | 3              | 4.22    | 4              | 5.12    | 1.08       |
| REQ08 - o que espera da empresa            | 9               | 8                    | 26          | 7.08      | 5              | 7.04    | 7              | 8.97    | 0.61       |
| REQ09 - anexar arquivos relacionados a reclamação | 9        | 8                    | 26          | 7.08      | 4              | 5.63    | 7              | 8.97    | 0.69       |
| REQ05 - informar como foi feita compra / serviço | 9         | 9                    | 27          | 7.35      | 4              | 5.63    | 3              | 3.84    | 0.97       |
| REQ06 - escolher a categoria da reclamação | 9               | 9                    | 27          | 7.35      | 4              | 5.63    | 3              | 3.84    | 0.97       |
| REQ11 - acompanhar o status da reclamação  | 9               | 6                    | 24          | 6.53      | 3              | 4.22    | 4              | 5.12    | 0.96       |
| REQ10 - ver outras reclamações             | 9               | 6                    | 24          | 6.53      | 5              | 7.04    | 4              | 5.12    | 0.68       |
| REQ03 - ver dados da empresa               | 8               | 7                    | 23          | 6.26      | 4              | 5.63    | 6              | 7.69    | 0.66       |
| REQ15 - feedback em caso de erro/falha     | 9               | 7                    | 25          | 6.81      | 5              | 7.04    | 5              | 6.41    | 0.66       |
| REQ01 - login gov.br                       | 9               | 9                    | 27          | 7.35      | 4              | 5.63    | 9              | 11.53   | 0.64       |
| REQ12 - funcionar em android/ios           | 9               | 9                    | 27          | 7.35      | 7              | 9.85    | 8              | 10.25   | 0.49       |
| REQ13 - interface simples e intuitiva      | 9               | 9                    | 27          | 7.35      | 7              | 9.85    | 6              | 7.69    | 0.53       |
| REQ04 - ver indicadores/gráficos dos dados| 7               | 4                    | 18          | 4.9       | 5              | 7.04    | 6              | 7.69    | 0.45       |
| REQ14 - acessibilidade                     | 7               | 4                    | 18          | 4.9       | 8              | 11.26   | 3              | 3.84    | 0.37       |


<div style="text-align: center;"><p>Tabela 3 - Tabela de Resultado da Priorização de Requisitos (Fonte: CÉSAR, Julio. 2024).</p></div>

## Link da Gravação

[Priorização - First Thing First(Mediador/Desenvolvedor)](https://youtu.be/CtUni6w0gSs)

[Priorização - First Thing First(Mediador/Usuário)](https://youtu.be/jka4Mdmq9TI)

## Bibliografia

> SERRANO, Milene, SERRANO, Maurício. Requisitos (Aula 07): Elicitação, Modelagem e Análise. UnB Gama, Brasília, 2023. Disponível em: <https://aprender3.unb.br/pluginfile.php/2692772/mod_resource/content/2/Requisitos%20-%20Aula%2007.pdf>. Acesso em: 17/04/2024.


## Histórico de Versão

| Versão | Data de Execução | Data de Revisão | Descrição                            | Autor(es)                               | Revisor(es) |
| ------ | ---------------- | --------------- | ------------------------------------ | --------------------------------------- | ----------- |
| `1.0`    | 17/04/2024       | 17/04/2024      | Criação da priorização first things first     | [Júlio Cesar](https://github.com/Julio1099), [Igor Thiago](https://github.com/Alladin-51) | [Guilherme Meister](https://github.com/gmeister18)    |

