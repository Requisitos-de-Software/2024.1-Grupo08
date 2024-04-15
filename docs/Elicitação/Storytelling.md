# Storytelling (Histórias)

## Introdução

_Storytelling_ é a elaboração de histórias narrativas fictícias sobre usuários usando a aplicação. O objetivo dessa técnica é providenciar um exemplo mais claro das exigências e necessidades do usuário. Em uma narrativa, é mais fácil para a equipe de desenvolvimento entender as preferências e motivações de um usuário na utilização do software.

### Vantagens

- Uma história relevante e cativante ajuda a aumentar o engajamento dos seus seguidores nas plataformas em que você publica o seu conteúdo.
- O storytelling permite formar uma comunidade, unindo as pessoas através de personagens com os quais elas podem se identificar.
- Conteúdo criativo. 

### Desvantagens

- Pode ser custoso e exigir tempo.
- Se a história não tiver uma situação ou personagens verossímeis, pode parecer forçada e conseguir o efeito contrário. 

## Metodologia

Para o desenvolvimento e realização do _storytelling_, foi utilizado as personas desenvolvidas e a observação de objetivos, sentimentos e tarefas dos usuários dentro de suas histórias e contexto. Por fim, elencamos alguns dos requisitos.

## Storytelling

### O boneco do GOAT

