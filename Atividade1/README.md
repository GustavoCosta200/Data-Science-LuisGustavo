# Análise de Produção de Água Mineral

Este projeto contém um **notebook de ciência de dados** desenvolvido
para explorar o dataset de produção de água mineral, realizando uma
análise descritiva e estatística inicial.

## Conteúdo

-   **Descrição do Dataset**
    -   Nome do dataset: Produção de Água Mineral
    -   Fonte: [dados.gov.br](https://dados.gov.br/dados/conjuntos-dados/anuario-mineral-brasileiro-amb)
    -   Órgão responsável: Agência Nacional de Mineração
    -   Objetivo: Monitorar a produção de água mineral por estado e período.
-   **Exploração Estatística**
    -   Estatísticas descritivas (média, mediana, moda, desvio padrão,
        quartis, IQR)
    -   Contagem de valores ausentes
    -   Tipos de dados identificados
    -   Visualizações: histogramas, boxplots e gráfico de dispersão

## Tecnologias Utilizadas

-   Python 3.x
-   pandas
-   numpy
-   matplotlib
-   seaborn

## Como Utilizar

1.  Abra o notebook `analise_producao_agua.ipynb` no **Jupyter
    Notebook**, **JupyterLab** ou **Google Colab**.
2.  Certifique-se de ter o arquivo CSV original:
    `Producao_Agua - Agua_Mineral_Producao.csv` na mesma pasta.
3.  Execute as células na ordem para reproduzir as análises.

## Comentários

- É possível identificar a distribuição dos valores de produção por meio de histogramas.
- Em alguns anos, a quantidade de dados obtidos foi menor.
- O boxplot ajuda a identificar outliers (valores muito acima ou abaixo do esperado).
- Em alguns estados, a venda de um tipo específico de embalagem de água é maior
- A estatística descritiva mostra média, mediana e moda: diferenças entre elas podem indicar assimetria na distribuição.
- Em alguns tipos de embalagem, há grande quantidade de valores 0, indicando que esta forma de vender água é bastante rara em vários estados.
- A análise do IQR mostra a dispersão central e ajuda a entender a variabilidade.
- Esta análise é bastante afetada pela quantidade de estados que não vendem determinados tipos de embalagem de água.
- A dispersão pode ser utilizada para verificar o preço e a quantidade de água realizadas ao comprar
    
