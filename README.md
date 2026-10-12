# Título Proyecto: __SmartStorage__

## Miembros del grupo LX-XXX-X (sustituir)

1. Calzadilla Buiza, Alberto
1. Apellidos, Nombre
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

- Términos específicos del dominio del problema, ordenados alfabéticamente. Se valorará la presencia de información multimedia.

## 3. Visión general del sistema

### 3.1. Requisitos generales

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

**Prueba de aceptación**
- Descripción de la primera comprobación a realizar
- Descripción de la segunda comprobación a realizar
- ...

#### 4.1.2. Reglas de negocio

##### R.N.01. Título regla negocio

Descripción de la regla de negocio.

### 4.2. Mapa de historias de usuario (opcional)

### 4.3. Requisitos no funcionales (opcional)

**R.N.F. 01. Título requisito no funcional**
Como [tipo de usuario]
quiero [servicio]
para [razón]

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


