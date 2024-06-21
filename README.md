# Análise do Dataset do Titanic

Este repositório contém uma análise abrangente do famoso dataset do Titanic. O objetivo desta análise é explorar os dados, identificar padrões e relacionamentos, e construir modelos preditivos para determinar a sobrevivência dos passageiros com base nas informações fornecidas.

## Descrição do Dataset

O dataset do Titanic é composto por informações sobre os passageiros do RMS Titanic, que naufragou em sua viagem inaugural em 1912. As colunas principais do dataset incluem:

- **PassengerId**: Identificador único do passageiro.
- **Survived**: Indicador de sobrevivência (0 = Não, 1 = Sim).
- **Pclass**: Classe do ticket (1 = Primeira, 2 = Segunda, 3 = Terceira).
- **Name**: Nome do passageiro.
- **Sex**: Sexo do passageiro.
- **Age**: Idade do passageiro.
- **SibSp**: Número de irmãos/cônjuges a bordo.
- **Parch**: Número de pais/filhos a bordo.
- **Ticket**: Número do ticket.
- **Fare**: Tarifa paga pelo passageiro.
- **Cabin**: Número da cabine.
- **Embarked**: Porto de embarque (C = Cherbourg, Q = Queenstown, S = Southampton).

## Objetivos da Análise

1. **Exploração de Dados**:
   - Entender a distribuição dos dados e identificar possíveis problemas de qualidade.
   - Analisar a relação entre diferentes variáveis e a sobrevivência dos passageiros.

2. **Preparação de Dados**:
   - Tratar valores faltantes e inconsistências.
   - Converter variáveis categóricas em numéricas.
   - Normalizar e padronizar os dados, se necessário.

3. **Visualização de Dados**:
   - Criar gráficos e visualizações para entender melhor os padrões nos dados.
   - Visualizar a correlação entre diferentes features e a taxa de sobrevivência.

4. **Modelagem Preditiva**:
   - Construir e avaliar modelos de machine learning para prever a sobrevivência dos passageiros.
   - Comparar o desempenho de diferentes algoritmos, como regressão logística, árvores de decisão, Random Forest e outros.

## Estrutura do Repositório

- **data/**: Contém os arquivos de dados originais e pré-processados.
- **notebooks/**: Jupyter Notebooks utilizados para a análise e modelagem do dataset.
- **results/**: Resultados da análise, incluindo visualizações e métricas de desempenho dos modelos.

## Tecnologias Utilizadas

- **Linguagem**: Python
- **Bibliotecas**: Pandas, NumPy, Matplotlib, Seaborn, Scikit-learn
- **Ferramentas**: Jupyter Notebook

## Conclusões

Nesta análise, buscamos entender os fatores que influenciaram a sobrevivência dos passageiros do Titanic e como podemos utilizar esses fatores para construir modelos preditivos eficazes. Os insights obtidos não só ajudam a melhorar a acurácia dos modelos, mas também fornecem uma compreensão mais profunda das circunstâncias em torno dessa tragédia histórica.
