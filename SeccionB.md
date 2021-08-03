### Propuesta de Solución para la Michoacana

De acuerdo a la motivación que se hizo llegar se pueden identificar las siguientes necesidades:

- Pronostico de demanda de producto
- Calculo optimo de inventario :
  - Basado en distribución actual
  - Basado en deep learning   
- Perfilamiento de zonas
- Elasticidades y rotación de productos

Como una solución incluye una implementación de una herramienta Web, la cual muestre:

#### Vista de Estadisticas generales
  - Ventas
  - Productos
  - Metas

#### Herramientas de pronostico:
Mediante los dos puntos de vista mencionados:
  
  - En el punto de vista probabilistico, será determinar el mejor estimador insesgado de la distribución correspondiente.
  
  - En el punto de vista de deep learning se propone una estructura de DNN

#### Medidores de Mercado

La funcionalidad de esto serivrá como una fotografía del comportamiento de la población donde se distribuye el producto mediante KNN, 
así como la apreciación general del mercado ya sea de los productos de la Michoacana, los competidores y posibles casos de canibalización usando
un hibrido de la teoría económica de la demanda y modelos de regresión

#### Calidad y proceso

Se desarrollarán procesos de ETL para hacer un check adicional sobre la consistencia de la información, 
así como las pruebas pertinentes para saber si hay diferencias significativas.

El EDA permitirá dar la(s) tablas necesarias o en su defecto los queries para poder gestionar la primer sección de la información,
para asi obtener la TAD correspondiente que sirva de ingesta para las herramientas de pronóstico, así como los analisis de mercado propuestos.

Las herramientas de pronóstico se medirán en el caso de DL: 
  - MSE

En cuanto a las medidas de Mercado: 

  - Perfilamiento se mediría mediante
    -  Accuracy
    -  Precision
    
  -  Modelos de regresión
    - Medidas de bondad y ajuste

Se tiene la meta que al estar en producción despues de la fase de pruebas correspondientes y las optimizaciones tomando los comentarios del usuario final,
se mediante una herramienta web donde pueda consultar tanto los visualizadores así como las herramientas de pronostico.

Esperando así que el éxito de esta solución se refleje mediante la recurrencia de uso logrando no solo reducir el tiempo invertido en la toma de decisiones 
sino notar un cumplimiento de la mayoría de las metas fijadas por el usuario.

  
  
