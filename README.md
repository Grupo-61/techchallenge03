# Tech Challenge 3 (Fase 3): Construção de Modelos de Machine Learning e Dashboard


**Tech Challenge** é um projeto que reúne a aplicação dos conhecimentos adquiridos em todas as disciplinas de uma fase da Especialização em Machine Learning Engineering da FIAP PosTech.

Para o Tech Challenge 3, o desafio proposto foi o seguinte:

> 📢 **Problema:** construa Modelos de Machine Learning à partir da coleta de dados, cumprindo as **etapas da Pipeline de Analytics** e, por fim, **consumo e apresentação do modelo por meio de uma aplicação e/ou Dashboard.**

Para este desafio as entregas devem ser realizadas utilizando bibliotecas de **Tratamento e construção de modelos de Machine Learning**, tais como Pandas e SKLearn e atender aos seguintes **Requisitos/objetivos**:

• **Requisito 1:** construa uma API que colete dados (se possível, em tempo real) e armazene isso em um banco de dados convencional, uma estrutura de DW ou até mesmo um Data Lake (se quiser, utilize a mesma ideia da fase 2, inclusive a fonte de dados).

• **Requisito 2:** construa um modelo de ML à sua escolha que utilize essa base de dados para treinar o mesmo.

• **Requisito 3:** seu modelo deve ser produtivo (alimentar uma aplicação simples ou um dashboard).

## 📌 Objetivos

- Elaborar a **Arquitetura do projeto**, demonstrando todas as fases da Pipeline de Analytics;
- Consumir dados de um dataset que atenda aos requisitos de qualidade para produção de bons modelos de Machine Learning;
- Percorrer etapas consistentes de um pipeline de Analytics;
- Implementar as soluções por meio do uso das tecnologias demandadas;
- Documentar o projeto de forma a permitir a sua reprodução;
- Disponibilizar a documentação em um repositório no **GitHub**.

## Possíveis dores

- Definição de um bom dataset que atenda aos requisitos de qualidade para a produção de bons modelos de Machine Learning;
- Baixa qualidade dos dados com problemas de valores faltantes (missing values) e registros inconsistentes (possíveis indícios de fraudes), por exemplo;
- Grande volume de dados, o que pode tornar o processamento lento e caro;
- Documentação sobre os dados de qualidade insuficiente;
- Definição de objetivos claros (KPIs = Key Performance Indicators), procurando o atendimento de áreas distintas.

## Proposta de solução

Em face ao desafio proposto, foi definido pela equipe o uso do modelo **CRISP-DM (Cross-Industry Standard Process for Data Mining)** como referência para a Pipeline de Analytics do projeto.

No entanto, duas etapas prévias se tornaram necessárias:

- Ingestão de dados: coleta automática de dados extraídos do (incluir a fonte??), por meio de script ??;
- Armazenamento de dados: salvamento em formato CSV (Comma Separated Values), em ??;

Em seguida, foram trabalhadas as fases do CRISP-DM:

- Business Understanding: compreensão do problema do negócio, os objetivos e critérios de sucesso;
- Data Understanding: coleta e exploração dos dados (EDA - Exploratory Data Analysis) para verificar qualidade, identificar padrões relevantes e conhecer o conjunto de dados disponíveis;
- Data Preparation: etapa de limpeza, transformação e formatação dos dados;
- Modeling: aplicação de diferentes técnicas de Machine Learning para construir modelos de dados, para o atendimento dos objetivos de negócio estabelecidos;
- Evaluation: análise dos modelos de dados desenvolvidos para verificar se os critérios de sucesso do negócio bem como qualidade do modelo foram atendidos;
- Deployment: implementação do modelo em produção na forma de uma aplicação e/pu dashboard.

**Importante**

Toda a implementação foi feita via **XPTO**?????  e foi documentada neste repositório.



### 📂 Estrutura do projeto

(inserir??)


### 🔩 Arquitetura da solução

A arquitetura da solução foi desenhada com base nos stages necessários ao atendimento de requisitos e consta na pasta de documentação deste repositório. [Link para o Diagrama](inserir figura e link??)


## Vídeo de Apresentação no Youtube
Para melhor compreensão da entrega, foi produzido um vídeo de apresentação que foi publicado no Youtube:

[Link para a Vídeo](inserir link)


## ✒️ Autores

| Nome                            |   RM    | Link do GitHub                                      |
|---------------------------------|---------|-----------------------------------------------------|
| Ana Paula de Almeida            | 363602  | [GitHub](https://github.com/Ana9873P)               |
| Augusto do Nascimento Omena     | 363185  | [GitHub](https://github.com/AugustoOmena)           |
| Bruno Gabriel de Oliveira       | 361248  | [GitHub](https://github.com/brunogabrieldeoliveira) |
| José Walmir Gonçalves Duque     | 363196  | [GitHub](https://github.com/WALMIRDUQUE)            |
| Pedro Henrique da Costa Ulisses | 360864  | [GitHub](https://github.com/ordepzero)              |

## 📄 Licença

Este projeto está licenciado sob a Licença MIT.  
Consulte o arquivo [license](docs/license/license.txt)  para mais detalhes.