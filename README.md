# Análise de dados - Turbina Eólica
## Inspeção de possíveis problemas em turbina eólica. 

#### Em Turbinas Eólicas, os Sistemas Scada medem e salvam dados como velocidade do vento, direção do vento, energia gerada etc. por intervalos de 10 minutos. Este arquivo foi retirado do sistema Scada de uma turbina eólica que está funcionando e gerando energia na Turquia.

###### Arquivo: https://www.kaggle.com/datasets/berkerisen/wind-turbine-scada-dataset
###### Os dados do arquivo são:
###### - Data/Hora (para intervalos de 10 minutos).
###### - LV ActivePower (kW): A potência gerada pela turbina naquele momento.
###### - Velocidade do vento (m/s): A velocidade do vento na altura do cubo da turbina (a velocidade do vento que a turbina usa para geração de eletricidade).
###### - TheoreticalPowerCurve (KWh): Os valores teóricos de potência que a turbina gera com aquela velocidade do vento que é dada pelo fabricante da turbina.
###### - Direção do Vento (°): A direção do vento na altura do cubo da turbina (as turbinas eólicas giram para esta direção automaticamente).

###### O objetivo final foi identificar as potências que estejam apresentando 5% de erro.
