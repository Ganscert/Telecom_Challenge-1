#### Diccionario de datos

- `1 customerID`: número de identificación único de cada cliente
- `2 Churn`: si el cliente dejó o no la empresa
- `3 gender`: género (masculino y femenino)
- `4 SeniorCitizen`: información sobre si un cliente tiene o no una edad igual o mayor a 65 años
- `5 Partner`: si el cliente tiene o no una pareja
- `6 Dependents`: si el cliente tiene o no dependientes
- `7 tenure`: meses de contrato del cliente
- `8 PhoneService`: suscripción al servicio telefónico
- `9 MultipleLines`: suscripción a más de una línea telefónica
- `10 InternetService`: suscripción a un proveedor de internet
- `11 OnlineSecurity`: suscripción adicional de seguridad en línea
- `12 OnlineBackup`: suscripción adicional de respaldo en línea
- `13 DeviceProtection`: suscripción adicional de protección del dispositivo
- `14 TechSupport`: suscripción adicional de soporte técnico, menor tiempo de espera
- `15 StreamingTV`: suscripción de televisión por cable
- `16 StreamingMovies`: suscripción de streaming de películas
- `17 Contract`: tipo de contrato
- `18 PaperlessBilling`: si el cliente prefiere recibir la factura en línea
- `19 PaymentMethod`: forma de pago
- `20 Charges.Monthly`: total de todos los servicios del cliente por mes
- `21 Charges.Total`: total gastado por el cliente


	-	`count`: número de valores no nulos en esa columna. Aquí todas tienen 7 267 registros válidos.
	-	`mean`: la media aritmética (promedio) de los valores. Por ejemplo, la media de tenure (meses de antigüedad) es ≈ 32,3 meses.
	-	`std`: desviación estándar, que mide la dispersión de los valores alrededor de la media. Un std alto indica que los datos están más dispersos.
	-	`min`: el valor mínimo observado. En tu caso, Churn llegó a –1 (probablemente por algún mapeo especial), tenure a 0 meses, y las demás binarias a 0.
	-	`25%` (primer cuartil): valor por debajo del cual se encuentra el 25 % de los datos. Por ejemplo, el 25 % de tus clientes tienen como máximo 9 meses de antigüedad.
	-	`50%` (mediana o segundo cuartil): el valor central que deja a la mitad de los datos por debajo y la otra mitad por encima. Aquí la mediana de tenure es 29 meses.
	-	`75%` (tercer cuartil): valor por debajo del cual se encuentra el 75 % de los datos. El 75 % de tus clientes tienen hasta 55 meses de antigüedad.
	-	`max`: valor máximo observado. Por ejemplo, el cliente más “antiguo” lleva 72 meses (“6 años”) y los indicadores binarios llegaron a 1 (sí).
