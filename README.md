#TIENDA ONLINE
Descripción:
Este código Python implementa una tienda online con las siguientes funcionalidades:
> Gestión de inventario:

Agregar productos con nombre, precio y cantidad.
Visualizar el inventario completo.
Buscar un producto por nombre y mostrar sus detalles.
Actualizar el stock de un producto.
Eliminar un producto del inventario.
Calcular el valor total del inventario.
Buscar productos por patrón regex.


>Ventas:

Permite a un cliente realizar una compra seleccionando productos del inventario.
Procesa el pago de la compra, calcula el cambio y muestra un mensaje de confirmación.


>Clientes:

Registrar un nuevo cliente con nombre y correo electrónico.
Visualizar la lista de clientes registrados.


>Historial de compras:

Registrar una compra para un cliente, actualiza las ventas totales y agrega la compra al historial de cliente.
Mostrar el historial de compras de un cliente.


>Ventas totales:

Calcular las ventas totales de la tienda.


Ejemplo de uso:
Mitienda = TiendaOnline()

# Agregar productos al inventario
tienda.agregar_producto("Camiseta", 20, 10)
tienda.agregar_producto("Zapatos", 50, 5)
tienda.agregar_producto("Taza", 10, 20)

# Visualizar el inventario
tienda.ver_inventario()

# Buscar un producto
tienda.buscar_producto("Camiseta")

# Realizar una compra
total_compra = tienda.realizar_compra()

# Procesar el pago
tienda.procesar_pago(total_compra)

# Registrar un nuevo cliente
tienda.agregar_clientes("Juan Pérez", "juan.perez@email.com")

# Registrar la compra
tienda.registrar_compra("Juan Pérez", carrito)

# Ver el historial de compras
tienda.ver_compras_cliente("Juan Pérez")

# Calcular ventas totales
tienda.calcular_ventas_totales()
