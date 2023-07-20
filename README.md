# Series Temporais

## Dataset
 - Os dados utilizaram foram removidos da plataforma Kaggle e podem ser obtidos no seguinte [link](https://www.kaggle.com/datasets/arashnic/learn-time-series-forecasting-from-gold-price);
 - Abaixo pode-se observar a vizualização da série temporal, que vai de 1970 até 2020, demonstrando a variação do preço do ouro em $.

![Alt text](./img/gold_price_time_series.png)

## Decomposição da série
    - Toda série temporal tem em sua composição 3 elementos
        => Tendência
        => Sazionalidade
        => Resíduo
    - Também existem os chamados 'ciclos', mas isso é identificado a partir da análise do comportamento da série temporal
    - Abaixo um gráfico demonstrando essa decomposição:
![!\[Alt text\](./img/gold_price) ](img/gold_price_time_series_decomposition.png)