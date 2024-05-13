Integrantes: Badaracco, Valentino; Correa, Felipe; Gross, Dylan; Hertler, Kevin; Waigel, Agustina; Zuleiman, Agustin.

Validación de los atributos
---------------------------
Código: 
Validación: El código ingresado debe estar registrado en el sistema. Si no está registrado, se considera invalido.
--------------------------------------------------------------------------------------------------------------------------------------------------
Nombre del producto:
Límites: mínimo 3 caracteres, máximo 100 caracteres
Validación: El nombre debe tener al menos 3 caracteres para ser válido
--------------------------------------------------------------------------------------------------------------------------------------------------
Tipo de producto:
Validación: Verificar si el tipo de producto seleccionado se encuentra entre los tipos permitidos en una lista predefinida. Si no está en la lista, se considera invalido.
--------------------------------------------------------------------------------------------------------------------------------------------------
Descripción:
Límites: mínimo 0 caracteres, máximo 300 caracteres.
Validación: La descripción puede ser opcional.
--------------------------------------------------------------------------------------------------------------------------------------------------
Stock inicial:
Límites: mínimo 0 productos, máximo 200 productos.
Validación: Debe ser un número válido que indique la cantidad de productos en existencia inicialmente.
--------------------------------------------------------------------------------------------------------------------------------------------------
Punto de pedido: 
Límite:
Validación: Se determina cuándo se debe realizar un pedido nuevo. Se gestiona internamente por el sistema.
--------------------------------------------------------------------------------------------------------------------------------------------------
Fecha de compra:
Límites: Debe estar entre 1 semana antes y hasta 1 semana después de la fecha actual.
--------------------------------------------------------------------------------------------------------------------------------------------------
Validación: Se debe validar que la fecha de compra esté dentro de un rango permitido. Esto puede verificarse comparando con la fecha actual.
--------------------------------------------------------------------------------------------------------------------------------------------------
Código del proveedor:
Validación: Debe existir en la base de datos proveedores.
--------------------------------------------------------------------------------------------------------------------------------------------------
Precio:
Límites: mínimo 1000 ($), máximo 100000 ($)
Validación: Verificar que el precio está dentro del rango permitido para evitar valores extremos o mínimos.
