# Título Proyecto: __SmartStorage__

## Miembros del grupo L2-ABS-6

1. Calzadilla Buiza, Alberto
1. Marzoug Yous, Ibrahim
1. Páez Sosa, Álvaro
1. Martínez Escudero, Domingo

## 1. Introducción al problema

&nbsp;&nbsp;&nbsp;&nbsp;La empresa de logística SmartStorage S.L recibe, almacena, controla el inventario y distribuye productos para varios clientes del sector comercial e industrial.
  
  
&nbsp;&nbsp;&nbsp;&nbsp;Actualmente, el almacén se gestiona con un sistema semiautomático que usa hojas de cálculo y registros en papel. Cuando llega un camión con mercancía, los operarios anotan a mano los recibos y el número de lote, para posteriormente registrar la ubicación donde guardan el stock. Al preparar un pedido de salida, los operarios reciben una lista en papel con la mercancía solicitada. Después buscan los productos manualmente en las estanterías del almacén. 
<br><br>
<p align="center">
  <img width="650" height="400" alt="image" src="https://github.com/user-attachments/assets/cfde1c92-0f24-431e-b464-8abb6479f8af" />
  </p>
  
<br><br>


### __1.1 PROBLEMAS IDENTIFICADOS__

&nbsp;&nbsp;&nbsp;&nbsp;La falta de un sistema informático centralizado ha generado diversos problemas operativos graves:

&nbsp;&nbsp;&nbsp;&nbsp;__-Inexactitud del inventario__: Hay diferencias frecuentes entre la cantidad de stock anotado en las hojas de cálculo y la cantidad real de producto que hay en el almacén. Esto cauda faltas inesperadas o compras innecesarias.
  
&nbsp;&nbsp;&nbsp;&nbsp;__Automatizar el control de inventario:__ Mantener el stock actualizado en tiempo real tras cada entrada, salida o reubicación de mercancía.

&nbsp;&nbsp;&nbsp;&nbsp;__Reducir errores en pedidos:__ Validar el empaque y envío de productos para evitar referencias incorrectas o cantidades equivocadas.

&nbsp;&nbsp;&nbsp;&nbsp;__Agilizar la preparación de envíos:__ Optimizar la localización de los artículos para reducir los tiempos de búsqueda en el almacén.

&nbsp;&nbsp;&nbsp;&nbsp;__Centralizar la información:__ Disponer de consultas y reportes en tiempo real sobre las operaciones y el estado de los pedidos.
<br><br>

<p align="center">
  <img width="400" height="300" alt="image1" src="https://github.com/user-attachments/assets/50695704-b934-4f19-acd6-c749366a0d2e" />
  <img width="400" height="300" alt="image2" src="https://github.com/user-attachments/assets/597c144c-963d-4dfc-a569-e3dfadce3273" />
</p>



<br><br>


### __1.2 CLIENTES Y USUARIOS DEL SISTEMA__

&nbsp;&nbsp;&nbsp;&nbsp;El nuevo sistema interaccionará con tres grupos principales claramente diferenciados dentro del ámbito del problema:

&nbsp;&nbsp;&nbsp;&nbsp;__-Clientes:__ Usuarios externos que consultan el catálogo de productos, comprueban su disponibilidad y realizan pedidos, contando con información de contacto y dirección.

&nbsp;&nbsp;&nbsp;&nbsp;__-Empleados:__ Personal interno de la organización encargado de la gestión del inventario y las operaciones, destacando los encargados de almacén y el personal autorizado para la aprobación de compras.

&nbsp;&nbsp;&nbsp;&nbsp;__-Proveedores:__ Empresas o socios comerciales encargados de suministrar los productos al sistema mediante el registro de líneas de compra.
<br><br>






### __1.3 EXPECTATIVAS Y OBJETIVOS DEL NUEVO SISTEMA__

&nbsp;&nbsp;&nbsp;&nbsp;Con el desarrollo del nuevo Sistema de Gestión de Almacén, se espera alcanzar los siguientes objetivos estratégicos:

&nbsp;&nbsp;&nbsp;&nbsp;__-Automatizar el control de inventario:__ Mantener el stock actualizado en tiempo real tras cada movimiento de entrada, salida o reubicación.

&nbsp;&nbsp;&nbsp;&nbsp;__-Reducir tiempos y errores operativos:__ Proporcionar listas de pedidos guiadas para minimizar desplazamientos e inconsistencias en la preparación de envíos.

&nbsp;&nbsp;&nbsp;&nbsp;__-Facilitar la toma de decisiones:__ Disponer de un catálogo de consultas y listados para el análisis en tiempo real del desempeño de las operaciones.

&nbsp;&nbsp;&nbsp;&nbsp;__-Mejorar el seguimiento de los lotes:__ Asegurar que se localice con precisión cualquier producto desde que se recibe hasta que llega al cliente final.

<br><br>

<p align="center">
<img width="400" height="300" alt="image" src="https://github.com/user-attachments/assets/31320d91-8bb7-4429-a09f-1510e1ecaa7f" />
<img width="400" height="300" alt="image" src="https://github.com/user-attachments/assets/a49677e1-024e-496e-b11c-bc308031f198" />

</p>

<br><br>

## 2. Glosario de términos

