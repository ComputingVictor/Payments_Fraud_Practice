<h1>Data Dictionary</h1>

<p>Payments Fraud Practice<br />
<strong>Aprendizaje Autom&aacute;tico</strong><br />
<strong>Master Universitario en Ciencia de Datos</strong></p>

<p>&nbsp;</p>

<p style="text-align:right">V&iacute;ctor Viloria V&aacute;zquez (<em>victor.viloria@cunef.edu</em>)</p>

<hr style="border:1px solid gray">

Este documento pretende aportar información descriptiva del contenido y forma del dataset utilizado en la segunda práctica de la asignatura de Machine Learning, la cual consiste en la de un modelo predictor del  dataset **Payments Fraud Practice**.

Este dataset incorpora informacion relativa a diferentes clientes de una empresa financiera, exactamente un número de **19 variables**.

**Nos disponemos a describir cada una de las variables que posee el dataset, su
significado, posibles valores que puede tomar y otros aspectos técnicos relevantes para el
manejo y que permitan la elaboración de modelos.**.

## Diccionario de datos

| **Field Name** 	| **Description** 	| **Variable Type** 	| **Data Type** 	| **Value** 	|
|:---:|:---	|---	|---	|:---	|
| step 	| Unity of time (hours) 	| Numerical 	| _int64_ 	| Values between [1 – 95] 	|
| type 	| Typer of transfer 	| Categorical 	| _object_ 	| - PAYMENT<br>- TRANSFER<br>- CASH_OUT<br>- DEBIT<br>- CASH_IN 	|
| amount 	| Quantity of amount tranferred 	| Numerical 	| _float64_ 	| Values between [0.1 -10000000] 	|
| gender 	| Gender of the client (Informed by himself) 	| Categorical 	| _object_ 	| - man<br>- woman<br>- unknow 	|
| device 	| Type of device where the client did the transaction 	| Categorical 	| _object_ 	| - mac<br>- pc<br>- iphone 	|
| connection 	| Time that the data takes to arrive from de entry connection 	| Numerical 	| _object_ 	| Values between [0 – 1] 	|
| nameOrig 	| Identifier of the client which did the transaction 	| Categorical 	| _object_ 	| - Cxxxxxxxxx 	|
| race 	| Client's race 	| Categorical 	| _object_ 	| - black<br>- asian<br>- latin 	|
| oldbalanceOrg 	| Balance before the transaction 	| Numerical 	| _float64_ 	| Values between [0 – 38939424.03] 	|
| age 	| Estimated Age 	| Numerical 	| _int64_ 	| Values between [5 – 100] 	|
| newbalanceOrig 	| Balance after the transaction 	| Numerical 	| _float64_ 	| Values between [0 –38946233.02] 	|
| nameDest 	| Receptor's name of the transaction (anonymized) 	| Categorical 	| _object_ 	| - Cxxxxxxxxx<br>- Mxxxxxxxxx 	|
| user_connections 	| Connections of the same user during the day 	| Numerical 	| _int64_ 	| Values between [1 – 10] 	|
| security_alert 	| Label that shows if an alert pop up when transaction was done 	| Categorical 	| _int64_ 	| 0: Alert wasn't executed<br> 1: Alert was executed	|
| oldbalanceDest 	| Balance of the receiver before the transaction 	| Numerical 	| _float64_ 	| Values between [0 – 42054659.73] 	|
| newbalanceDest 	| Balance of the receiver after the transaction 	| Numerical 	| _float64_ 	| Values between [0 –42169156.09] 	|
| zone 	| Origin place where the transaction was launched 	| Categorical 	| _object_ 	| - capital<br>- country<br>- africa 	|
| user_number 	| Number of recurrent users at the moment the transaction was done 	| Numerical 	| _int64_ 	| Values between [59 – 5000] 	|
| **isFraud** 	| **TARGET: Label that detects if a fraud was done or not** 	| Categorical 	| _int64_ 	| 0: Not a Fraudulent transaction<br>1: Fraudulent transacion 	|
