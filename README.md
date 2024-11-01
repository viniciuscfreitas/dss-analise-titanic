<<<<<<< HEAD
# dss-analise-titanic
Análise de Dados e Machine Learning no Titanic: Explorando o impacto de diferentes variáveis na sobrevivência dos passageiros e construindo modelos preditivos usando Python e Scikit-Learn.
=======
# Gustavo Cristiano Pessoa de Souza - RM 551924
# Gustavo Medeiros Miranda da Silva - RM 552093
# Vinicius do Carmo Fonseca Freitas - RM 97599

# Análise de Dados e Machine Learning no Dataset Titanic

Este projeto realiza uma análise detalhada e modelagem preditiva utilizando o dataset Titanic. O objetivo é explorar o impacto de diferentes variáveis na sobrevivência dos passageiros e construir modelos para prever a sobrevivência com base nas características dos passageiros.

## Sumário
- [Introdução](#introdução)
- [Objetivos do Projeto](#objetivos-do-projeto)
- [Perguntas de Pesquisa](#perguntas-de-pesquisa)
- [Exploração de Dados (EDA)](#exploração-de-dados-eda)
- [Modelagem e Avaliação](#modelagem-e-avaliação)
- [Conclusão](#conclusão)
- [Como Usar Este Repositório](#como-usar-este-repositório)

## Introdução
Este projeto faz parte de um portfólio de análise de dados e aprendizado de máquina e explora o famoso conjunto de dados Titanic. Nele, aplicamos técnicas de EDA, pré-processamento de dados, e construímos modelos de machine learning para prever a sobrevivência dos passageiros.

## Objetivos do Projeto
- Realizar uma análise exploratória para identificar padrões nos dados.
- Responder a perguntas de pesquisa sobre as características dos passageiros.
- Construir e avaliar modelos de machine learning para prever a sobrevivência.

## Perguntas de Pesquisa
1. Qual é a taxa de sobrevivência geral?
2. A idade influencia na taxa de sobrevivência?
3. Passageiros em classes diferentes tiveram taxas de sobrevivência diferentes?
4. Qual foi o impacto do sexo dos passageiros na sobrevivência?
5. Qual a taxa de sobrevivência entre passageiros que embarcaram em diferentes portos?
6. É possível prever a sobrevivência com base nas características dos passageiros?
7. Qual é a precisão de um modelo de Regressão Logística para prever a sobrevivência?
8. Passageiros com familiares a bordo tinham uma taxa de sobrevivência maior?
9. Existe correlação entre o preço da tarifa e a sobrevivência?
10. Como modelos supervisionados podem prever a sobrevivência no Titanic?

## Exploração de Dados (EDA)
A etapa de EDA inclui:
- Visualização da taxa de sobrevivência geral.
- Análise da idade, classe e sexo dos passageiros em relação à sobrevivência.
- Gráficos de distribuição e correlação usando `seaborn` e `matplotlib`.

## Modelagem e Avaliação
Modelos construídos:
- **Regressão Logística**: Usada para prever a sobrevivência e obteve uma acurácia de aproximadamente XX%.
- **Random Forest**: Com ajuste de hiperparâmetros, obteve uma acurácia de XX%.
- **Avaliação dos Modelos**: Comparação entre os modelos com `accuracy_score` e `classification_report`.

## Conclusão
Identificamos que fatores como classe, sexo e idade têm um impacto significativo na sobrevivência dos passageiros. A regressão logística mostrou um desempenho robusto na predição da sobrevivência, enquanto o Random Forest melhorou a acurácia após otimização.

## Como Usar Este Repositório
1. Clone o repositório:
   ```bash
   git clone https://github.com/viniciuscfreitas/dss-analise-titanic.git
   ```
2. Instale as bibliotecas necessárias:
   ```bash
   pip install pandas seaborn matplotlib scikit-learn
   ```
3. Adicione o arquivo `titanic.csv` na raiz do repositório.
4. Abra o notebook `Projeto_Titanic_Notebook_Portugues.ipynb` para explorar o código e executar as análises.
>>>>>>> a643909 (Adiciona README e notebook finalizado)