| Término | Imagen | Descripción |
| :--- | :---: | :--- |
| **Almacén** | <img width="450" height="346" alt="image" src="https://github.com/user-attachments/assets/17ad5df0-43db-4e74-b8f6-a7e3a4af9456" /> | Instalación física, gestionada por un empleado, encargada del almanaje de bienes dentro de la cadena de suministro |
| **Categoría** | <img width="450" height="346" alt="image" src="https://github.com/user-attachments/assets/4a3330e6-9bd4-44e3-8795-b378ce4aaa4e" /> | Agrupación de productos que permite estructurar el catálogo. |
| **Cliente** |<img width="450" height="346" alt="image" src="https://github.com/user-attachments/assets/5bc3d3c0-5847-4a78-8f5a-db451551db3a" /> | Tipo de usuario externo del sistema que realiza pedidos de compra y cuenta con datos asociados a su usuario e incluye la dirección para localizar a este cliente. |
| **Empleado** | <img width="450" height="346" alt="image" src="https://github.com/user-attachments/assets/a85b7b3a-0311-4f63-8e0b-9247fcd3594c" /> | Tipo de usuario interno de la organización vinculado a un puesto de trabajo y fecha de ingreso, encargado de gestionar almacenes, procesar pedidos y aprobar compras. |
| **Línea de Compra** | <img width="450" height="346" alt="image" src="https://github.com/user-attachments/assets/77283850-08d9-4efe-9363-da3cc5864017" /> | Detalle de los artículos recibidos de un proveedor en un almacén específico, indicando cantidad, costo unitario, fecha, producto y el empleado que gestiona la recepción. |
| **Línea de Venta** | <img width="450" height="346" alt="image" src="https://github.com/user-attachments/assets/e9b75103-6c5f-4e17-8985-65575db2f84b" />| Detalle de los productos incluidos en un pedido de cliente, que especifica la cantidad solicitada, el precio unitario y el subtotal correspondiente. |
| **Pedido** | <img width="450" height="346" alt="image" src="https://github.com/user-attachments/assets/abb62818-84b1-4f3e-8ed4-d78952493c9c" /> | Solicitud realizada por un cliente y procesada por un empleado, la cual contiene una o más líneas de venta, un estado, una fecha y un cálculo total. |
| **Producto** | <img width="450" height="346" alt="image" src="https://github.com/user-attachments/assets/df2b13ae-10a4-4730-a6e8-bc3f129369e2" /> | Artículo comercializado en el sistema, caracterizado por un nombre, un precio y asociado obligatoriamente a una categoría y uno o varios proveedores. |
| **Proveedor** | <img width="450" height="346" alt="image" src="https://github.com/user-attachments/assets/fb02b951-820a-4e11-9a8a-ac7f3a82c972" /> | Entidad externa que suministra los productos, con la cual se registran las líneas de compra. |
| **Stock** | <img width="450" height="346" alt="image" src="https://github.com/user-attachments/assets/dc8ac227-28db-45d7-a7dd-1c7c482ce456" /> | Cantidad disponible de un producto específico en un almacén determinado, calculada en función de las entradas por compras y las salidas por ventas. |
| **Usuario** | <img width="450" height="346" alt="image" src="https://github.com/user-attachments/assets/5b2de0e6-8bf7-414c-904f-00eb4989f53f" /> | Entidad base del sistema que cuenta con un identificador, un correo electrónico único, una contraseña, un teléfono de contacto y un rol, especializándose exclusivamente como cliente o como empleado. |

## 3. Visión general del sistema

### 3.1. Requisitos generales


&nbsp;&nbsp;&nbsp;&nbsp;El sistema de SmartStorage centraliza y automatiza la organización de la empresa bajo los siguiente principios:

&nbsp;&nbsp;&nbsp;&nbsp;__-Gestión de inventario por almacén:__ El sistema calcula y actualiza el stock físico de cada producto, registrando las entradas por compras y las salidas por ventas.

&nbsp;&nbsp;&nbsp;&nbsp;__-Validación de Procesos:__ El sistema bloquea de forma automática las operaciones no permitidas, como procesar ventas sin stock suficiente o registrar cantidad y precios menores o iguales que cero.

&nbsp;&nbsp;&nbsp;&nbsp;__-Seguimiento del pedido:__ Todas las operaciones de entrada de mercancía y gestión de pedidos quedan vinculadas al empleado responsable y cliente correspondiente.

&nbsp;&nbsp;&nbsp;&nbsp;__-Exclusividad de datos:__ Para evitar que la información se duplique, cada producto debe tener un código único, los usuarios no pueden compartir el mismo correo electrónico y es obligatorio asignarle una categoría a cada artículo.

&nbsp;&nbsp;&nbsp;&nbsp;__-Registro de precios:__ Al confirmar un pedido de venta o registrar una línea de compra, los precios unitarios y costos se mantienen fijos para que no se pueda alterar el historial.

  
### 3.2. Usuarios del sistema

&nbsp;&nbsp;&nbsp;&nbsp;El sistema SmartStorage define tres perfiles de usuario bien diferenciados, estructurando sus permisos y accesos de la siguiente manera:

&nbsp;&nbsp;&nbsp;&nbsp;__-Clientes (Usuarios externos):__ Tienen acceso a la plataforma web para consultar el catálogo de productos y filtrar por categorías.

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;Pueden registrarse con un correo electrónico y contraseña, gestionar sus datos de contacto, crear pedidos y realizar un seguimiento del estado de sus compras.

&nbsp;&nbsp;&nbsp;&nbsp;__-Empleados (Personal Interno):__ Personal de la organización vinculado por fehca de ingreso y un puesto de trabajo específico que determina su nivel de acceso:

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;__Encargados:__ Tienen permiso para administrar un almacén concreto, consultar stock en tiempo real, registrar líneas de compra y validar la recepción de mercancía.

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;__Personal autorizado de compras:__ Tienen permisos específicos para aprobar compras, gestionar el aprovisionamiento del inventario y supervisar la relación con los proveedores.

&nbsp;&nbsp;&nbsp;&nbsp;__-Proveedores (Entidades externas):__ Actúan como socios comerciales de referencia en el sistema. Aunque no disponen de una interfaz de usuario, su información es indispensable para vincular líneas de compra, costes y suministro de los productos.

