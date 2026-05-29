# Sistemas-de-Informaci-n- ARMORPC
Nombre de la Empresa o Caso de Estudio: ARMOR PC
Sector Económico: Tienda Virtual
Descripción del Problema/Necesidad: Lograr tener un crecimiento a nivel nacional ofreciendo hardware de calidad ya sea para las empresas pequeñas como también empresas grandes.
Objetivo General del Proyecto: Realizar la distribución de componentes de hardware y equipos especializados en alto rendimiento.

ENTRADAS:
1. GPU
2. CPU
3. BOARD
4. RAM
5. HDD-SDD
6. PSU
7. CHASIS
   Administrador de importacion
   Son numeros (seriales)

PROCESOS
   Validación de los componentes ingresados
   Verificación de las unidades requeridas
   Registra y guarda la información obtenida mediante la validación y verificación

SALIDAS
   venta de un componente
   reporte y solicitud garantía
   se usa libremente
   
USUARIOS
   -ADMIN
   -COMPRADOR

   -NO, solo el admin puede ver toda la información de la página, es decir: el inventario, modificación, actualizar y eliminar

   El comprador solo puede visualizar el stock para realizar la compra
   solicitud de una garantía

   No tiene permisos porque solo puede realizar compras

   INFORMACION

   Los recibos, garantías con proveedores
   la información registrada de la empresa (BASE DE DATOS)

Avance del proyecto:
1. Contexto Administrativo:
Contexto Administrativo: Para nuestro sistema ARMOR-PC enfocado en la venta de componentes de hardware apoya una estructura descentralizada ya que la venta de los componentes se requiere una actualización constante del stock, las necesidades del cliente, debe saber actuar de manera rápida ante los cambios que presenta el mercado. 
La estructura descentralizada garantiza que la experiencia del usuario sea fluida y eficaz que el inventario también se mantenga al día es decir en tiempo real. 

2. Modelo de roles 
<img width="457" height="497" alt="image" src="https://github.com/user-attachments/assets/46c7c507-5fec-4d5e-a5dc-8236231ecbd8" />


3. Matriz Raci 
<img width="524" height="245" alt="image" src="https://github.com/user-attachments/assets/af68fd66-92ba-409a-a943-bac80519114d" />


4. Diccionario de datos


cliente

<img width="840" height="155" alt="image" src="https://github.com/user-attachments/assets/aee8975d-a1b5-40de-bce2-1f8636ac8ed3" />


Empleado

<img width="851" height="163" alt="image" src="https://github.com/user-attachments/assets/e20365b8-6a0f-413e-a578-039b35763366" />


productos

<img width="904" height="169" alt="productos" src="https://github.com/user-attachments/assets/82a0e753-8138-429e-bba6-419bab857173" />


compra

<img width="861" height="167" alt="image" src="https://github.com/user-attachments/assets/cf46b6bb-654c-4be1-bdac-2afd9bcddfbe" />


Pago

<img width="881" height="173" alt="image" src="https://github.com/user-attachments/assets/13912e5a-2ea8-4ed4-8a7a-7c280ca9c193" />


Despacho
<img width="947" height="209" alt="image" src="https://github.com/user-attachments/assets/4f342900-d2c9-4b4d-b34b-ea2d8868bddb" />



2. El Prototipo Funcional (Lógica del Sistema)
<img width="536" height="515" alt="image" src="https://github.com/user-attachments/assets/b1907678-d083-4ec1-bf84-2a80cd5b6b27" />



Arquitectura
El sistema maneja una arquitectura organizada que permite capturar, validar, almacenar y procesar información relacionada con clientes, productos, compras y pagos.
Los datos ingresados por los usuarios pasan por procesos de validación antes de almacenarse en la base de datos, permitiendo posteriormente generar información útil para el seguimiento de pedidos y el control administrativo.



<img width="316" height="527" alt="image" src="https://github.com/user-attachments/assets/03f4f0bb-d781-4202-9c61-5ea68c4d0352" />


<img width="231" height="451" alt="image" src="https://github.com/user-attachments/assets/ce8de326-2e71-4084-adfa-75125a52ef1a" />


<img width="267" height="492" alt="image" src="https://github.com/user-attachments/assets/51e0b3c2-529c-459e-9014-43e7b7307d19" />


<img width="265" height="430" alt="image" src="https://github.com/user-attachments/assets/585abacf-7cea-4343-a3b5-6d46fac6fcb8" />


Tipo de SI
El proyecto combina características de TPS, MIS y DSS dentro de la pirámide de Sistemas de Información
Se clasifica como TPS (Transaction Processing System) porque registra operaciones diarias relacionadas con clientes, compras, pagos y productos.
También incorpora funciones MIS (Management Information System), ya que organiza la información y genera reportes administrativos para el seguimiento de pedidos y control de procesos.
Finalmente, presenta características DSS (Decision Support System) debido a que permite realizar análisis inteligentes relacionados con ventas, inventario y rendimiento operativo, apoyando la toma de decisiones dentro de la organización.


