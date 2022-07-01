# Proyecto_DW_DEVF

#### Link a Tablero con los datos <br>
https://public.tableau.com/app/profile/emmanuel8661/viz/financial_indicators/Hoja1?publish=yes.
<br>

El archivo ETL se ejecuta diario a las 6:30 en servidor de integracion y llena los datos en una db sql server. <br>
<br>
###El DW contiene las tablas <br>

#### Dimensiones: <br>
dimIndicator : Tabla de dimensiones que contiene los indicadores financieros a traer información. Si se desea agregar un indicador mas solo se coloca la información en esta tabla. 
<br>

#### Echos
FacIndicators : Contiene los valores de los indicadores financieros y la relación a las dimensiones