## 4. Catálogo de requisitos

### 4.1. Requisitos funcionales

#### ·RF-01. Consultar el catálogo de productos

&nbsp;&nbsp;&nbsp;&nbsp;Como cliente, quiero consultar el catálogo de productos y filtrarlos por categoría, para encontrar los que necesito comprar.

[Prueba de aceptación positiva — PAP-01.1]

&nbsp;&nbsp;&nbsp;&nbsp;Suponemos que existen productos pertenecientes a la categoría «Herramientas», cuando el cliente consulte dicha categoría el sistema mostrará los productos correspondientes con su nombre y precio.

[Prueba de aceptación negativa — PAN-01.1]

&nbsp;&nbsp;&nbsp;&nbsp;Suponemos que no existen productos en la categoría seleccionada, cuando el cliente realice la consulta el sistema mostrará un mensaje indicando que no se han encontrado productos, sin mostrar artículos de otras categorías.

#### ·RF-02. Registrar productos en el sistema

&nbsp;&nbsp;&nbsp;&nbsp;Como administrador del inventario, quiero consultar el registro de nuevos productos con un código único, un nombre, un precio y una categoría, para mantener actualizado el catálogo de artículos.

[Prueba de aceptación positiva — PAP-02.1]

&nbsp;&nbsp;&nbsp;&nbsp;Dado que el código «PROD-101» no está registrado y la categoría seleccionada existe, cuando el administrador introduce los datos válidos del producto, el sistema guarda el artículo y lo muestra en el catálogo.

[Prueba de aceptación negativa — PAN-02.1]

&nbsp;&nbsp;&nbsp;&nbsp;Dado que el código «PROD-101» ya pertenece a otro producto, cuando el administrador intenta registrar un segundo producto con ese mismo código, el sistema rechaza el registro e informa de que el código ya existe.

#### ·RF-03. Consultar el stock por producto y almacén

&nbsp;&nbsp;&nbsp;&nbsp;Como gestor de inventario, quiero consultar las unidades disponibles de cada producto en un almacén concreto, para conocer el stock existente antes de gestionar una operación.

[Prueba de aceptación positiva — PAP-03.1]

&nbsp;&nbsp;&nbsp;&nbsp;Suponiendo que el producto "PROD-101" tiene 25 unidades en el almacén de Sevilla, cuando el empleado consulte su stock en dicho almacén el sistema mostrará que hay 25 unidades disponibles.

[Prueba de aceptación negativa — PAN-03.1]

&nbsp;&nbsp;&nbsp;&nbsp;Suponiendo que el empleado consulta el stock de un código de producto inexistente, cuando realice la búsqueda el sistema informará de que el producto no está registrado y no presentará una cantidad de stock inventada.

#### ·RF-04. Registrar la recepción de mercancías de un proveedor

&nbsp;&nbsp;&nbsp;&nbsp;Como encargado de almacén, quiero consultar el registro de las mercancías recibidas de los proveedores indicando el producto, la cantidad, el coste unitario y el almacén de destino, para mantener actualizado el inventario.

[Prueba de aceptación positiva — PAP-04.1]

&nbsp;&nbsp;&nbsp;&nbsp;Suponemos que un producto tiene 10 unidades registradas en el almacén, cuando el encargado registre la recepción válida de 20 unidades adicionales, el sistema registrará la compra y actualizará el stock a 30 unidades.

[Prueba de aceptación negativa — PAN-04.1]

&nbsp;&nbsp;&nbsp;&nbsp;Suponemos que el encargado está registrando una recepción de mercancías, si introduce una cantidad igual a cero, entonces el sistema rechazará la operación, informará del error y mantendrá sin cambios el stock anterior.

#### ·RF-05. Consultar la ubicación de un producto

&nbsp;&nbsp;&nbsp;&nbsp;Como operario de almacén, quiero consultar la ubicación física de un producto, para localizarlo rápidamente durante la preparación de los pedidos.

[Prueba de aceptación positiva — PAP-05.1]

&nbsp;&nbsp;&nbsp;&nbsp;Dado que el producto "PROD-101" está ubicado en el pasillo 2, estantería 3, cuando el operario consulte su ubicación, el sistema mostrará esos datos para facilitar su localización.

[Prueba de aceptación negativa — PAN-05.1]

&nbsp;&nbsp;&nbsp;&nbsp;Dado que un producto no tiene ninguna ubicación registrada, cuando el operario intente localizarlo, el sistema informará de que no dispone de una ubicación asignada, sin mostrar una localización incorrecta.

#### ·RF-06. Crear pedidos de clientes

&nbsp;&nbsp;&nbsp;&nbsp;Como cliente, quiero poder realizar una búsqueda de productos para poder crear un pedido que contenga uno o varios productos y sus cantidades, para solicitar la compra de los artículos que necesito.

[Prueba de aceptación positiva — PAP-06.1]

&nbsp;&nbsp;&nbsp;&nbsp;Cuando un cliente registrado crea un pedido que contiene al menos una línea de venta con cantidades válidas, el sistema registra el pedido y lo asocia al cliente correspondiente.

[Prueba de aceptación negativa — PAN-06.1]

&nbsp;&nbsp;&nbsp;&nbsp;Si un cliente intenta confirmar un pedido sin incluir ninguna línea de venta, el sistema rechaza la operación y muestra un mensaje indicando que debe añadir al menos un producto.

#### ·RF-07. Validar el stock antes de confirmar una venta

&nbsp;&nbsp;&nbsp;&nbsp;Como empleado responsable de procesar pedidos, quiero poder consultar la disponibilidad de los productos antes de confirmar una venta, para evitar comprometer mercancía que no existe en el inventario.

