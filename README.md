# SIFI
Universidad Libre | Trabajo de POO: **SISTEMA DE FACTURACION E INVENTARIO**
- Nuestros apuntes en [Medium](https://www.google.com)


# Problema
El sistema debe permitir facturar y llevar el control de inventario teniendo en cuenta los siguientes requerimientos funcionales:
1.un cliente puede realizar compras(CREDITO/CONTADO/CREDITO-CONTADO) de varios productos
2.en una factura se pueden registrar todos los productos que se requieran
3.Un vendedor puede atender a varios clientes
4.Se debe manejar los productos por categorias y precios
5.existe un inventario de productos
6.existen proveedores de los diferentes productos.

la aplicacion orientada a objetos debe permitir lo siguiente REPORTES:
1. poder consultar las facturas de los clientes
2. poder consultar que vendedores vendieron "X" factura a "X" cliente
3. poder consultar las facturas en un rango de fecha
4. poder consultar el stock del inventario
5. poder consultar los proveedores que surten "X" producto
6. las facturas devueltas o canceladas
7. saldos pendientes de los clientes por pagar

Si hay dudas de los requerimientos funcionales con gusto se los podre despejar. 
Este proyecto se va a entregar por fases(Parciales)

Para este primer corte(parcial 1) que se debe entregar:
1. diagama de clases con sus atributos y metodos
2. relaciones entre las clases
3. sustentacion


# Maqueta
Diagrama de clases y atributos.

| Cliente |                           
| ------------- |                      
| `Cedula` |                          
| `NombreCompleto` |                 
| `Monto` |                            
| `MetodoPago` |                                                        
| - RegistrarCliente |                
| - MostrarDatosPedidoCliente |       
| - RealizarCompra | 
| - SaldosPendientes |  

| Factura |
| ------------- |
| `IDFactura` | 
| `CedulaCliente` | 
| `IVA` |
| `Fecha` |
| `Total_pagar` |
| - RegistrarFactura |
| - ImprimirFactura |

| Producto |
| ------------- |
| `ID Producto ` | 
| `NombreProducto ` | 
| `Precio_Cantidad ` | 
| `CategoríaProducto ` |
| `CantidadProductosDisponibles ` |
| `Proveedores  ` |
| - RegistrarProductos |
| - MostrarCantidadProductosDisponibles |


| Vendedores |
| ------------- |
| `Cedula ` |
| `NombreCompleto ` | 
| `CantidadProductosVendidos ` |
| `TotalHorasLaboradas  ` |
| - IngresoVenta  |
| - TotalVentas |