&emsp;&emsp;[Jorge Serafim](https://github.com/Requisitos-de-Software/2024.1-Consumidor.gov/blob/main/assets/img/Elicita%C3%A7%C3%A3o/jorge.jpeg), cardiologista experiente e recordista de cubo mágico em Goiás, vivia uma rotina frenética entre consultas, academia e NBA. Mas, em meio à agitação, havia um espaço especial para seu filho, prestes a completar 10 anos. Buscando o presente ideal, Jorge comprou um boneco do atleta Lebron James pela internet, imaginando a alegria do pequeno.

&emsp;&emsp;Qual não foi sua surpresa ao receber o produto: totalmente diferente das fotos, com defeito e sem a qualidade esperada. A frustração deu lugar à indignação. Jorge, habituado à precisão e à eficiência do mundo médico, não se intimidou e partiu para a ação. Tentou contato com a empresa por todos os canais possíveis, mas o silêncio era a única resposta. Sem perder a calma, ele recorreu ao Consumidor.gov, plataforma criada para defender os direitos dos consumidores. 

&emsp;&emsp;Na plataforma, Jorge narrou sua saga em busca do boneco perfeito, anexando fotos, comprovantes e detalhando a omissão da empresa. A cada dia que passava, a esperança de ver seu filho brincar com o boneco do melhor jogador de basquete da história se misturava à frustração com a falta de resposta. Dias se transformaram em semanas, e a resposta finalmente chegou. A empresa, pressionada pela ação no Consumidor.gov, ofereceu duas opções: estorno do valor pago ou troca do boneco. Jorge, sempre pensando no melhor para seu filho, optou pela troca.

&emsp;&emsp;Após a árdua batalha, a alegria reinou. O boneco perfeito chegou, e o sorriso no rosto do pequeno era a recompensa que Jorge buscava. 

### A Desilusão da Paleta

&emsp;&emsp;[Bianca Torquato](https://github.com/Requisitos-de-Software/2024.1-Consumidor.gov/blob/main/assets/img/Elicita%C3%A7%C3%A3o/bianca.jpeg), estudante de psicologia e influenciadora digital apaixonada por moda e beleza, se rendeu à paleta de sombras da Wepink, marca da influenciadora Virginia. As cores vibrantes prometiam looks incríveis, mas a paleta veio com a maquiagem quebrada, o que entristeceu muito a Bianca.

&emsp;&emsp;Com suas habilidades de comunicação impecáveis, detalhou a situação em sua reclamação, anexando fotos e vídeos que comprovavam os defeitos no produto recebido. Bianca compartilhou sua experiência com seus seguidores nas redes sociais, alertando-os sobre a falha da empresa e incentivando-os a sempre buscar seus direitos

&emsp;&emsp;Após semanas de espera, a Wepink reconheceu o erro e ofereceu duas opções: reembolso ou troca. Bianca, decepcionada com a marca, optou pelo reembolso. E graças ao consumidor.gov conseguiu resolver o problema com a marca o mais rápido possível.

## Requisitos Elicitados

&emsp;&emsp;Com base nas histórias criadas no storytelling, foram elicitados os requisitos presentes na tabela 1:


| Identificador | Descrição                                                                          | Tipo | Implementado | Persona |
| ------------- | ---------------------------------------------------------------------------------- | ---- | ------------ | ------- |
|       ST01    |   Eu, como usuário, gostaria de fazer reclamações acerca de um produto específico                                 |  RF  | Sim          | Todas |
| ST02          | Eu, como usuário, gostaria de acompanhar do status da reclamação .                      | RF   | Sim          | Todas |
| ST03          | Eu, como usuário, gostaria da Resolução de conflitos .             | RF   | Sim          | Todas |
| ST04          | Eu, como usuário, gostaria de Histórico de reclamações.     | RF   | Não          | Todas |
| ST05          | Eu, como usuário, gostaria de Avaliação de empresas.                    | RF   | Sim          | [Jorge Serafim](https://github.com/Requisitos-de-Software/2024.1-Consumidor.gov/blob/main/assets/img/Elicita%C3%A7%C3%A3o/jorge.jpeg) |
| ST06          | Eu, como usuário, gostaria de Integração com redes sociais.                       | RF   | Não          | [Bianca Torquato](https://github.com/Requisitos-de-Software/2024.1-Consumidor.gov/blob/main/assets/img/Elicita%C3%A7%C3%A3o/bianca.jpeg) |
| ST07          | Eu, como usuário, gostaria de Anexação de arquivos.        | RNF  | Sim          | Todas |
| ST08          | Eu, como usuário, gostaria de gostaria de uma interface acessível com contraste de cor .                                | RNF   | Sim          | [Bianca Torquato](https://github.com/Requisitos-de-Software/2024.1-Consumidor.gov/blob/main/assets/img/Elicita%C3%A7%C3%A3o/bianca.jpeg)|
| ST09          | Eu, como usuário, gostaria de gostaria de que o aplicativo tenha suporte ao usuário. | RF | Não          | [Bianca Torquato](https://github.com/Requisitos-de-Software/2024.1-Consumidor.gov/blob/main/assets/img/Elicita%C3%A7%C3%A3o/bianca.jpeg) |
| ST10          | Eu, como usuário, gostaria de gostaria de que o aplicativo tenha tutorial.                | RF   | Não          | [Bianca Torquato](https://github.com/Requisitos-de-Software/2024.1-Consumidor.gov/blob/main/assets/img/Elicita%C3%A7%C3%A3o/bianca.jpeg) |
| ST11          | Eu, como usuário, gostaria de gostaria de que o aplicativo tenha acessibilidade.                              | RF   | Sim          |  |
| ST12          | Eu, como usuário, gostaria de gostaria de realizar registro/login em uma conta.                                       | RF   | Sim          | [Jorge Serafim](https://github.com/Requisitos-de-Software/2024.1-Consumidor.gov/blob/main/assets/img/Elicita%C3%A7%C3%A3o/jorge.jpeg) |
| ST13          | Eu, como usuário, gostaria de .                                     | RF   | Sim          |  |
| ST14          | Eu, como usuário, gostaria de .                        | RF   | Sim          |  |
| ST15          | Eu, como usuário, gostaria de .      | RF   | Sim          |  |
| ST16          | Eu, como usuário, gostaria de .                | RNF   | Sim          |  |
| ST17          | Eu, como usuário, gostaria de .           | RF   | Não          |  |
| ST18          | Eu, como usuário, gostaria de .                     | RF   | Sim          |  |
| ST19          | Eu, como usuário, gostaria de .               | RF   | Não          |  |

<div style="text-align: center">
<p> Tabela 1: Requisitos elicitados com o Storytelling (Fonte: Guilherme, 2024).</p>
</div>

**Legenda:**

- ST: Requisitos de <span>_Storytelling_</span>
- RF: Requisitos <span>Funcionais</span>
- RNF: Requisitos não <span>Funcionais</span>




## Histórico de Versão
| Versão | Data          | Descrição           | Autor(es)     |  Revisor(es)  |
| ------ | ------------- | ---------------------------------- | ------------- | ------------- |
| `1.0`  | 04/04/2024 | Criação do documento | [Guilherme Meister](https://github.com/gmeister18) e [Matheus Ferreira](https://github.com/matferreira1) | [Henrique Galdino](https://github.com/hgaldino05) e [Rodrigo ](https://github.com/rodrigogontijoo) |