[Prueba de aceptación positiva — PAP-07.1]

&nbsp;&nbsp;&nbsp;&nbsp;Al confirmar la venta de un producto del que hay 10 unidades disponibles y se solicitan 4, el sistema acepta la operación y actualiza el stock a 6 unidades.

[Prueba de aceptación negativa — PAN-07.1]

&nbsp;&nbsp;&nbsp;&nbsp;Cuando se intenta confirmar una venta de 8 unidades de un producto del que solo quedan 5 disponibles, el sistema bloquea la operación por falta de stock y mantiene las 5 unidades en el inventario.

#### ·RF-08. Validar los productos durante la preparación de un pedido

&nbsp;&nbsp;&nbsp;&nbsp;Como operario de almacén, quiero consultar que los productos y las cantidades recogidos coinciden con las líneas del pedido, para evitar enviar artículos incorrectos a los clientes.

[Prueba de aceptación positiva — PAP-08.1]

&nbsp;&nbsp;&nbsp;&nbsp;La preparación de un pedido se valida correctamente cuando el operario recoge las 3 unidades solicitadas del producto «PROD-101» y confirma que la referencia y la cantidad coinciden con las indicadas en el pedido.

[Prueba de aceptación negativa — PAN-08.1]

&nbsp;&nbsp;&nbsp;&nbsp;Si el pedido solicita el producto «PROD-101» y el operario intenta validar el producto «PROD-202», el sistema impide confirmar esa línea e informa de que la referencia recogida no coincide con la solicitada.

#### ·RF-09. Gestionar el estado de los pedidos

&nbsp;&nbsp;&nbsp;&nbsp;Como empleado responsable de los envíos, quiero consultar y actualizar el estado de los pedidos, para conocer su situación y realizar un seguimiento de su entrega.

[Prueba de aceptación positiva — PAP-09.1]

&nbsp;&nbsp;&nbsp;&nbsp;Cuando se selecciona un estado válido para un pedido ("pendiente", "en preparación", "enviado" o "entregado"), el empleado guardará la modificación y podrá consultar posteriormente el nuevo estado del pedido.

[Prueba de aceptación negativa — PAN-09.1]

&nbsp;&nbsp;&nbsp;&nbsp;Si el empleado introduce un estado no admitido, como "en ruta", el sistema rechazará la modificación, mostrará un mensaje de error y conservará el estado anterior del pedido.

#### ·RF-10. Registrar usuarios y controlar sus tipos

&nbsp;&nbsp;&nbsp;&nbsp;Como administrador del sistema, quiero consultar los registros de los usuarios con un correo electrónico único y asignarles un tipo de usuario, cliente o empleado, para mantener sus perfiles identificados y evitar duplicidades.

[Prueba de aceptación positiva — PAP-10.1]

&nbsp;&nbsp;&nbsp;&nbsp;Se probará a registrar un usuario con correo electrónico todavía no registrado en la base de datos y se le asignará el tipo "cliente". El sistema creará el perfil con éxito y podrá ser consultado.

[Prueba de aceptación negativa — PAN-10.1]  

&nbsp;&nbsp;&nbsp;&nbsp;Se probará a registrar un usuario como cliente y empleado al mismo tiempo. El sistema rechazará la operación, mandando un mensaje de error e informando de que ambas categorías son excluyentes.




### 4.1.1. Requisitos de información


##### ·R.I.01. Información de Usuario

&nbsp;&nbsp;&nbsp;&nbsp;Como administrador del sistema quiero gestionar los perfiles de usuario, roles y datos de acceso de los usuarios para garantizar la seguridad de la información de cada uno de los usuarios y restringir las operaciones según el rol de cada empleado.

[Prueba de aceptación positiva — PAP-01.1]

&nbsp;&nbsp;&nbsp;&nbsp;El administrador crea un nuevo usuario asignándole un rol y una contraseña segura; el sistema guarda el registro exitosamente y permite iniciar sesión con esos datos restringiendo las funciones de administración.

[Prueba de aceptación negativa — PAN-01.1]

&nbsp;&nbsp;&nbsp;&nbsp;El administrador intenta crear un usuario nuevo dejando el campo de correo electrónico vacío, esto provoca que el sistema rechace el registro y muestre un mensaje de error indicando que el campo es obligatorio.


##### ·R.I.02. Información de Cliente

&nbsp;&nbsp;&nbsp;&nbsp;Como responsable de ventas quiero registrar y consultar los datos de contacto, dirección y preferencias de los clientes para controlar los pedidos de salida con precisión y realizar un seguimiento de cada solicitud de pedido de cada cliente.

[Prueba de aceptación positiva — PAP-02.1]

&nbsp;&nbsp;&nbsp;&nbsp;El responsable de ventas ingresa el nombre, dirección y teléfono de un nuevo cliente, el sistema almacena correctamente la información y la muestra disponible al crear un pedido.

[Prueba de aceptación negativa — PAN-02.1]

&nbsp;&nbsp;&nbsp;&nbsp;El responsable de ventas introduce un número de teléfono con letras y caracteres no válidos, el sistema bloquea el guardado y manda un mensaje de alerta de formato incorrecto.


##### ·R.I.03. Información de Empleado

&nbsp;&nbsp;&nbsp;&nbsp;Como responsable de los empleados quiero mantener actualizada la información personal, laboral y de turnos del personal del almacén para controlar la asignación de tareas y roles de cada uno de ellos y poder ver cual es el rendimiento de los trabajadores.

[Prueba de aceptación positiva — PAP-03.1] 

&nbsp;&nbsp;&nbsp;&nbsp;El administrador registra a un nuevo empleado asignándolo al turno de la mañana, el sistema acepta el registro y actualiza la lista de personal activo en el almacén.

