## Análise Exploratória de Dados de Montanhas Russas

Este projeto explora um conjunto de dados sobre montanhas russas, utilizando técnicas de Análise Exploratória de Dados (EDA) para entender a estrutura dos dados, identificar padrões e tendências, e obter insights sobre as relações entre diferentes variáveis.
Estrutura do Projeto

    coaster_db.csv: Arquivo de dados original.
    README.md: Este arquivo de documentação.
    exploratory_data_analysis.ipynb: Notebook Jupyter com o código Python que conduz a análise.

## Dependências

Certifique-se de ter as seguintes bibliotecas Python instaladas:

  *  pandas
  *  numpy
  *  matplotlib
  *  seaborn

## Processo de Análise

    Importação e Leitura dos Dados:
        O conjunto de dados coaster_db.csv é lido em um DataFrame Pandas.
        Uma seleção inicial de colunas relevantes é feita para a análise.

    Limpeza e Transformação de Dados:
        Conversão de tipos de dados (por exemplo, datas).
        Renomeação de colunas para maior clareza.
        Tratamento de valores ausentes e duplicados.

    Análise Descritiva:
        Cálculo de estatísticas descritivas (média, desvio padrão, etc.) para variáveis numéricas.
        Verificação da distribuição dos valores de Year_Introduced.
        Criação de histogramas e gráficos de densidade para Speed_mph (velocidade).
        Análise da contagem de valores por tipo de montanha russa (Type_Main).

    Visualização de Dados:
        Gráfico de dispersão entre Speed_mph (velocidade) e Height_ft (altura).
        Gráfico de dispersão com cores diferentes para cada ano de introdução (Year_Introduced).
        Gráficos de pares (pairplot) para visualizar as relações entre diversas variáveis.
        Mapa de calor da correlação entre variáveis numéricas.
        Gráfico de barras horizontais para a velocidade média por localização.

## Interpretação dos Resultados

**A análise revela:**

    Distribuição: A maioria das montanhas russas foi introduzida nos últimos 30 anos.
    
    Velocidade: As velocidades variam bastante, com algumas montanhas russas ultrapassando 100 mph.
    
    Altura: A altura também tem uma ampla faixa de valores.
    
    Tipos: Existem diferentes tipos de montanhas russas (Steel, Wooden, etc.)
    
    Correlações: Algumas correlações fracas a moderadas são observadas entre as variáveis (por exemplo, entre Speed_mph e Height_ft).
    
    Localização: A velocidade média varia por localização, com alguns locais apresentando montanhas russas mais rápidas do que outros.

## Considerações Finais

Esta análise é apenas o primeiro passo para entender os dados das montanhas russas. As informações obtidas podem ser usadas para aprofundar a análise, respondendo a perguntas mais específicas, criando modelos preditivos, ou comparando diferentes tipos de montanhas russas.

**Lembre-se:** A EDA é um processo iterativo, e os resultados podem levar a novas perguntas e a um maior refinamento da análise.
