# **Relatório do Projeto de Visualização de Dados de Vendas e Despesas usando Seaborn**

## **1\. Introdução**

Este projeto demonstra a aplicação prática da biblioteca Seaborn na visualização de dados do mundo real, especificamente na área de negócios. O objetivo principal é apresentar como o Seaborn pode ser utilizado para analisar e interpretar dados financeiros, como vendas e despesas.

## **2\. Metodologia**

O projeto foi desenvolvido utilizando as bibliotecas Seaborn e Pandas em Python. A metodologia pode ser dividida nas seguintes etapas:

1. **Geração de DataFrame Inicial:**  
   * Foi criado um DataFrame do Pandas para simular dados de vendas.  
   * O DataFrame contém a coluna:  
     * `Vendas`: Valores das vendas.  
   * Os dados de `Vendas` foram gerados aleatoriamente para simular diferentes valores de vendas.  
2. **Visualização do Histograma de Vendas:**  
   * A biblioteca Seaborn foi utilizada para criar um histograma, visualizando a distribuição de frequência dos valores de vendas.  
   * O histograma permite a análise da distribuição dos dados financeiros, identificando a frequência com que diferentes valores ocorrem.  
3. **Adição de Dados de Despesas:**  
   * Foram adicionados dados fictícios de despesas ao DataFrame.  
   * O DataFrame agora contém a coluna:  
     * `Despesas`: Valores das despesas.  
4. **Visualização do Boxplot de Vendas e Despesas:**  
   * A biblioteca Seaborn foi utilizada para criar um boxplot, visualizando a distribuição estatística dos valores de vendas e despesas.  
   * O boxplot permite a comparação da distribuição estatística entre as duas variáveis.  
5. **Adição de Dados de Mês:**  
   * Foram adicionados dados de mês ao DataFrame.  
   * O DataFrame agora contém a coluna:  
     * `Mês`: Nomes dos meses do ano.  
6. **Visualização do Gráfico de Barras de Vendas por Mês:**  
   * A biblioteca Seaborn foi utilizada para criar um gráfico de barras, visualizando as vendas por mês.  
   * O gráfico de barras permite a análise da evolução das vendas ao longo do tempo.  
7. **Estruturação dos Dados:**  
   * O DataFrame foi utilizado para representar os fatos (vendas e despesas) e as medidas (valores de vendas e despesas).  
   * A coluna `Mês` representa a dimensão de tempo.  
   * As colunas `Vendas` e `Despesas` representam as medidas dos fatos.

## **3\. Resultados**

1. **DataFrame Inicial:**  
   * Foi criado um DataFrame contendo dados simulados de vendas.  
   * Este DataFrame representa a estrutura básica dos dados de vendas.  
2. **Histograma de Vendas:**  
   * Foi gerado um histograma utilizando o Seaborn para visualizar a distribuição de frequência dos valores de vendas.  
   * O histograma mostra a frequência com que diferentes valores de vendas ocorrem, permitindo identificar a concentração dos dados e a presença de outliers.  
3. **DataFrame com Despesas:**  
   * Foram adicionados dados fictícios de despesas ao DataFrame, permitindo a análise comparativa entre vendas e despesas.  
4. **Boxplot de Vendas e Despesas:**  
   * Foi gerado um boxplot utilizando o Seaborn para visualizar a distribuição estatística dos valores de vendas e despesas.  
   * O boxplot mostra a mediana, quartis, valores mínimo e máximo, e outliers para ambas as variáveis, fornecendo uma visão geral da distribuição e identificando valores atípicos.  
5. **DataFrame com Mês:**  
   * Foram adicionados dados de mês ao DataFrame, permitindo a análise da evolução das vendas ao longo do tempo.  
6. **Gráfico de Barras de Vendas por Mês:**  
   * Foi gerado um gráfico de barras utilizando o Seaborn para visualizar as vendas por mês.  
   * O gráfico mostra a variação das vendas ao longo dos meses, permitindo identificar tendências sazonais e meses de maior ou menor desempenho.

## **4\. Conclusão**

Este projeto demonstrou como utilizar a biblioteca Seaborn para visualizar a distribuição de dados de vendas, a distribuição estatística comparativa de vendas e despesas, e a evolução das vendas ao longo do tempo. A organização do relatório seguiu a ordem do código, facilitando a compreensão do fluxo de trabalho e a interpretação dos resultados.

A visualização dos dados em um histograma permite uma análise mais intuitiva das informações de vendas, facilitando a identificação da concentração dos dados e a presença de valores atípicos. O boxplot oferece uma visão geral da distribuição estatística de vendas e despesas, identificando valores atípicos e fornecendo insights adicionais sobre a dispersão e assimetria dos dados. O gráfico de barras permite a análise da variação das vendas ao longo dos meses, auxiliando na identificação de tendências sazonais e na compreensão do desempenho mensal.