[Prueba de aceptación negativa — PAN-03.1]

&nbsp;&nbsp;&nbsp;&nbsp;El administrador intenta registrar a un empleado con un número de DNI que ya está registrado en el sistema, por lo tanto el sistema rechaza la operación por duplicidad.


##### ·R.I.04. Información de Producto

&nbsp;&nbsp;&nbsp;&nbsp;Como administrador del inventario quiero registrar las características detalladas de cada artículo como por ejemplo: dimensiones, peso y precio; para identificar, ubicar y vender correctamente la mercancía disponible en el almacén.

[Prueba de aceptación positiva — PAP-04.1]

&nbsp;&nbsp;&nbsp;&nbsp;El gestor de inventario da de alta un producto introduciendo supeso, dimensiones y precio de venta, el sistema crea el registro completo y genera datos para guardar correctamente el producto.

[Prueba de aceptación negativa — PAN-04.1]

&nbsp;&nbsp;&nbsp;&nbsp;El gestor de inventario intenta registrar un producto indicando un precio de venta con valor negativo, lo que provoca que el sistema detecte el error y rechace la inserción del producto.


##### ·R.I.05. Información de Categoría

&nbsp;&nbsp;&nbsp;&nbsp;Como administrador del catálogo de productos quiero organizar los productos en categorías para facilitar la búsqueda y el análisis del stock necesario por tipos de productos.

[Prueba de aceptación positiva — PAP-05.1]

&nbsp;&nbsp;&nbsp;&nbsp;El administrador del catálogo crea una categoría principal llamada "Electrónica" y una subcategoría "Smartphones", el sistema asocia correctamente la jerarquía en el árbol de categorías.

[Prueba de aceptación negativa — PAN-05.1]

&nbsp;&nbsp;&nbsp;&nbsp;El administrador intenta eliminar una categoría que actualmente tiene productos activos vinculados. Esto provoca que el sistema impida la eliminación y advierta que debe reubicar o cambiar de categoría los productos primero.


##### ·R.I.06. Información de Almacén

&nbsp;&nbsp;&nbsp;&nbsp;Como responsable de almacenaje quiero gestionar las zonas, pasillos y ubicaciones físicas del almacén para optimizar las rutas de recogida y la distribución del espacio disponible para cada categoría de productos disponibles.

[Prueba de aceptación positiva — PAP-06.1]

&nbsp;&nbsp;&nbsp;&nbsp;El supervisor del almacén configura una nueva ubicación física indicando Zona A, Pasillo 3 y Estantería 2, el sistema registra la ubicación como disponible para almacenar mercancía.


[Prueba de aceptación negativa — PAN-06.1]

&nbsp;&nbsp;&nbsp;&nbsp;El supervisor intenta crear una ubicación asignando una estantería que ya existe exactamente igual en la misma zona, el sistema rechaza el registro por conflicto de duplicidad de espacios.


##### ·R.I.07. Información de Stock

&nbsp;&nbsp;&nbsp;&nbsp;Como gestor de inventario quiero poder controlar en tiempo real la disponibilidad, las entradas, las ventas y la cantidad mínimos de cada prodcuto para evitar llegar a un stock nulo y planificar un reabastecimiento de los productos los cuales están llegando al mínimo de disponibilidad.

[Prueba de aceptación positiva — PAP-07.1]

&nbsp;&nbsp;&nbsp;&nbsp;Un operario registra la entrada física de 50 unidades de un producto, el sistema actualiza automáticamente el stock actual sumando las unidades y desactivando la alerta de stock bajo.

[Prueba de aceptación negativa — PAN-07.1] 

&nbsp;&nbsp;&nbsp;&nbsp;Un operario intenta registrar la salida de 30 unidades de un producto cuando el stock disponible es de solo 10 unidades, el sistema bloquea la transacción por falta de existencias suficientes.


##### ·R.I.08. Información de Proveedor

&nbsp;&nbsp;&nbsp;&nbsp;Como responsable del almacén quiero administrar la información de contacto, plazos de entrega y condiciones de los proveedores para coordinar las compras de mercancía de manera eficiente, para poder hacer un seguimiento de los productos que nos ofrecen los proveedores.

[Prueba de aceptación positiva — PAP-08.1] 

&nbsp;&nbsp;&nbsp;&nbsp;El responsable de compras registra un proveedor nuevo con su NIF y un plazo de entrega de 5 días hábiles, el sistema guarda los datos comerciales de forma correcta.

[Prueba de aceptación negativa — PAN-08.1]

&nbsp;&nbsp;&nbsp;&nbsp;El responsable de compras deja en blanco el campo del NIF obligatorio al intentar dar de alta al proveedor; el sistema no permite guardar el registro y destaca el campo faltante.


##### ·R.I.09. Información de Pedido

&nbsp;&nbsp;&nbsp;&nbsp;Como administrador en los envíos de porductos a los clientes quiero registrar y hacer seguimiento del estado de los pedidos de venta (pendiente, en preparación, enviado, entregado) para cumplir con los plazos de entrega acordado previamente con el cliente a la hora de realizar el pedido.

[Prueba de aceptación positiva — PAP-09.1] 

&nbsp;&nbsp;&nbsp;&nbsp;El especialista en envíos cambia el estado de un pedido de "En preparación" a "Enviado" tras la salida del producto del almacén, el sistema actualiza el estado y registra la fecha de salida.

[Prueba de aceptación negativa — PAN-09.1]

&nbsp;&nbsp;&nbsp;&nbsp;El especialista en envíos intenta marcar un pedido como "Entregado" sin haber seleccionado previamente un cliente ni productos asociados, el sistema rechaza la acción por estar incompleta la orden.


