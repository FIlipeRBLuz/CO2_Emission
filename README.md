# CO2_Emission
Descrição: O conjunto de dados contém 9358 resultados médios de 5 sensores químicos de um dispositivo multisensor (PTXX.SX). O dispositivo estava localizado a nível da rua, dentro de uma cidade significativamente poluída. Os dados foram registrados de março de 2004 a fevereiro de 2005 (um ano). Valores ausentes são marcados com o valor -200. A medida de outros sensores também está disponível e algumas podem ser redundantes. A variável chave a ser analisada é PT08.S1 (CO), concentração de CO na atmosfera. Informação das colunas:  Date (DD/MM/YYYY) Time (HH.MM.SS) PT08.S1 (CO) – Variável de predição Non Metanic HydroCarbons Concentration (mg/m^3) 4 Benzene Concentration (mg/m^3) PT08.S2 (NMHC) N PT08.S3 (NOx) 8 NO2 Concentration (mg/m^3) PT08.S4 (NO2s) PT08.S5 (O3) Temperature (C) Relative Humidity (%) AH Absolute Humidity  Perguntas:  Escolha uma estratégia de tratamento de valores faltantes e outliers e justifique sua escolha. Para as quartas-feiras, quais os horários de pico na cidade (de maior concentração de CO) ? Quais as variáveis mais correlacionadas com a variável de predição? Crie um modelo de regressão de PT08.S1 a partir das demais variáveis. Avalie usando as métricas que julgar pertinente para o problema. Pergunta bônus: como as estações do ano interferem nas variáveis/predição e qual sua proposta de solução? Essas perguntas servem apenas para direcionar a análise. Sinta-se livre para surpreender.  Finalização do Desenvolvimento:  Ao finalizar, envie um email para o o recrutador responsável pelo seu processo seguindo o padrão de assunto: "Prova 1 - [Nome] - [Tecnologia]". Não esqueça de adicionar o usuário radix.recruit como reporter do seu repositório. Crie ou edite o README do seu repositório para realizar comentários e/observações, por exemplo, o que achou dos desafios ou maiores dificuldades encontradas.   Requirements:   Data:  qualidade_do_ar.csv    Program Language:  Python 3.7.6    Libraries:  matplotlib==3.1.3 numpy==1.18.1 scikit-learn==0.22.1 scipy==1.4.1 seaborn==0.10.0 statsmodels==0.11.0     Description - This notebook was developed aims to predict CO2 emission using regression technics based on other features. It was part of Radix challenging. - The challenge was cool to solve, creating the necessity of reading about the subject, trying to improve my knowledge about CO2 emission and also about new technics to solve the questions. - I tried to be innovative using new methods, enjoying the opportunity to learn more about regression models, hypothesis tests and plotting results.
