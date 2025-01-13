# Bootcamp-Project-Zuber-Company
Project Overview
This project analyzed ride-sharing data for Zuber in Chicago, focusing on patterns of rides and the impact of external factors such as weather on trips. Data cleaning, exploratory data analysis, and hypothesis testing were performed using SQL and Python.

Key Insights
Popular Neighborhoods:
The Loop and River North have the highest number of trips among all neighborhoods. The difference in trip counts between the top two neighborhoods is approximately 1,200. However, the third place lags behind by almost 3,000 trips.

Top Taxi Companies:
Flash Cab is the most active taxi company, with the highest number of trips. Among the top 25 companies, 24 have more than 1,000 trips, and the 25th is close to this threshold with 978 trips. Companies outside this top 25 experience a significant drop in trip counts, with the highest having only 428 trips.

Hypothesis Testing
Hypothesis:
"The average duration of trips from the Loop to O'Hare International Airport changes on rainy Saturdays."

Steps Taken:
Grouped Saturdays into two categories based on weather conditions:
Bad weather: Includes "rain" or "storm" in the weather description.
Good weather: All other conditions.
Retrieved trips starting in the Loop and ending at O'Hare, and joined them with weather data to assess the relationship between trip duration and weather conditions.

Findings:
The number of trips is higher on good-weather Saturdays than on rainy ones.
However, the average trip duration is significantly longer on rainy Saturdays, likely due to increased traffic during rainy conditions.
Further analysis with additional data would be needed to confirm this assumption.

Conclusion:
Based on the data and the hypothesis test, the null hypothesis was rejected. There is a significant difference in the average duration of trips from the Loop to O'Hare International Airport on rainy Saturdays compared to non-rainy ones.

================================================================================================================

Visão Geral do Projeto
Este projeto analisou dados de compartilhamento de caronas da Zuber em Chicago, com foco nos padrões de viagens e no impacto de fatores externos, como o clima, nas corridas. Foram realizadas limpeza de dados, análise exploratória e teste de hipóteses utilizando SQL e Python.

Principais Conclusões
Bairros Populares:
O Loop e River North têm o maior número de corridas entre todos os bairros. A diferença no número de corridas entre os dois bairros mais populares é de aproximadamente 1.200. Contudo, o terceiro lugar fica atrás por quase 3.000 corridas.

Principais Empresas de Táxi:
A Flash Cab é a empresa de táxi mais ativa, com o maior número de corridas. Entre as 25 principais empresas, 24 têm mais de 1.000 corridas, e a 25ª está próxima desse número, com 978 corridas. Empresas fora desse top 25 apresentam uma queda significativa no número de corridas, com a maior delas tendo apenas 428.

Teste de Hipótese
Hipótese:
"A duração média das viagens do Loop para o Aeroporto Internacional O'Hare muda em sábados chuvosos."

Passos Realizados:
Agrupou os sábados em duas categorias com base nas condições climáticas:
Clima ruim: Inclui "chuva" ou "tempestade" na descrição do clima.
Clima bom: Todas as outras condições.
Recuperou corridas iniciadas no Loop e terminadas em O'Hare, juntando os dados com informações meteorológicas para avaliar a relação entre duração das corridas e condições climáticas.

Resultados:
O número de corridas é maior nos sábados de clima bom do que nos chuvosos.
Contudo, a duração média das corridas é significativamente maior nos sábados chuvosos, possivelmente devido ao aumento do trânsito em condições de chuva.
Análises adicionais com mais dados seriam necessárias para confirmar essa suposição.

Conclusão:
Com base nos dados e no teste de hipótese, a hipótese nula foi rejeitada. Existe uma diferença significativa na duração média das corridas do Loop para o Aeroporto Internacional O'Hare em sábados chuvosos em comparação com os sábados de clima bom.