##### ·R.I.10. Información de Línea de Venta

&nbsp;&nbsp;&nbsp;&nbsp;Como gestor de la venta de los productos quiero detallar cada producto, cantidad y precio de cada venta específica para poder controlar automáticamente el stock correspondiente y poder gestionar los productos en venta disponibles .

[Prueba de aceptación positiva — PAP-10.1]

&nbsp;&nbsp;&nbsp;&nbsp;Al procesar una venta, el gestor añade 3 unidades del producto A a un precio unitario de 20€, el sistema calcula automáticamente el precio total que sería 60€ y descuenta esas 3 unidades del stock.

[Prueba de aceptación negativa — PAN-10.1] 

&nbsp;&nbsp;&nbsp;&nbsp;El usuario introduce una cantidad de venta igual a cero para un artículo en la línea de venta, el sistema rechaza la línea indicando que la cantidad mínima debe ser al menos 1.


##### ·R.I.11. Información de Línea de Compra

&nbsp;&nbsp;&nbsp;&nbsp;Como responsable de compras quiero registrar las cantidades específicas y los costes acordados para cada artículo de compra realizado por cada proveedor para verificar que la recepción de la mercancía ha sido correcta y actualizar los costes de los productos dsiponibles en el inventario. 

[Prueba de aceptación positiva — PAP-11.1] 

&nbsp;&nbsp;&nbsp;&nbsp;El gestor de compras registra una línea de compra con 100 unidades de un artículo a un coste acordado de 10€ por unidad, el sistema almacena la línea y calcula el importe total de la compra que sería de 1000€.

[Prueba de aceptación negativa — PAN-11.1] 

&nbsp;&nbsp;&nbsp;&nbsp;El gestor de compras ingresa un coste unitario con letras en lugar de números, el sistema detecta un error de tipo de dato y no permite guardar la línea de compra.




### 4.1.2. Reglas de negocio


**R.N.01. Clasificación de productos**

Todo producto debe pertenecer obligatoriamente a una única categoria.

[Prueba de aceptación positiva — PAP-01.1]

Al registrar un nuevo producto en el sistema, si el administrador selecciona una categoría existente para asociarla a un artículo, el sistema guarda correctamente el producto en dicha categoría.

[Prueba de aceptación negativa — PAP-01.1]

Durante el alta de un nuevo producto, si el administrador intenta dejar el campo de categoría vacío o asignarle simultáneamente varias categorías, el sistema rechaza la operación e informa que el producto debe pertenecer a una única categoría. 


**R.N.02. Tipos de usuario**

&nbsp;&nbsp;&nbsp;&nbsp;Un usuario puede estar registrado como cliente, empleado o proveedor, pero nunca como varios al mismo tiempo.

[Prueba de aceptación positiva — PAP-02.1]

Al registrar un nuevo usuario en la plataforma con un correo único y asignarle el rol de "Cliente", el sistema crea el perfil con éxito como cliente sin registrarlo como empleado.

[Prueba de aceptación negativa — PAP-02.1]

Cuando un usuario intenta registrarse en el sistema indicando de forma simultánea los roles de "Cliente" y "Empleado", el sistema bloquea el registro y muestra un error indicando que ambas categorías no pueden ser seleccionadas al mismo tiempo.


**R.N.03. Gestión de pedidos**

&nbsp;&nbsp;&nbsp;&nbsp;Todo pedido debe estar asociado a un CLIENTE que lo realiza y a un EMPLEADO encargado de procesarlo.

[Prueba de aceptación positiva — PAP-03.1]

Tras realizar un pedido válido, si el empleado responsable lo procesa y se asignan ambos identificadores en el sistema, el pedido se guarda quedando vinculado el cliente y el empleado correspondiente

[Prueba de aceptación negativa — PAP-03.1]

Al intentar confirmar un pedido sin haber asignado un empleado encargado de procesarlo, el sistema rechaza la orden por estar incompleta y no permite guardarla


**R.N.04. Contenido de los pedidos**

&nbsp;&nbsp;&nbsp;&nbsp;Todo pedido debe contener al menos una linea de venta, correspondiente a un producto solicitado por el cliente.

[Prueba de aceptación positiva — PAP-04.1]

Cuando un cliente crea una solicitud de compra y añade a su cesta al menos una línea de venta con un producto y cantidad válidos, el sistema acepta el pedido con éxito.

[Prueba de aceptación negativa — PAP-04.1]

En la situación de que un cliente intente confirmar un pedido cuya orden no incluye ninguna línea de venta, el sistema rechaza la operación y muestra un mensaje indicando que debe añadir al menos un producto.

**R.N.05. Cantidades y precios de venta**

&nbsp;&nbsp;&nbsp;&nbsp;En cada linea de venta, la cantidad solicitada debe ser mayor que cero y el precio unitario del producto también debe ser positivo.

[Prueba de aceptación positiva — PAP-05.1]

Al procesar una línea de venta introduciendo 3 unidades de un artículo a un precio de 20€(ambos mayores que cero), el sistema acepta la línea y calcula correctamente el total.

[Prueba de aceptación negativa — PAP-05.1]

Si el usuario añade un artículo la línea de venta indicando una cantidad igual a cero o un precio negativo, el sistema rechaza la línea indicando que la cantidad y el precio deben ser estrictamente mayores que cero

**R.N.06. Precio válido de los productos**

&nbsp;&nbsp;&nbsp;&nbsp;El precio de un producto no podrá ser negativo, evitando registrar artículos con valores económicos incorrectos.

[Prueba de aceptación positiva — PAP-06.1]

Al dar de alta un producto en el inventario con un precio de venta de 45€, el sistema valida que es un valor positivo y se almacena el artículo correctamente en el catálogo.

