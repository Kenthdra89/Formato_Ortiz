Función: ObtenerTotalPedidosCliente
Contar el total de pedidos realizados por un cliente específico. Se utiliza el ID del cliente como parámetro de entrada para identificar los pedidos asociados.

Datos/Tablas Manipulados:

Parámetros de Entrada:
cliente_id (INT): Identificador del cliente.
Consulta SQL:
Tabla utilizada: PEDIDOS
Operación: Contar el número total de pedidos para un cliente específico.


Función: ObtenerPrecioTotalPedido
 Calcular el precio total de un pedido específico, teniendo en cuenta la cantidad y el precio de cada producto en el pedido. Se utiliza el ID del pedido como parámetro de entrada.

Datos/Tablas Manipulados:

Parámetros de Entrada:
pedido_id (INT): Identificador del pedido.
Consulta SQL:
Tablas utilizadas: DETALLES_DE_PEDIDO, PRODUCTOS
Operación: Calcular el precio total sumando el precio de cada producto multiplicado por su cantidad en el pedido.
