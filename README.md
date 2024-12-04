# Prueba-de-hipotesis-estadistica

__Contexto__

La optimización de los servicios de atención al cliente es fundamental para el éxito de cualquier empresa.Consciente de esta realidad, la operadora de servicios de atención al cliente ha desarrollado una nueva herramienta analítica destinada a identificar a los operadores que requieren mejorar su eficacia. Este análisis exploratorio se centra en la detección de operadores ineficaces, utilizando como indicadores clave el número de llamadas perdidas, los tiempos de espera y el volumen de llamadas salientes. Los resultados de este estudio permitirán a la empresa tomar decisiones informadas para mejorar la calidad del servicio y la satisfacción del cliente.

Se considera que un operador es ineficaz si tiene una gran cantidad de llamadas entrantes perdidas (internas y externas) y un tiempo de espera prolongado para las llamadas entrantes. Además, si se supone que un operador debe realizar llamadas salientes, un número reducido de ellas también será un signo de ineficacia.

El análisis se realiza bajo la siguiente estructura:

•	Lleva a cabo el análisis exploratorio de datos.

•	Identificar operadores ineficaces.

•	Prueba las hipótesis estadísticas.

__Descripción de los datos__

Los datasets contienen información sobre el uso del servicio de telefonía virtual. Sus clientes son organizaciones que necesitan distribuir gran cantidad de llamadas entrantes entre varios operadores, o realizar llamadas salientes a través de sus operadores. Los operadores también pueden realizar llamadas internas para comunicarse entre ellos. 

- __telecom_dataset_us.csv:__

•	_user_id:_ ID de la cuenta de cliente.

•	_date:_ fecha en la que se recuperaron las estadísticas.

•	_direction:_ "dirección" de llamada (out para saliente, in para entrante).

•	_internal:_ si la llamada fue interna (entre los operadores de un cliente o clienta).

•	_operator_id:_ identificador del operador.

•	_is_missed_call:_ si fue una llamada perdida.

•	_calls_count:_ número de llamadas.

•	_call_duration:_ duración de la llamada (sin incluir el tiempo de espera).

•	_total_call_duration:_ duración de la llamada (incluido el tiempo de espera).

- __telecom_clients_us.csv:__

•	_user_id:_ ID de usuario/a.

•	_tariff_plan:_ tarifa actual de la clientela.

•	_date_start:_ fecha de registro de la clientela.

__Tabla de Contenido__

En el archivo 'hipotesis_estadistica.ipynb' se encuentra el siguiente desarrollo:

- Carga de librerías y archivos.
- Cambio de tipo de datos.
- Exploración visual de los datos.
- Cálculo y distribución de métricas de ineficiencia.
- Prueba de hipótesis estadística.

__Conclusiones__

__Enlace al Dashboard__

https://public.tableau.com/views/Proy_final_17331582911660/Dashboard1?:language=es-ES&publish=yes&:sid=&:redirect=auth&:display_count=n&:origin=viz_share_link





