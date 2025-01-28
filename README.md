# Farmacia
# Diagrama de Clases

![Image](https://github.com/user-attachments/assets/aae2a1a6-ba3b-46c3-a9b8-4a4cf46b9264)

Este proyecto está organizado en aplicaciones modulares, donde cada aplicación tiene su propia lógica y responsabilidades específicas
Funciones de cada aplicación
usuarios: Maneja la autenticación y registro de usuarios con roles específicos (administrador, empleado, cliente).
inventarios: Gestiona los productos, sucursales y el stock disponible en cada sucursal.
ventas: Maneja las ventas de productos y los detalles de cada venta.
transferencias: Permite transferir productos entre sucursales.
pedidos: Registra los pedidos realizados por los clientes, incluyendo sucursal de retiro.
Flujo del proyecto
Usuarios:

Los usuarios se registran o inician sesión.
Dependiendo del rol, acceden a diferentes funcionalidades.
Inventarios:

Los productos se crean y asignan a sucursales.
El stock se actualiza manualmente o mediante transferencias.
Ventas:

Los empleados registran ventas realizadas en la sucursal actual.
Cada venta incluye productos, cantidad, y total.
Transferencias:

Si un producto no está disponible en una sucursal, se transfiere desde otra sucursal.
Pedidos:

Los clientes hacen pedidos que se registran con el producto, la sucursal de retiro, y el estado.
