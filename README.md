# Projeto de Previsão de Geração de Energia Solar

1. Introdução e Problema
A energia solar é uma das fontes de energia renovável mais promissoras e de crescimento mais rápido no mundo. No entanto, uma de suas principais desvantagens é a sua natureza intermitente e variável, uma vez que a geração de energia fotovoltaica (FV) depende diretamente de condições meteorológicas como irradiação solar e temperatura.

Essa variabilidade representa um desafio significativo para a estabilidade da rede elétrica e o gerenciamento de energia. Previsões imprecisas podem levar a um desequilíbrio entre oferta e demanda, resultando em custos operacionais mais altos e potencial instabilidade na rede.

Objetivo Principal: O objetivo deste projeto é desenvolver um modelo de machine learning capaz de prever com precisão a geração de energia de uma usina solar com base em dados meteorológicos e históricos. A aplicação de técnicas de regressão e séries temporais permitirá criar uma ferramenta para otimizar o gerenciamento da produção de energia.

2. Sobre o Dataset
Para este projeto, utilizaremos o dataset "Solar Power Generation Data", disponível publicamente no Kaggle.

Este conjunto de dados foi coletado em duas usinas de energia solar na Índia durante um período de 34 dias e é ideal para esta análise por conter informações tanto de geração de energia quanto de sensores meteorológicos.

O dataset é composto por quatro arquivos principais:

Plant_1_Generation_Data.csv: Dados de geração de energia da Usina 1.

Plant_1_Weather_Sensor_Data.csv: Dados dos sensores meteorológicos da Usina 1.

Plant_2_Generation_Data.csv: Dados de geração de energia da Usina 2.

Plant_2_Weather_Sensor_Data.csv: Dados dos sensores meteorológicos da Usina 2.

Principais Variáveis:
Dados de Geração:

DATE_TIME: Data e hora da observação (intervalos de 15 minutos).

AC_POWER: Potência de saída em corrente alternada (kW) - Nossa variável alvo.

DC_POWER: Potência de entrada em corrente contínua (kW).

DAILY_YIELD: Energia acumulada gerada no dia (kWh).

SOURCE_KEY: ID do inversor que gerou os dados.

Dados Meteorológicos:

DATE_TIME: Data e hora da observação.

AMBIENT_TEMPERATURE: Temperatura ambiente (°C).

MODULE_TEMPERATURE: Temperatura do módulo solar (°C).

IRRADIATION: Intensidade da irradiação solar (W/m²).# Projeto de Previsão de Geração de Energia Solar

1. Introdução e Problema
A energia solar é uma das fontes de energia renovável mais promissoras e de crescimento mais rápido no mundo. No entanto, uma de suas principais desvantagens é a sua natureza intermitente e variável, uma vez que a geração de energia fotovoltaica (FV) depende diretamente de condições meteorológicas como irradiação solar e temperatura.

Essa variabilidade representa um desafio significativo para a estabilidade da rede elétrica e o gerenciamento de energia. Previsões imprecisas podem levar a um desequilíbrio entre oferta e demanda, resultando em custos operacionais mais altos e potencial instabilidade na rede.

Objetivo Principal: O objetivo deste projeto é desenvolver um modelo de machine learning capaz de prever com precisão a geração de energia de uma usina solar com base em dados meteorológicos e históricos. A aplicação de técnicas de regressão e séries temporais permitirá criar uma ferramenta para otimizar o gerenciamento da produção de energia.

2. Sobre o Dataset
Para este projeto, utilizaremos o dataset "Solar Power Generation Data", disponível publicamente no Kaggle.

Este conjunto de dados foi coletado em duas usinas de energia solar na Índia durante um período de 34 dias e é ideal para esta análise por conter informações tanto de geração de energia quanto de sensores meteorológicos.

O dataset é composto por quatro arquivos principais:

Plant_1_Generation_Data.csv: Dados de geração de energia da Usina 1.

Plant_1_Weather_Sensor_Data.csv: Dados dos sensores meteorológicos da Usina 1.

Plant_2_Generation_Data.csv: Dados de geração de energia da Usina 2.

Plant_2_Weather_Sensor_Data.csv: Dados dos sensores meteorológicos da Usina 2.

Principais Variáveis:
Dados de Geração:

DATE_TIME: Data e hora da observação (intervalos de 15 minutos).

AC_POWER: Potência de saída em corrente alternada (kW) - Nossa variável alvo.

DC_POWER: Potência de entrada em corrente contínua (kW).

DAILY_YIELD: Energia acumulada gerada no dia (kWh).

SOURCE_KEY: ID do inversor que gerou os dados.

Dados Meteorológicos:

DATE_TIME: Data e hora da observação.

AMBIENT_TEMPERATURE: Temperatura ambiente (°C).

MODULE_TEMPERATURE: Temperatura do módulo solar (°C).

IRRADIATION: Intensidade da irradiação solar (W/m²).