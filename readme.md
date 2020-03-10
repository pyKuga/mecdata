Como o Antony traçou, é necessário atigingirmos algumas metas, e até abro para complementação:
1. identificar os fatores q tornam uma região propensa a incendios
  temos estes campos:
  id - id único para cada registro
  estado - estado cujos dados foram extraídos
  estacao - indicador aleatório e único para cada região de aquisição dos dados
  data - data de observação dos dados
  precipitacao - dados de precipitação [mm]
  temp_max - dados de temperatura máxima observada no dia [°C]
  temp_min - dados de temperatura mínima observada no dia [°C]
  insolacao - período de tempo em que houve irradiação solar sobre superfície [horas]
  evaporacao_piche - medida de evaporação [mm]
  precipitacao - dados de precipitação [mm]
  temp_comp_med - temperatura compensada média [°C]
  umidade_rel_med - umidade relativa média [%]
  vel_vento_med - velocidade média do vento [m/s]
  altitude - altitude do local de medição [m]
  fires - variável booleana que indica se houve incêndio no dia ou não


2. trabalhar com os dados, pra deixar td ok
  temos que achar algum método de filtragem
3. usar algum algoritmo de machine learning pra conseguir identificar as regiões
