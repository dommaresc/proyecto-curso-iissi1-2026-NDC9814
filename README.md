# Título Proyecto: __SmartStorage__

## Miembros del grupo LX-XXX-X (sustituir)

1. Calzadilla Buiza, Alberto
1. Marzoug Yous, Ibrahim
1. Apellidos, Nombre
1. Apellidos, Nombre

## 1. Introducción al problema

  La empresa de logística SmartStorage S.L recibe, almacena, controla el inventario y distribuye productos para varios clientes del sector comercial e industrial.
  
  
  Actualmente, el almacén se gestiona con un sistema semiautomático que usa hojas de cálculo y registros en papel. Cuando llega un camión con mercancía, los operarios anotan a mano los recibos y el número de lote, para posteriormente registrar la ubicación donde guardan el stock. Al preparar un pedido de salida, los operarios reciben una lista en papel con la mercancía solicitada. Después buscan los productos manualmente en las estanterías del almacén. 
<br><br>
<p align="center">
  <img width="650" height="400" alt="image" src="https://github.com/user-attachments/assets/cfde1c92-0f24-431e-b464-8abb6479f8af" />
  </p>
  
<br><br>


__1.1 PROBLEMAS IDENTIFICADOS__

La falta de un sistema informático centralizado ha generado diversos problemas operativos graves:

  -__Inexactitud del inventario__: Hay diferencias frecuentes entre la cantidad de stock anotado en las hojas de cálculo y la cantidad real de producto que hay en el almacén. Esto cauda faltas inesperadas o compras innecesarias.
  
  -__Pérdidas de tiempo__: Los operarios pierden una cantidad de tiempo considerable buscando mercancía en los almacenes, debido a que no hay un control a tiempo real de las ubicaciones del stock.
  
  -__Errores en la preparación de pedidos__:  Si no hay una validación automática durante el proceso de empaque y envío, se mandan referencias incorrectas o cantidades equivocadas a los clientes finales.
  
  -__Errores humanos por registro de datos__: Al pasar la información de los registros en papel a las hojas de cálculo, se cometen errores frecuentes de tipeo que corrompen el historial de entradas y salidas de mercancía.

<br><br>

<p align="center">
  <img width="450" height="350" alt="image1" src="https://github.com/user-attachments/assets/50695704-b934-4f19-acd6-c749366a0d2e" />
  <img width="450" height="350" alt="image2" src="https://github.com/user-attachments/assets/597c144c-963d-4dfc-a569-e3dfadce3273" />
</p>



<br><br>


__1.2 CLIENTES Y USUARIOS DEL SISTEMA__

El nuevo sistema interaccionará con tres grupos principales claramente diferenciados dentro del ámbito del problema:

__Clientes:__ Usuarios externos que realizan pedidos en la plataforma, consultando la disponibilidad de los artículos y el catálogo de productos, realizando un seguimiento de sus compras. Cada cliente contará con información asociado a su contacto (teléfono y dirección).

__Empleados:__ Personal interno de la organización vinculado a la empresa desde determinada fecha de ingreso y ocupando un rol específico. Destacando los siguientes roles:

  __-Encargados/Gestores de almacén:__ Empleados responsables de gestionar un almacén específico y supervisar la entrada de mercancías al inventario del local.
  
  __-Personal Autorizado:__ Empleados con un rol específico para aprobar compras y registrar órdenes de aprovisionamiento con proveedores.

__Proveedores:__ Empresas o socios comerciales encargados de suministrar productos al sistema y con quienes se registran las líneas de compra





__1.3 EXPECTATIVAS Y OBJETIVOS DEL NUEVO SISTEMA__

Con el desarrollo del nuevo Sistema de Gestión de Almacén, se espera alcanzar los siguientes objetivos estratégicos:

__-Automatizar el control de inventario:__ Mantener el stock actualizado en tiempo real tras cada movimiento de entrada, salida o reubicación.

__-Reducir tiempos y errores operativos:__ Proporcionar listas de pedidos guiadas para minimizar desplazamientos e inconsistencias en la preparación de envíos.

