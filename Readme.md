# <p align="center">Análise de dados Exploratória da vacinação contra a COVID-19</p>

 ![capa](https://github.com/Jonatas-Gomes/A3-BigData/assets/57242457/fc731d86-4cd7-45b6-8248-9e83d153429c)

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
- [Insights ](#3-insights)
- [Ferramentas](#ferramentas)
- [Conclusão](#conclusão)
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
  Os objetivos deste estudo é realizar uma Análise Exploratória (Exploratory Data Analysis - EDA) do conjunto de dados da vacinação contra a COVID 19, disponível na pasta [data](https://github.com/Jonatas-Gomes/A3-BigData/tree/main/data);  a fim  de  caracterizar o perfil dos vacinados contra a COVID-19 por estado, região e data. Especificamente serão respondidas as seguintes questões de pesquisa:
<details>
  <summary>Qual dia da semana teve a maior média de doses aplicadas?</summary>
  
   [O dia da semana com a maior média de doses aplicadas foi quarta-feira, com 824.631 doses aplicadas.](#4-vacinação-por-datamês-ano-dia-da-semana)
</details>

<details>
  <summary>Qual foi o total de doses aplicadas em SP?</summary>
 
   [O total de doses aplicadas em SP foi de 131 milhões](#2-total-de-vacinação-por-estado)
</details>

<details>
  <summary>Qual foi o ano com o maior numero de doses aplicadas?</summary>
 
   [O ano com o maior numero foi 2021 com 341.839.264 milhões de doses aplicadas](#4-vacinação-por-datamês-ano-dia-da-semana)
</details>

<details>
  <summary>Qual foi a regiao com o menor numero de doses aplicadas?</summary>
 
   [Centro oeste com 13.678.978 de vacinados com a primeira dose](#3-total-de-vacinação-por-região)
</details>

<details>
  <summary>Qual foi a dose com o menor numero de aplicação e por quê?</summary>
 
   [O menor numero de aplicação foi na terceira dose. Segundo o potal g1, falta campanhas de alerta para a necessidade da vacinação completa.](#3-total-de-vacinação-por-região)
</details>

## 2. Metodologia
  ![Metodologia](https://github.com/Jonatas-Gomes/A3-BigData/assets/57242457/a20f9954-ccd5-45af-ad71-db444dae8d39)
## Observações

## 2.1 Configuração do Ambiente
  Para o processo de ETL(extração, transformação e leitura dos dados) foi utilizada ferramenta Microsoft Power BI. 
 ![Conf_ambient](https://github.com/Jonatas-Gomes/A3-BigData/assets/57242457/e1184e7a-ff75-4e14-9c15-4ee53408adec)
## 2.2 Visão Geral do Conjunto de Dados
  ![visaogeral](https://github.com/Jonatas-Gomes/A3-BigData/assets/57242457/24686b7b-2a0f-43cb-ab32-d602d75dbc30)
  ![ConjuntoDeDados](https://github.com/Jonatas-Gomes/A3-BigData/assets/57242457/62916921-3266-482a-9ace-3371a8ed00d3)

## 2.3 Remoção de Colunas
  ![newremo_colunms](https://github.com/Jonatas-Gomes/A3-BigData/assets/57242457/de40bdde-a61b-4896-917a-77581848deaa) 

## 2.4 Mapeamento de Dados
  
## 2.5 Dados Ausentes
  ![ausentes](https://github.com/Jonatas-Gomes/A3-BigData/assets/57242457/af815179-ae77-45e0-a251-50a5d10c4a45)
## 2.6 Feature Engineering
  ![eng_recursos](https://github.com/Jonatas-Gomes/A3-BigData/assets/57242457/2a297506-970c-4239-b7d3-7c9b031d1508)  
## 3 Insights 
  ### 1. Menu
  ![card_1](https://github.com/Jonatas-Gomes/A3-BigData/assets/57242457/e36bd086-c0d0-4233-b971-ae9625160462)
  ### 2. Total de vacinação por estado
  O gráfico abaixo apresenta a soma de doses aplicadas por estado
  ![card_2](https://github.com/Jonatas-Gomes/A3-BigData/assets/57242457/dd6527aa-3be5-43cc-b397-1f632454d8d6)
  ### 3. Total de vacinação por região
  O gráfico abaixo apresenta o total de vacinação por dose e região.
  ![vacina_regioon](https://github.com/Jonatas-Gomes/A3-BigData/assets/57242457/77d1686b-139e-4529-a672-3325a09db180)
  ### 4. Vacinação por data(Mês, Ano, Dia da semana)
  O gráfico abaixo apresenta a média de aplicação da vacina por dia da semana, mês e ano.
  ![card_5](https://github.com/Jonatas-Gomes/A3-BigData/assets/57242457/eba879a5-eb09-490b-91a1-4f031740e3a5)

## Ferramentas
 - PowerBI
## Conclusão
 A análise de dados sobre as datas de vacinação contra a COVID-19 aborda o problema de monitorar o progresso e a cobertura vacinal, fornecendo informações atualizadas sobre o número de pessoas vacinadas em diferentes períodos de tempo.

A análise de dados sobre as datas de vacinação foi criada para garantir que a imunização esteja ocorrendo de maneira adequada e eficiente. Ela permite avaliar se o cronograma estabelecido está sendo seguido, se os grupos prioritários estão sendo alcançados e se não há lacunas na cobertura vacinal, pois a falta de acompanhamento adequado dos dados de vacinação pode levar a atrasos na imunização, desigualdades no acesso às vacinas e uma resposta inadequada à pandemia.

Em conclusão, a análise dos dados da COVID-19 destaca a importância das medidas de saúde pública, da vacinação em massa e da adoção de políticas equitativas para enfrentar os desafios impostos pela pandemia.

## Referências
- Link dos conjuntos de dados:
https://infoms.saude.gov.br/extensions/SEIDIGI_DEMAS_Vacina_C19/SEIDIGI_DEMAS_Vacina_C19.html#


