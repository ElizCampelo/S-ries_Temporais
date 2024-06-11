# [Series Temporais]

## Visão Geral
Este repositório contém informações e recursos para [análise detalhada da série temporal]. É um projeto desenvolvido para o Visual Studio Code.
O estudo tem os seguintes passos:
Importação e visualização dos dados.
Estatística descritiva.
Visualização da série temporal.
Análise de autocorrelação (ACF) e autocorrelação parcial (PACF).
Teste de estacionariedade usando o teste de Dickey-Fuller Aumentado (ADF).
Diferenciação da série, se necessário.
Resumo da análise. 

## Conteúdo
- **[Arquivo 1]**: Notebook da analise Bearq.
- **[Arquivo 2]**: Base dos dados Bearq
- **[Arquivo 3]**: Base dos dados Colorado River.
- **[Arquivo 4]**: Notebook Colorado River.
- **[Arquivo 5]**: Base dos dados sem nome.
- **[Arquivo 6]**: Notebook sem nome.
- **[Arquivo 6]**: Notebook Temperature.
- **[Arquivo 6]**: Base dos dados Temperature.

## Configuração do Ambiente
1. Certifique-se de ter o Visual Studio Code instalado. Você pode baixá-lo em [visualstudio.com](https://code.visualstudio.com/).
2. 

## Resumo


**Resumo da Análise da Série Temporal: Annual River Flows**

- **Período:** A série cobre o período de 1878 em diante.
- **Frequência:** Anual.
- **Tendência:** A análise visual do gráfico da série temporal mostra possíveis tendências ao longo do tempo.
- **Variações Sazonais:** A análise de ACF e PACF pode mostrar padrões sazonais anuais.
- **Eventos Extremos:** Há alguns pontos nos dados que podem ser considerados eventos extremos, mas eles não são frequentes.
- **Autocorrelação:** A ACF mostra uma autocorrelação significativa para vários lags, sugerindo que a série tem memória e é autocorrelacionada.
- **Teste de Estacionariedade:** O teste de Dickey-Fuller Aumentado (ADF) indica que a série pode não ser estacionária, pois o valor p é maior que 0.05.
- **Importância dos Lags:** Os gráficos de ACF e PACF mostram que vários lags têm correlações significativas, indicando a importância de incluir esses lags em modelos ARIMA ou SARIMA.

**Conclusão:** A série temporal apresenta possíveis tendências. A análise de ADF sugere que a série pode não ser estacionária, indicando a necessidade de diferenciação para modelagem. Os gráficos de ACF e PACF serão úteis para determinar a ordem dos modelos de séries temporais apropriados.


**Resumo da Análise da Série Temporal: Bearq**
Estatísticas Descritivas
Contagem: 154 observações
Média: 408.27
Desvio Padrão: 97.60
Valor Mínimo: 212.80
Primeiro Quartil (25%): 325.43
Mediana (50%): 427.45
Terceiro Quartil (75%): 466.95
Valor Máximo: 600.00
Visualização da Série Temporal
O gráfico da série temporal mostra uma tendência ascendente geral ao longo do tempo, com flutuações significativas.

Análise de Autocorrelação (ACF) e Autocorrelação Parcial (PACF)
ACF: O gráfico da ACF indica que há autocorrelações significativas em vários lags, o que sugere que os valores da série estão correlacionados com seus valores passados. Isto é indicativo de uma tendência ou uma componente de longo prazo na série.
PACF: O gráfico da PACF mostra algumas correlações significativas nos primeiros lags, sugerindo que os primeiros lags têm um impacto significativo na série.
Teste de Dickey-Fuller Aumentado (ADF)
Estatística ADF: -2.0233
Valor-p: 0.2764
Número de Lags Usados: 11
Número de Observações: 142
Valores Críticos:
1%: -3.4773
5%: -2.8821
10%: -2.5777
Estatística AIC: 1193.832
O valor-p do teste ADF é maior que 0.05, o que significa que não podemos rejeitar a hipótese nula de que a série possui uma raiz unitária. Portanto, a série não é estacionária.


**Resumo da Análise da Série Temporal: Monthly Air Temperature (Nottingham, 1920–1939)**

- **Período:** A série cobre o período de janeiro de 1920 a dezembro de 1939.
- **Frequência:** Mensal.
- **Tendência:** A análise visual do gráfico da série temporal mostra possíveis tendências ao longo do tempo, embora não seja muito pronunciada.
- **Variações Sazonais:** A ACF e a PACF mostram padrões de sazonalidade, indicando que a temperatura pode ter componentes sazonais anuais.
- **Eventos Extremos:** Há alguns pontos nos dados que podem ser considerados eventos extremos, mas eles não são frequentes.
- **Autocorrelação:** A ACF mostra uma autocorrelação significativa para vários lags, sugerindo que a série tem memória e é autocorrelacionada.
- **Teste de Estacionariedade:** O teste de Dickey-Fuller Aumentado (ADF) indica que a série pode não ser estacionária, pois o valor p é maior que 0.05.
- **Importância dos Lags:** Os gráficos de ACF e PACF mostram que vários lags têm correlações significativas, indicando a importância de incluir esses lags em modelos ARIMA ou SARIMA.

**Conclusão:** A série temporal apresenta sazonalidade e possíveis tendências. A análise de ADF sugere que a série pode não ser estacionária, indicando a necessidade de diferenciação para modelagem. Os gráficos de ACF e PACF serão úteis para determinar a ordem dos modelos de séries temporais apropriados.                                                                               
# Análise de Séries Temporais de Produção de Leite

## Introdução
Este repositório contém uma análise detalhada da previsão de produção de leite utilizando três diferentes modelos: ARIMA,