[Prueba de aceptación negativa — PAP-06.1]

Durante el registro de un artículo, si el usuario introduce un precio de venta con un valor negativo(por ejemplo, -10€), el sistema detecta el error mediante la restricción y rechaza la inserción del producto.

**R.N.07. Disponibilidad de inventario**

&nbsp;&nbsp;&nbsp;&nbsp;No se podrá confirmar la venta de un producto si la cantidad solicitada supera las unidades disponibles en stock. En ese caso, el pedido deberá rechazarse o esperar hasta tener suficientes unidades.

[Prueba de aceptación positiva — PAP-07.1]

Partiendo de un producto que cuenta con un stock de 10 unidades disponibles, al solicitar la compra de 4 unidades, el sistema acepta la transacción y actualiza automáticamente el inventario restando la cantidad vendida.

[Prueba de aceptación negativa — PAP-07.1]

Cuando se intenta confirmar una venta de 8 unidades de un producto del que únicamente se dispone de 5 unidades en stock, el sistema bloquea la operación por falta de existencias y mantiene intacto el inventario.

### 4.2. Mapa de historias de usuario (opcional)
&nbsp;&nbsp;&nbsp;&nbsp;__H.U.01:__  El cliente entra a la plataforma y consulta qué productos hay disponibles y su precio.

&nbsp;&nbsp;&nbsp;&nbsp;__H.U.02:__  El cliente elige los productos, indica las cantidades y ordena un pedido.

&nbsp;&nbsp;&nbsp;&nbsp;__H.U.03:__ El cliente consulta el estado de su pedido (en preparación, enviado, entregado)

&nbsp;&nbsp;&nbsp;&nbsp;__H.U.04:__ El empleado consulta el stock real que queda de cada producto en el almacén.

&nbsp;&nbsp;&nbsp;&nbsp;__H.U.05:__ El empleado coge los pedidos que han hecho los clientes, los procesa y valida la salida de mercancía del almacén.

&nbsp;&nbsp;&nbsp;&nbsp;__H.U.06:__ El encargado del almacén registra la llegada de nuevos productos de los proveedores para reponer el inventario.


### 4.3. Requisitos no funcionales (opcional)

__R.N.F.01. Facilidad de uso__

&nbsp;&nbsp;&nbsp;&nbsp;Como usuario, quiero que el sistema tenga una interfaz sencilla e intuitiva para poder utilizarlo sin dificultades.

__R.N.F.02. Seguridad__

&nbsp;&nbsp;&nbsp;&nbsp;Como usuario, quiero que mis datos personales estén protegidos para evitar que otras personas puedan acceder a ellos sin autorización.

__R.N.F.03. Rendimiento__

&nbsp;&nbsp;&nbsp;&nbsp;Como cliente, quiero que las consultas de productos se realicen rápidamente para poder consultar el catálogo sin largas esperas.

__R.N.F.04. Compatibilidad__

&nbsp;&nbsp;&nbsp;&nbsp;Como usuario, quiero que el sistema funcione en distintos navegadores web para poder acceder a él desde diferentes ordenadores.

__R.N.F.05 Disponibilidad__

&nbsp;&nbsp;&nbsp;&nbsp;Como usuario, quiero que la plataforma esté accesible de forma continua y así poder consultar el catálogo o gestionar el inventario en cualquier momento.

__R.N.F.06 Tiempo de respuesta en las búsquedas__

&nbsp;&nbsp;&nbsp;&nbsp;Como empleado, quiero que las búsquedas específicas por código o nombre tarde menos de dos segundos en mostrar los resultados para agilizar el trabajo.

__R.N.F.07 Recuperación ante fallos__

&nbsp;&nbsp;&nbsp;&nbsp;Como administrador del sistema, quiero que la plataforma cuente con mecanismos de copia de seguridad constantes para garantizar la seguridad del sistema en caso de fallo.

__R.N.F.08 Adaptabilidad__

&nbsp;&nbsp;&nbsp;&nbsp;Como usuario, quiero que la interfaz de la plataforma se adapte tanto a pantallas de ordenador como teléfonos móviles para poder consultar su información desde cualquier dispositivo.

-- fin entregable 1 --

## 5. Modelo conceptual

### 5.1. Diagramas de clases UML
<br><br>
<p align="center">
<img width="2000" height="1000" alt="Captura de pantalla 2026-11-04 115203" src="https://github.com/user-attachments/assets/fccb3119-d10d-4602-b0e2-1b1918154d39" />
</p>
<br><br>

### 5.2. Escenarios de prueba

- con descripción textual y diagrama de objetos UML.

### - PRUEBA 1: Creación de un pedido y validación de stock

  ## 1.1 Descripción textual

  &nbsp;&nbsp;&nbsp;&nbsp; Un cliente registrado (José López) desea realiza un pedido de compra de 2 unidades del producto "Taladro" (PROD-101). El sistema comprueba mediante las reglas de negocio que haya stock suficiente en el inventario (hay 10 unidades disponibles). Al validarse correctamente, el sistema crea el objeto "Pedido", genera su "Línea de venta" correspondiente, vincula al cliente y al empleado encargado de procesarlo, y descuenta automáticamente las unidades del "Stock", dejando el pedido en estado "pendiente".

  ## 1.2 Diagrama UML

  
### - PRUEBA 2: Registro de recepción de mercancía de un proveedor

  ## 2.1 Descripción textual

  &nbsp;&nbsp;&nbsp;&nbsp; Un camión de un proveedor habitual (Ferretería Manolo S.L.) llega al almacén central. El encargado de almacén (Carlos Gómez) registra la entrada de 50 nuevas del producto "Martillo" (PROD-202). El sistema crea una nueva "Línea de Compra" con el coste acordado, localiza el "Almacén" y actualiza "Stock" sumando las nuevas unidades al inventario físico disponible para que los operarios puedan volver a comerciazarlas.

  ## 2.2 Diagrama UML


