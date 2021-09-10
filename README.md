# SIFI
Universidad Libre | Trabajo de POO: Sistema de Facturación e Inventario.

DIAGRAMA DE CLASES Y ATRIBUTOS.

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