__-Facilitar la toma de decisiones:__ Disponer de un catálogo de consultas y listados para el análisis en tiempo real del desempeño de las operaciones.

__-Mejorar el seguimiento de los lotes:__ Asegurar que se localice con precisión cualquier producto desde que se recibe hasta que llega al cliente final.

<br><br>

<p align="center">
<img width="450" height="350" alt="image" src="https://github.com/user-attachments/assets/31320d91-8bb7-4429-a09f-1510e1ecaa7f" />
<img width="450" height="350" alt="image" src="https://github.com/user-attachments/assets/a49677e1-024e-496e-b11c-bc308031f198" />

</p>

<br><br>

## 2. Glosario de términos

| Término | Imagen | Descripción |
| :--- | :---: | :--- |
| **Almacén** | <img width="740" height="494" alt="image" src="https://github.com/user-attachments/assets/17ad5df0-43db-4e74-b8f6-a7e3a4af9456" /> | Instalación física, gestionada por un empleado, encargada del almanaje de bienes dentro de la cadena de suministro |
| **Categoría** | <img width="229" height="148" alt="image" src="https://github.com/user-attachments/assets/4a3330e6-9bd4-44e3-8795-b378ce4aaa4e" /> | Agrupación de productos que permite estructurar el catálogo. |
| **Cliente** |<img width="450" height="346" alt="image" src="https://github.com/user-attachments/assets/5bc3d3c0-5847-4a78-8f5a-db451551db3a" /> | Tipo de usuario externo del sistema que realiza pedidos de compra y cuenta con datos asociados a su usuario e incluye la dirección para localizar a este cliente. |
| **Empleado** | <img width="612" height="408" alt="image" src="https://github.com/user-attachments/assets/a85b7b3a-0311-4f63-8e0b-9247fcd3594c" /> | Tipo de usuario interno de la organización vinculado a un puesto de trabajo y fecha de ingreso, encargado de gestionar almacenes, procesar pedidos y aprobar compras. |
| **Línea de Compra** | <img width="304" height="166" alt="image" src="https://github.com/user-attachments/assets/77283850-08d9-4efe-9363-da3cc5864017" /> | Detalle de los artículos recibidos de un proveedor en un almacén específico, indicando cantidad, costo unitario, fecha, producto y el empleado que gestiona la recepción. |
| **Línea de Venta** | <img width="554" height="554" alt="image" src="https://github.com/user-attachments/assets/e9b75103-6c5f-4e17-8985-65575db2f84b" />| Detalle de los productos incluidos en un pedido de cliente, que especifica la cantidad solicitada, el precio unitario y el subtotal correspondiente. |
| **Pedido** | <img width="447" height="447" alt="image" src="https://github.com/user-attachments/assets/abb62818-84b1-4f3e-8ed4-d78952493c9c" /> | Solicitud realizada por un cliente y procesada por un empleado, la cual contiene una o más líneas de venta, un estado, una fecha y un cálculo total. |
| **Producto** | <img width="447" height="447" alt="image" src="https://github.com/user-attachments/assets/df2b13ae-10a4-4730-a6e8-bc3f129369e2" /> | Artículo comercializado en el sistema, caracterizado por un nombre, un precio y asociado obligatoriamente a una categoría y uno o varios proveedores. |
| **Proveedor** | <img width="632" height="486" alt="image" src="https://github.com/user-attachments/assets/fb02b951-820a-4e11-9a8a-ac7f3a82c972" /> | Entidad externa que suministra los productos, con la cual se registran las líneas de compra. |
| **Stock** | <img width="1024" height="594" alt="image" src="https://github.com/user-attachments/assets/dc8ac227-28db-45d7-a7dd-1c7c482ce456" /> | Cantidad disponible de un producto específico en un almacén determinado, calculada en función de las entradas por compras y las salidas por ventas. |
| **Usuario** | <img width="447" height="447" alt="image" src="https://github.com/user-attachments/assets/5b2de0e6-8bf7-414c-904f-00eb4989f53f" /> | Entidad base del sistema que cuenta con un identificador, un correo electrónico único, una contraseña, un teléfono de contacto y un rol, especializándose exclusivamente como cliente o como empleado. |