## 6. Matrices de trazabilidad

- Matriz de trazabilidad entre los elementos del modelo conceptual y los requisitos.

|       | Entidades  | Asociaciones  | Restricciones  | 
|:------|:-----------|:-----------|:-----------|
| R.I.01. Información de Usuario  | Usuario<br>Cliente<br>Empleado  | Especialización Usuario -> Cliente, Empleado, Proveedor  | Correo no nulo y único<br>Cliente y Empleado exclusivos  |
| R.I.02. Información de Cliente  | Cliente           | Cliente realiza Pedido  | -  |
| R.I.03. Información de Empleado  | Empleado  | Empleado gestiona Línea_compra<br>Empleado trabaja en Almacén<br>Empleado gestiona Pedido  | DNI único  |
| R.I.04. Información de Producto  | Producto  | Línea_compra pertenece a Producto<br>Proveedor suministra Producto<br>Producto corresponde a Categoría<br>Producto registra Stock<br>Producto se rellena con Pedido  | ID Producto único<br>Precio Producto >= 0  |
| R.I.05. Información de Categoría  | Categoría<br>Producto  | Producto corresponde a Categoría  | 1 Categoría por Producto<br>No eliminar categorías con productos activos  |
| R.I.06. Información de Almacén  | Almacén<br>Ubicación  | Empleado trabaja en Almacén<br>Línea_compra abastece Almacén  | Sin ubicaciones duplicadas en una misma zona  |
| R.I.07. Información de Stock  | Producto<br>Almacén<br>Stock  | Línea_compra abastece Almacén<br>Producto registra Stock<br>Producto se relaciona con Pedido  | No vender más unidades de las disponibles  |
| R.I.08. Información de Proveedor  | Producto<br>Proveedor<br>Línea de Compra  | Línea_compra pertenece a Producto<br>Proveedor suministra a Producto  | NIF de Proveedor no nulo  |
| R.I.09. Información de Pedido  | Cliente<br>Empleado<br>Pedido<br>Línea de Venta  | Cliente realiza Pedido<br>Empleado gestiona Pedido<br>Producto se relaciona con Pedido  | 1 Cliente y 1 Empleado por Pedido<br>1 Línea de Venta<br>Estado con valores permitidos  |
| R.I.10. Información de Línea de Venta  | Producto<br>Pedido<br>Línea de Venta  | -  | Cantidad y Precio Unitario > 0  |
| R.I.11. Información de Línea de Compra  | Empleado<br>Producto<br>Almacén<br>Proveedor<br>Línea de Compra  | Empleado gestiona Línea_compra<br>Línea_compra abastece Almacén<br>Línea_compra pertenece a Producto  | Cantidad > 0  |


|       | Entidades  | Asociaciones  | Restricciones  |
|:------|:-----------|:--------------|:---------------|
| RF-01. Consultar el catálogo de productos |  |  |  |
| RF-02. Registrar productos en el sistema |  |  |  |
| RF-03. Consultar el stock por producto y almacén |  |  |  |
| RF-04. Registrar la recepción de mercancías de un proveedor |  |  |  |
| RF-05. Consultar la ubicación de un producto |  |  |  |
| RF-06. Crear pedidos de clientes |  |  |  |
| RF-07. Validar el stock antes de confirmar una venta |  |  |  |
| RF-08. Validar los productos durante la preparación de un pedido |  |  |  |
| RF-09. Gestionar el estado de los pedidos |  |  |  |
| RF-10. Registrar usuarios y controlar sus tipos |  |  |  |


|       | Entidades  | Asociaciones  | Restricciones  |
|:------|:-----------|:--------------|:---------------|
| R.N.01. Clasificación de productos |  |  |  |
| R.N.02. Tipos de usuario |  |  |  |
| R.N.03. Gestión de pedidos |  |  |  |
| R.N.04. Contenido de los pedidos |  |  |  |
| R.N.05. Cantidades y precios de venta |  |  |  |
| R.N.06. Precio válido de los productos |  |  |  |
| R.N.07. Disponibilidad de inventario |  |  |  |


-- fin entregable 2 --

## 7. Modelo relacional en 3FN

- Relaciones obtenidas al aplicar la transformación del modelo conceptual.

### 7.1.  Justificación de la estrategia de transformación de jerarquías

- si se identificaron jerarquías en el MC.


### 8. Matriz de trazabilidad MC/SQL (opcional):

- Restricciones sobre el MC / Elementos del modelo tecnológico (SQL) (Triggers, checks, etc.)
- Incluir Reglas de negocio — Constraints/Triggers en las matrices de trazabilidad para el entregable 3

|       | EntidadX   | AsociaciónX  | RestricciónX  | Entidad2 ...   | 
|:-------|:-------|:-------|:-------|:-------|
| TABLA-1 |        |        |        |        |
| TABLA-2 |        |        |        |        |
| TABLA-3 |        |        |        |        |
| TABLA-4 |        |        |        |        |
| TRIG-1 |        |        |        |        |
| TRIG-2 | X      | X      |        | X      |
| TRIG-3 |        | X      |        | X      |
| TRIG-4 |        |        | X      |        |
| CONST-1 |        |        |        |        |
| CONST-2 | X      | X      |        | X      |
| CONST-3 |        | X      |        | X      |
| CONST-4 |        |        | X      |        |

Se consideran todo tipo de constraints declarativas (aquellas definidas durante el CREATE TABLE).
-- fin entregable 3 --

## Referencias


