**CASOS DE USO**

🔹 Gestión de Usuarios

CU001\_RegistrarUsuario

CU002\_IniciarSesion

CU003\_RecuperarContrasena

🔹 Gestión de Empresas

CU004\_RegistrarEmpresa

CU005\_ConsultarEmpresa

CU006\_ActualizarEmpresa

🔹 Gestión de Empleados

CU007\_RegistrarEmpleado

CU008\_ActualizarEmpleado

CU009\_ConsultarEmpleado

🔹 Gestión de Restaurantes

CU010\_RegistrarRestaurante

CU011\_ActualizarRestaurante

CU012\_ConsultarRestaurante

🔹 Gestión de Convenios

CU013\_CrearAcuerdoEmpresaRestaurante

CU014\_ActualizarConvenio

CU015\_ConsultarConvenio

🔹 Gestión de QR

CU016\_GenerarCodigoQR

CU017\_ValidarCodigoQR

🔹 Consumo

CU018\_RegistrarConsumoQR

CU019\_ConsultarConsumos

🔹 Reportes y Facturación

CU020\_GenerarReportes

CU021\_ProcesarFacturacion



**REQUISITOS FUNCIONALES**



**<i>~~Requisitos Funcionales:~~</i>**



**Gestión de actores**

•	RFN01: El sistema debe permitir el registro de usuarios dentro de la plataforma.

•	RFN02: El sistema debe permitir la autenticación de usuarios para el acceso seguro al sistema.

•	RFN03: El sistema debe permitir la recuperación de acceso en caso de olvido de credenciales.

•	RFN04: El sistema debe permitir la gestión de roles y permisos de los usuarios.



**Gestión de empresas (multi-tenant)**

•	RFN05: El sistema debe permitir el registro de empresas dentro del servicio.

•	RFN06: El sistema debe permitir la gestión de la información de las empresas.

•	RFN07: El sistema debe garantizar el aislamiento de la información entre empresas.



**Gestión de empleados**

•	RFN08: El sistema debe permitir el registro de empleados asociados a una empresa.

•	RFN09: El sistema debe permitir la gestión de la información de los empleados.

•	RFN10: El sistema debe generar un código QR único para cada empleado.



**Gestión de restaurantes**

•	RFN11: El sistema debe permitir el registro de restaurantes afiliados.

•	RFN12: El sistema debe permitir la gestión de la información de los restaurantes.



**Gestión de convenios**

•	RFN13: El sistema debe permitir la creación de convenios entre empresas y restaurantes.

•	RFN14: El sistema debe validar la vigencia de los convenios antes de permitir el consumo.

•	RFN15: El sistema debe permitir la gestión de las condiciones de los convenios.



**Gestión de consumos**

•	RFN16: El sistema debe permitir registrar el consumo de alimentos por parte de los empleados.

•	RFN17: El sistema debe validar la autorización del consumo antes de su registro.

•	RFN18: El sistema debe permitir la consulta del historial de consumos.

•	RFN19: El sistema debe generar reportes de consumo.



**Reportes y facturación**

•	RFN20: El sistema debe generar reportes de facturación basados en los consumos registrados.



**Sistema de invitaciones**

•	RFN21: El sistema debe permitir el envío de invitaciones a usuarios.

•	RFN22: El sistema debe permitir la aceptación de invitaciones para el acceso al sistema.



**<i>~~REQUISITOS NO FUNCIONALES (RNF)~~</i>**



Los siguientes requisitos definen las condiciones de calidad bajo las cuales debe operar el sistema MESAPASS.



**Seguridad**

•	RNF01: El sistema debe garantizar la autenticación segura de los usuarios.

•	RNF02: El sistema debe proteger la información mediante mecanismos de control de acceso.

•	RNF03: El sistema debe asegurar la confidencialidad de los datos personales.

•	RNF04: El sistema debe prevenir accesos no autorizados a la información.



**Rendimiento**

•	RNF05: El sistema debe responder a las operaciones críticas en un tiempo menor a 2 segundos.

•	RNF06: El sistema debe soportar múltiples usuarios concurrentes sin degradación significativa del servicio.



**Disponibilidad**

•	RNF07: El sistema debe estar disponible durante los horarios operativos del servicio.

•	RNF08: El sistema debe minimizar tiempos de inactividad.



**Usabilidad**

•	RNF09: El sistema debe ser fácil de usar para todos los actores del servicio.

•	RNF10: El sistema debe permitir realizar las operaciones en el menor número de pasos posible.



**Integridad de datos**

•	RNF11: El sistema debe garantizar la consistencia de la información registrada.

•	RNF12: El sistema debe evitar la duplicidad de registros de consumo.



**Escalabilidad**

•	RNF13: El sistema debe permitir el crecimiento en número de empresas, empleados y restaurantes sin afectar su desempeño.

•	Trazabilidad

•	RNF14: El sistema debe registrar las operaciones realizadas para fines de auditoría y control.