## 3. Visión general del sistema

### 3.1. Requisitos generales


El sistema de SmartStorage centraliza y automatiza la organización de la empresa bajo los siguiente principios:

  __Gestión de inventario por almacén:__ El sistema calcula y actualiza el stock físico de cada producto, registrando las entradas por compras y las salidas por ventas.

  __Validación de Procesos:__ El sistema bloquea de forma automática las operaciones no permitidas, como procesar ventas sin stock suficiente o registrar cantidad y precios menores o iguales que cero.

  __Seguimiento del pedido:__ Todas las operaciones de entrada de mercancía y gestión de pedidos quedan vinculadas al empleado responsable y cliente correspondiente.

  __Exclusividad de datos:__ Para evitar que la información se duplique, cada producto debe tener un código único, los usuarios no pueden compartir el mismo correo electrónico y es obligatorio asignarle una categoría a cada artículo.

  __Registro de precios:__ Al confirmar un pedido de venta o registrar una línea de compra, los precios unitarios y costos se mantienen fijos para que no se pueda alterar el historial.

  
### 3.2. Usuarios del sistema

## 4. Catálogo de requisitos

### 4.1. Requisitos funcionales

#### R.F.01. Título requisito funcional

Como [tipo de usuario]
quiero [servicio]
para [razón]

**Prueba de aceptación**
- Descripción de la primera comprobación a realizar
- Descripción de la segunda comprobación a realizar
- Se debe aplicar la regla de negocio R.N.XX.
- ...

#### 4.1.1. Requisitos de información

##### R.I.01. Título requisito de información

Como [tipo de usuario]
quiero [servicio]
para [razón]

##### R.I.01. Información de Usuario

Como administrador del sistema quiero gestionar los perfiles de usuario, roles y datos de acceso de los usuarios para garantizar la seguridad de la información de cada uno de los usuarios y restringir las operaciones según el rol de cada empleado.

##### R.I.02. Información de Cliente

Como responsable de ventas quiero registrar y consultar los datos de contacto, dirección y preferencias de los clientes para controlar los pedidos de salida con precisión y realizar un seguimiento de cada solicitud de pedido de cada cliente.

##### R.I.03. Información de Empleado

Como responsable de los empleados quiero mantener actualizada la información personal, laboral y de turnos del personal del almacén para controlar la asignación de tareas y roles de cada uno de ellos y poder ver cual es el rendimiento de los trabajadores.

##### R.I.04. Información de Producto

Como administrador del inventario quiero registrar las características detalladas de cada artículo como por ejemplo: dimensiones, peso y precio; para identificar, ubicar y vender correctamente la mercancía disponible en el almacén.

##### R.I.05. Información de Categoría

Como administrador del catálogo de productos quiero organizar los productos en categorías para facilitar la búsqueda y el análisis del stock necesario por tipos de productos.

##### R.I.06. Información de Almacén

Como responsable de almacenaje quiero gestionar las zonas, pasillos y ubicaciones físicas del almacén para optimizar las rutas de recogida y la distribución del espacio disponible para cada categoría de productos disponibles.

##### R.I.07. Información de Stock

Como gestor de inventario quiero poder controlar en tiempo real la disponibilidad, las entradas, las ventas y la cantidad mínimos de cada prodcuto para evitar llegar a un stock nulo y planificar un reabastecimiento de los productos los cuales están llegando al mínimo de disponibilidad.

##### R.I.08. Información de Proveedor

Como responsable del almacén quiero administrar la información de contacto, plazos de entrega y condiciones de los proveedores para coordinar las compras de mercancía de manera eficiente, para poder hacer un seguimiento de los productos que nos ofrecen los proveedores.

##### R.I.09. Información de Pedido

Como administrador en los envíos de porductos a los clientes quiero registrar y hacer seguimiento del estado de los pedidos de venta (pendiente, en preparación, enviado, entregado) para cumplir con los plazos de entrega acordado previamente con el cliente a la hora de realizar el pedido.

##### R.I.10. Información de Línea de Venta

