# T1_POO
Cafetería Universitaria 
Contexto del caso
Sistema de gestión de pedidos para una cafetería
Una cafetería universitaria desea implementar un pequeño sistema que permita
gestionar los pedidos realizados por sus clientes.
Actualmente, los pedidos se registran manualmente, lo que dificulta conocer los
pedidos realizados por cada cliente y calcular correctamente los importes.
El sistema debe permitir registrar la información básica de un cliente y sus pedidos.
De cada cliente se desea almacenar:
• Código del cliente.
• Nombre completo.
• Correo electrónico.
Un cliente puede realizar uno o varios pedidos.
De cada pedido se desea almacenar:
• Código del pedido.
• Descripción del producto solicitado.
• Precio unitario.
• Cantidad.
• Estado del pedido: PENDIENTE, ATENDIDO o CANCELADO.
El sistema debe permitir:
1. Registrar clientes.
2. Agregar pedidos a un cliente.
3. Mostrar los datos del cliente y sus pedidos.
4. Calcular el importe de cada pedido.
5. Determinar el importe total de los pedidos de un cliente.
6. Buscar un pedido por su código.
7. Cambiar el estado de un pedido.
8. Validar que los datos ingresados sean correctos.
9. 
Restricciones del negocio

• El código del cliente no debe estar vacío.
• El código del pedido debe ser único dentro del cliente.
• El precio y la cantidad deben ser mayores que cero.
• Un pedido solamente puede tener uno de los tres estados establecidos.
• Un cliente puede tener varios pedidos.
• No se deben permitir pedidos duplicados por código.
• Los atributos de las clases deben estar encapsulados
