# Análise de Documentos

## Introdução

Este documento tem como objetivo elicitar e documentar os requisitos de software para o aplicativo Consumidor.gov, utilizando a técnica de análise de documentos. O Consumidor.gov é um app com a finalidade de fornecer um canal direto de comunicação entre consumidores e empresas para a resolução de conflitos de consumo. O aplicativo é executado em várias plataformas, incluindo Windows, Mac, Linux e dispositivos móveis.

## Metodologia

A técnica utilizada neste documento é a análise de documentos. Essa técnica é particularmente útil quando os requisitos do software estão implícitos em documentos existentes e podem ser extraídos por meio de uma análise cuidadosa do conteúdo. A análise de documentos é uma técnica complementar a outras técnicas de elicitação de requisitos, para obter uma visão abrangente dos requisitos do software.

## Elicitação de Requisitos do Aplicativo

### Funcionalidades e Recursos

- Interlocução entre consumidores e empresas:
    - Ambiente totalmente público e transparente, dispensada a intervenção do Poder Público. [Documentação do Consumidor.gov](https://www.consumidor.gov.br/pages/conteudo/publico/1)
    - Fornecimento de informações essenciais à elaboração e execução de políticas públicas de defesa dos consumidores. [Documentação do Consumidor.gov](https://www.consumidor.gov.br/pages/conteudo/publico/1)
    - Possibilidade de ler o conteúdo das reclamações, respostas das empresas e comentário final dos consumidores.

### Requisitos Técnicos

- Sistemas operacionais suportados: Android e iOS [Página de download Consumidor.gov](https://play.google.com/store/apps/details?id=br.com.consumidor&hl=pt_BR&gl=US)

### Requisitos de Usabilidade e Acessibilidade

- Interface do usuário intuitiva e fácil de usar [Consumidor.gov User Reviews](https://apps.apple.com/br/app/consumidor-gov-br/id1492523966?see-all=reviews)
- Suporte ao modo escuro e letras maiores

### Requisitos de Segurança e Privacidade

- Respeito à privacidade do usuário e ausência de rastreamento ou coleta de dados invasiva [Política de Privacidade](https://www.consumidor.gov.br/pages/conteudo/publico/7)
- Proteção contra vulnerabilidades [Política de Privacidade](https://www.consumidor.gov.br/pages/conteudo/publico/7)

## Tabela de requisitos

| Identificação | Descrição | Categoria |
| --- | --- | --- |
| ADD01 | Possibilidade de ler o conteúdo das reclamações, respostas das empresas e comentário final. | RF |
| ADD02 |  | RF |
| ADD03 | Interlocução entre consumidores e empresas. | RF |
| ADD04 | Sistemas operacionais suportados: Android e iOS. | RNF |
| ADD05 | Interface do usuário intuitiva. | RI |
| ADD06 | Suporte ao modo escuro | RI |
| ADD07 | Suporte a fontes maiores | RI |
| ADD08 | Capacidade de lidar com grande número de empresas e usúarios. | RPR |
| ADD09 | Risco de violação de privacidade do usuário. | RR |
| ADD10 | Testes para garantir que os Fornecimento de informações funcione corretamente. | RT |
| ADD11 | Testes para garantir que o software não colete dados invasivamente. | RT |
| ADD12 | Testes para garantir que a interface do usuário seja intuitiva para todos. | RT |
| ADD13 | Testes para garantir que o software respeite a privacidade do usuário. | RT |
| ADD14 | Testes para garantir que o software tenha um bom desempenho em todos dispositivos. | RT |
<div style="text-align: center;"><p>Tabela 1 - Tabela dos requisitos levantados (Fonte: MEISTER, Guilherme. 2024).</p></div>

## Legenda

- RF: Requisitos Funcionais - Descrevem o comportamento ou a funcionalidade que o software deve ter para atender às necessidades do usuário.

- RNF: Requisitos Não-Funcionais - Descrevem os atributos que o software deve ter, como desempenho, segurança e usabilidade, mas não descrevem o comportamento do software em si.

- RI: Requisitos de Interface - Descrevem as características da interface do usuário, como layout, navegação e personalização.

- RPR: Requisitos de Produto - Descrevem as características do produto, como compatibilidade, desempenho e custo.

- RR: Riscos - São os riscos associados ao desenvolvimento e uso do software.

- RT: Testes e Validações - Descrevem as atividades necessárias para testar e validar o software antes de sua implantação.

## Bibliografia

## Histórico de Versões
| Data | Versão | Descrição | Autor(es) | Data de revisão | Revisor(es) |
| :-: | :-: | :-: | :-: | :-: | :-: |
| 15/04/2024 | `1.0` | Criando o artefato | [Guilherme Meister](https://github.com/gmeister18) | 30/04/2023 | [Henrique Galdino](https://github.com/hgaldino05) |