Como gestor de la venta de los productos quiero detallar cada producto, cantidad y precio de cada venta específica para poder controlar automáticamente el stock correspondiente y poder gestionar los productos en venta disponibles .

##### R.I.11. Información de Línea de Compra

Como responsable de compras quiero registrar las cantidades específicas y los costes acordados para cada artículo de compra realizado por cada proveedor para verificar que la recepción de la mercancía ha sido correcta y actualizar los costes de los productos dsiponibles en el inventario. 

**Prueba de aceptación**
- Descripción de la primera comprobación a realizar
- Descripción de la segunda comprobación a realizar
- ...

#### 4.1.2. Reglas de negocio

##### ### 4.1.2. Reglas de negocio

**R.N.01. Clasificación de productos**

Todo producto debe pertenecer obligatoriamente a una única categoria.

**R.N.02. Tipos de usuario**

Un usuario puede estar registrado como cliente o como empleado, pero nunca como ambos al mismo tiempo.

**R.N.03. Gestión de pedidos**

Todo pedido debe estar asociado a un CLIENTE que lo realiza y a un EMPLEADO encargado de procesarlo.

**R.N.04. Contenido de los pedidos**

Todo pedido debe contener al menos una linea de venta, correspondiente a un producto solicitado por el cliente.

**R.N.05. Cantidades y precios de venta**

En cada linea de venta, la cantidad solicitada debe ser mayor que cero y el precio unitario del producto también debe ser positivo.

**R.N.06. Precio válido de los productos**

El precio de un producto no podrá ser negativo, evitando registrar artículos con valores económicos incorrectos.

**R.N.07. Disponibilidad de inventario**

No se podrá confirmar la venta de un producto si la cantidad solicitada supera las unidades disponibles en stock. En ese caso, el pedido deberá rechazarse o esperar hasta tener suficientes unidades.

### 4.2. Mapa de historias de usuario (opcional)
H.U.01: Como cliente, quiero consultar los productos disponibles para conocer los artículos que puedo comprar.

H.U.02: Como cliente, quiero realizar pedidos de productos para adquirir los artículos que necesito.

H.U.03: Como cliente, quiero consultar el estado de mis pedidos para conocer su situación.

H.U.04: Como empleado, quiero consultar el stock de los productos para conocer las unidades disponibles en cada almacén.

H.U.05: Como empleado, quiero procesar los pedidos de los clientes para gestionar las ventas.

H.U.06: Como empleado, quiero registrar las compras recibidas de los proveedores para mantener actualizado el inventario.

### 4.3. Requisitos no funcionales (opcional)

**R.N.F. 01. Título requisito no funcional**
Como [tipo de usuario]
quiero [servicio]
para [razón]

R.N.F.01. Facilidad de uso

Como usuario, quiero que el sistema tenga una interfaz sencilla e intuitiva para poder utilizarlo sin dificultades.

R.N.F.02. Seguridad

Como usuario, quiero que mis datos personales estén protegidos para evitar que otras personas puedan acceder a ellos sin autorización.

R.N.F.03. Rendimiento

Como cliente, quiero que las consultas de productos se realicen rápidamente para poder consultar el catálogo sin largas esperas.

R.N.F.04. Compatibilidad

Como usuario, quiero que el sistema funcione en distintos navegadores web para poder acceder a él desde diferentes ordenadores.

-- fin entregable 1 --

## 5. Modelo conceptual

### 5.1. Diagramas de clases UML

- con restricciones.

### 5.2. Escenarios de prueba

- con descripción textual y diagrama de objetos UML.

## 6. Matrices de trazabilidad

- Matriz de trazabilidad entre los elementos del modelo conceptual y los requisitos.

|       | EntidadX   | AsociaciónX  | RestricciónX  | Entidad2 ...   | 
|:------|:-----------|:-----------|:-----------|:-----------|
| RI-1  | X          | X          | X          | X          |
| RI-2  |            | X          |            | X          |
| RF-1  |            | X          |            | X          |
| RF-2  | X          |            | X          | X          |
| RN-1  |            | X          |            |            |
| RN-2  | X          | X          | X          |            |
| ...   |            |            |            |            |

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


