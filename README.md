# Meteograma_GFS_GRIB2

Script para plotar um meteograma das variavéis do modelo utilizando dados de 3 dias de previsão do modelo GFS. O teste foi realizado para a cidade de Pelotas-RS mas pode ser aplicado em qualquer outra cidadade através da função np.where.

Requerimentos: import pygrib
from mpl_toolkits.basemap import Basemap
from mpl_toolkits.basemap import shiftgrid
import matplotlib.pyplot as plt
import numpy as np
import pandas as pd
from datetime import datetime
Observação: O código foi elaborado na plataforma Google Colab.

Ponto de grade escolhido; 

![image](https://github.com/vlsantos-bit/Meteograma_GFS_GRIB2/blob/main/grad_escolhida.png)

Resultado do meteograma para umidade
![image](https://github.com/vlsantos-bit/Meteograma_GFS_GRIB2/blob/main/meteo_umid1.png) 
![image](https://github.com/vlsantos-bit/Meteograma_GFS_GRIB2/blob/main/umid_meteograma2.png)
