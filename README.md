# Tech Challenge 3 (Fase 3): Construção de Modelos de Machine Learning e Dashboard


**Tech Challenge** é um projeto que reúne a aplicação dos conhecimentos adquiridos em todas as disciplinas de uma fase da Especialização em Machine Learning Engineering da FIAP PosTech.

Para o Tech Challenge 3, o desafio proposto foi o seguinte:

> 📢 **Problema:** construa Modelos de Machine Learning à partir da coleta de dados, cumprindo as **etapas de uma Pipeline de Análise de Dados** e, por fim, **consumo e apresentação do modelo por meio de uma aplicação e/ou Dashboard.**

Para este desafio as entregas devem ser realizadas utilizando bibliotecas de **Tratamento e construção de modelos de Machine Learning**, tais como Pandas e SKLearn e atender aos seguintes **Requisitos/objetivos**:

• **Requisito 1:** leitura de dados à partir de um dataset interessante para exploração das nuances técnicas requeridas ao projeto.

• **Requisito 2:** construção de um modelo de ML à escolha da equipe e que utilize essa base de dados para treinar o mesmo.

• **Requisito 3:** implantação do modelo construído em produção (na forma de uma aplicação simples ou um dashboard).

## 📌 Objetivos

- Consumir dados de um dataset que atenda aos requisitos de qualidade para produção de bons modelos de Machine Learning;
- Percorrer etapas consistentes de um pipeline de Análise de Dados;
- Implementar as soluções por meio do uso das tecnologias demandadas;
- Documentar o projeto de forma a permitir a sua reprodução;
- Disponibilizar a documentação em um repositório no **GitHub**.

## Possíveis dores

- Definição de um bom dataset que atenda aos requisitos de qualidade para a produção de bons modelos de Machine Learning;
- Baixa qualidade dos dados com problemas de valores faltantes (missing values) e registros inconsistentes (em regras de negócio ou fraudes, por exemplo);
- Grande volume de dados, o que pode tornar o processamento lento e caro;
- Documentação sobre os dados de qualidade insuficiente;
- Definição de objetivos claros de negócio, procurando o atendimento de áreas distintas.

## Proposta de solução

Em face ao desafio proposto, foi definido pela equipe o uso do modelo **CRISP-DM (Cross-Industry Standard Process for Data Mining)** como referência para a Pipeline de Análise de Dados do projeto.

No entanto, duas etapas prévias se tornaram necessárias:

- **Pesquisa de dataset relevante:** após amplo trabalho de pesquisa dos membros da equipe, foi definido o seguinte dataset, originalmente em formato .CSV:
 
    Ecommerce Behavior Data from Multi Category Store
    https://www.kaggle.com/datasets/mkechinov/ecommerce-behavior-data-from-multi-category-store/data

    **Importante**
    
    - O dataset original encontra-se dividido em 7 partes correspondentes aos meses de Outubro/2019, Novembro/2019, Dezembro/2019, Janeiro/2020, Fevereiro/2020, Março/2020 e Abril/2020
    - Para este cenário, o volume de dados é de 16.45 GB
    
    Como não é requisito deste projeto trabalhar com tal volume de dados, decidimos por fazer um recorte de alguns dias de operações de e-commerce:

    - Datas selecionadas: 01/12/2019, 01/01/2020, 01/02/2020, 01/03/2020 e 01-04-2020 - seleção de datas de início de mês de 6 meses da amostra, o que poderia capturar comportamentos interessantes de consumo.
    - Com este recorte, foram extraídas 499.995 linhas e 9 colunas
    - Para este cenário, o volume de dados é de 207.73 MB

Após a leitura dos dados (CSV), em seguida, foram trabalhadas as fases do **CRISP-DM**:

- **Business Understanding:** compreensão do problema do negócio, os objetivos e critérios de sucesso;
- **Data Understanding:** coleta e exploração dos dados (EDA - Exploratory Data Analysis) para verificar qualidade, identificar padrões relevantes e conhecer o conjunto de dados disponíveis - à partir desta análise, pode-se observar oportunidades de modelos analíticos. Também nesta etapa, uma série de inferências se torna possível à partir de análises estatísticas exploratórias por meio de tabelas e gráficos;
- **Data Preparation:** etapa de limpeza, transformação e formatação dos dados;
- **Modeling:** aplicação de diferentes técnicas de Machine Learning para construir modelos de dados, para o atendimento dos objetivos de negócio estabelecidos;
- **Evaluation:** análise dos modelos de dados desenvolvidos para verificar se os critérios de sucesso do negócio bem como qualidade do modelo foram atendidos;
- **Deployment:** implementação do modelo em produção na forma de uma aplicação e/pu dashboard. A integração do modelo construído com a aplicação/dashboard se deu por meio da exportação de dados para testes (no formato CSV) e modelos treinados (no formato  Pickle).

**Importante**

Toda a implementação foi feita usando **Python e bibliotecas**, tais como:

- Tratamento de dados e Análises: Pandas
- Gráficas: MatplotLib e Seaborn
- Machine Learning - Scikit Learn (SKLearn): K-Means, RandomForestClassifier e Logistic Regression 
- Outras bibliotecas complementares de tratamento e avaliação do modelo tais como StandardScaler, Silhouete Score, Classification Report, Joblib e outras
- Aplicação com Dashboard: Streamlit


### 📂 Estrutura do projeto

```
.
├── techchallenge03
│   ├── datasets
│   ├── streamlitapp
│ .gitignore
| README.md
| requirements.txt
| Tech Challenge 3.ipynb
```


## Vídeo de Apresentação no Youtube
Para melhor compreensão da entrega, foi produzido um vídeo de apresentação que foi publicado no Youtube:

[Link para a Vídeo](https://www.youtube.com/watch?v=xTFogDyhg9o)


## Link Público da  API no Streamlit
Para o atendimento do Requisito 3, a aplicação foi implementada no StreamLit e pode ser acessada pelo link:

[Link para a Aplicação](https://tech-challenge-3-grupo64.streamlit.app/)


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