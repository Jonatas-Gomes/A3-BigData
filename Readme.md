# Análise de dados Exploratória da vacinação contra a COVID-19

 <img width = 1200 height=350 alt="capa-image" src="https://github.com/Jonatas-Gomes/A3-BigData/assets/57242457/48ef8d96-c8b8-48d7-a979-d211eab9459b">

## Sumário 
- [Introdução](#1-introdução)
- [Objetivos](#11-objetivos)
- [Metodologia](#2-metodologia)
- [Observações](#observações)
- [Configuração do Ambiente](#21-configuração-do-ambiente)
- [Visão Geral do Conjunto de Dados](#22-visão-geral-do-conjunto-de-dados)
- [Remoção de Colunas](#23-remoção-de-colunas)
- [Mapeamento de Dados](#24-mapeamento-de-dados)
- [Dados Ausentes](#25-dados-ausentes)
- [Feature Engineering](#26-feature-engineering)
- [Análise de Dados](#3-análise-de-dados)
- [Insights ](#31-insights)
- [Referências](#referências)


## 1. Introdução
 A análise de dados é um processo que tem sido cada vez mais utilizado para extrair insights e informações relevantes a partir de grandes volumes de dados. Neste projeto, realizamos uma análise    exploratória de dados em um conjunto de dados a fim de caracterizar o perfil dos vacinados contra a COVID-19 por estado, região e data.
 
**Fonte dos dados:**

Os dados utilizados neste projeto foram obtidos a partir de informações fornecidas pelo Ministério da Saúde, contendo elementos sobre o quantitativo da população vacinada para COVID-19 no Brasil. A planilha contém informes sobre diferentes variáveis no que tange ao panorama de vacinação nacional, como a vacinação por estado e região, por data e por dose aplicada. Além disso, cada um desses levantamentos pode ser estratificado por região do Brasil, o que amplia a possibilidade de análises que relacionem estados, cidades e regiões em detrimento ao Brasil. 

**Escopo do projeto:**

O escopo do projeto de análise de dados foi delimitado pela disponibilidade das informações pelo Ministério da Saúde e pelo objetivo de identificar padrões e tendências do panorama de vacinação contra a COVID-19 a nível nacional, associado às suas variáveis.

**Método de análise:**

A análise descritiva da cobertura vacinal no Brasil é uma abordagem importante para compreender o panorama da imunização no país. Por meio dessa análise, são utilizadas técnicas e métricas para descrever e resumir os dados disponíveis, como a taxa de cobertura vacinal, distribuição geográfica, evolução temporal e dados demográficos. Essas informações são fundamentais para identificar áreas de melhoria, direcionar estratégias de vacinação e garantir uma cobertura vacinal abrangente e equitativa em toda a população brasileira

**Contribuições:**

A análise descritiva da cobertura vacinal da COVID-19 no Brasil revelou informações importantes sobre o progresso da imunização. Foram identificados os seguintes insights:
A cobertura vacinal geral, ou seja, a proporção da população vacinada, foi calculada, fornecendo uma visão geral do avanço da vacinação.
A evolução temporal da cobertura vacinal foi observada, ajudando a compreender fatores que influenciaram a adesão da população.
Variações regionais na cobertura vacinal foram identificadas, direcionando recursos e esforços para áreas com menor adesão.
Essas informações são relevantes para orientar estratégias de saúde pública, direcionar recursos e tomar decisões mais eficazes na campanha de vacinação contra a COVID-19.

**Organização do relatório:**

1- Introdução
Breve introdução sobre a importância da análise da cobertura vacinal no contexto da pandemia da COVID-19.
Objetivos da análise descritiva.

2-  Métodologia 
Descrição dos métodos e técnicas utilizados na coleta e análise dos dados.
Explicação das fontes de dados utilizadas e sua confiabilidade.

3- Ánalise de dados 
Apresentação dos principais insights obtidos a partir da análise descritiva.
Discussão dos resultados e interpretação dos dados.


## 1.1. Objetivos
  Os objetivos deste estudo é realizar uma Análise Exploratória (Exploratory Data Analysis - EDA) do conjunto de dados da vacinação contra a COVID 19, disponível em(vou linkar a pasta); a fim  de       caracterizar o perfil dos vacinados contra a COVID-19 por estado, região e data. Especificamente serão respondidas as seguintes questões de pesquisa:
  - 1 [Quantidade de vacinação em 1ª dose](#4-proporção-de-doses-aplicadas)
  - 2 [Quantidade de vacinação em 2021](#5-vacinação-por-datamês-ano-dia-da-semana)
  - 3 [Quantidade de vacinação no Sudeste](#3-total-de-vacinação-por-região)
  - 4 [Quantidade de vacinação em 2ª dose](#4-proporção-de-doses-aplicadas)
  - 5 [Quantidade de vacinação em 3ª dose](#4-proporção-de-doses-aplicadas)

## 2. Metodologia
  ![Metodologia](https://github.com/Jonatas-Gomes/A3-BigData/assets/57242457/51240dd5-8697-43a6-844b-adfc77cd2348)
## Observações

## 2.1 Configuração do Ambiente
  Para o processo de ETL(extração, transformação e leitura dos dados) foi utilizada ferramenta Microsoft Power BI. 
 ![Conf_ambient](https://github.com/Jonatas-Gomes/A3-BigData/assets/57242457/e1184e7a-ff75-4e14-9c15-4ee53408adec)
## 2.2 Visão Geral do Conjunto de Dados
  ![visaogeral](https://github.com/Jonatas-Gomes/A3-BigData/assets/57242457/24686b7b-2a0f-43cb-ab32-d602d75dbc30)

## 2.3 Remoção de Colunas
  ![remo_colum](https://github.com/Jonatas-Gomes/A3-BigData/assets/57242457/002138e3-1f2b-4b59-b203-0644e8a975c7)

## 2.4 Mapeamento de Dados
  
## 2.5 Dados Ausentes
  ![dados_ausentes](https://github.com/Jonatas-Gomes/A3-BigData/assets/57242457/ef384a66-0deb-49b0-85ce-f5d415d90d5b)
## 2.6 Feature Engineering
  ![feature_engineering](https://github.com/Jonatas-Gomes/A3-BigData/assets/57242457/2941642f-f91d-41bb-be09-a9ab7e4383e0)

## 3. Análise de Dados
  
## 3.1 Insights 
  ### 1. Menu
  ![card_1](https://github.com/Jonatas-Gomes/A3-BigData/assets/57242457/e36bd086-c0d0-4233-b971-ae9625160462)
  ### 2. Total de vacinação por estado
  ![card_2](https://github.com/Jonatas-Gomes/A3-BigData/assets/57242457/dd6527aa-3be5-43cc-b397-1f632454d8d6)
  ### 3. Total de vacinação por região
  ![card_3](https://github.com/Jonatas-Gomes/A3-BigData/assets/57242457/2c32a9b4-2522-491e-be35-5c5b5245c103)
  ### 4. Proporção de doses aplicadas
  ![card_4](https://github.com/Jonatas-Gomes/A3-BigData/assets/57242457/235950ee-ecd0-4676-a6de-791e89c1b2a2)
  ### 5. Vacinação por data(Mês, Ano, Dia da semana)
  ![card_5](https://github.com/Jonatas-Gomes/A3-BigData/assets/57242457/eba879a5-eb09-490b-91a1-4f031740e3a5)

## Referências
- Link dos conjuntos de dados:
https://infoms.saude.gov.br/extensions/SEIDIGI_DEMAS_Vacina_C19/SEIDIGI_DEMAS_Vacina_C19.html#


