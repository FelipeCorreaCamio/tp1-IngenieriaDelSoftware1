Integrantes: Badaracco, Valentino; Correa, Felipe; Gross, Dylan; Hertler, Kevin; Waigel, Agustina; Zuleiman, Agustin.
==================================================================================================================================================
Validación de los atributos
---------------------------
Código: 
Tipo de dato: VARCHAR
Validación: El código ingresado debe estar registrado en el sistema. Si no está registrado, se considera inválido.
Para validarlo se prueba con códigos que si esten registrados, y códigos que no existan, para ver como reacciona el sistema ante el error.
--------------------------------------------------------------------------------------------------------------------------------------------------
Nombre del producto:
Tipo de dato: VARCHAR
Límites: mínimo 3 caracteres, máximo 100 caracteres
Validación: El nombre debe tener al menos 3 caracteres y como máximo 100 caracteres para ser válido
Para validarlo se prueba con nombres que cumplan con los límites, y con nombres que no cumplan con los límites, para ver como reacciona el sistema ante el error.
--------------------------------------------------------------------------------------------------------------------------------------------------
Tipo de producto:
Tipo de dato: VARCHAR
Validación: Verificar si el tipo de producto seleccionado se encuentra entre los tipos permitidos en una lista predefinida. Si no está en la lista, se considera invalido.
Para validarlo se prueba con tipos de productos que esten en la lista predefinida, y con tipos de productos que no esten en la lista, para ver la reaccion del sistema ante el error.
--------------------------------------------------------------------------------------------------------------------------------------------------
Descripción:
Tipo de dato: TEXT
Límites: mínimo 0 caracteres, máximo 300 caracteres.
Validación: La descripción puede ser opcional, pero en el caso de que haya debe tener como máximo 300 caracteres.
Para validarlo se prueba con descripciones que cumplan con los límites, y con descripciones que no cumplan con los límites, para ver como reacciona el sistema ante el error.
--------------------------------------------------------------------------------------------------------------------------------------------------
Stock inicial:
Tipo de dato: INT
Límites: mínimo 10 productos, máximo 200 productos.
Validación: Debe ser un número entre 10 y 200 para que sea válido.
Para validarlo se prueba con números que cumplan con los límites, y con números por fuera de los límites, para ver como reacciona el sistema ante el error.
--------------------------------------------------------------------------------------------------------------------------------------------------
Punto de pedido: 
Tipo de dato: INT
Límites: minimo 0, máximo 20.
Validación: Se determina cuándo se debe realizar un pedido nuevo. Se gestiona internamente por el sistema.
Para validarlo se prueba con números que cumplan con los límites, y con números por fuera de los límites, para ver como reacciona el sistema ante el error.
--------------------------------------------------------------------------------------------------------------------------------------------------
Fecha de compra:
Tipo de dato: DATE
Límites: Debe estar entre 1 semana antes y hasta 1 semana después de la fecha actual.
Validación: Se debe validar que la fecha de compra esté dentro de un rango permitido. Esto puede verificarse comparando con la fecha actual.
Para validarlo se deben probar con fechas que esten dentro de los límites, y fechas por fuera de los límites.
--------------------------------------------------------------------------------------------------------------------------------------------------
Código del proveedor:
Tipo de dato: VARCHAR
Validación: Debe existir en la base de datos proveedores.
Para validarlo se prueba con códigos de proveedor que si esten registrados, y códigos de proveedor que no existan, para ver como reacciona el sistema ante el error.
--------------------------------------------------------------------------------------------------------------------------------------------------
Precio:
Tipo de dato: FLOAT
Límites: mínimo 1000 ($), máximo 100000 ($)
Validación: Verificar que el precio está dentro del rango permitido para evitar valores extremos o mínimos.
Para validarlo se prueba con números que cumplan con los límites, y con números por fuera de los límites, para ver como reacciona el sistema ante el error.
==================================================================================================================================================
Codificacion:

Para la codificación elegiríamos la codificación alfanumérica. 
Con 3 letras y 3 números (ABC123)
En las 3 primeras letras pondríamos una breve descripción del nombre del tipo de prenda, ejemplo: CAM(camisa) - PAN(pantalón) - REM(remera) - POL(pollera).
Y los 3 números siguientes serian secuenciales para cada variedad de prendas que hay dentro de cada tipo
Ejemplos: 
CAM001 para una camisa manga larga de "x" modelo
PAN005 para un pantalón largo para "x" modelo 
