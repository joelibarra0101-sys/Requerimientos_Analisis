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





Gestión de actores del servicio

RFN01: El sistema debe permitir el registro de empresas dentro del servicio de alimentación.

RFN02: El sistema debe permitir el registro de restaurantes afiliados al servicio.

RFN03: El sistema debe permitir el registro de empleados beneficiarios por empresa.

RFN04: El sistema debe permitir la actualización y consulta de la información de empresas, restaurantes y empleados.

🔷 Gestión de convenios

RFN05: El sistema debe permitir la creación de convenios entre empresas y restaurantes.

RFN06: El sistema debe permitir definir las condiciones del convenio, incluyendo modalidad de pago (prepago, postpago o mixto).

RFN07: El sistema debe permitir establecer restricciones, beneficios o límites de consumo dentro del convenio.

RFN08: El sistema debe validar la vigencia del convenio antes de autorizar cualquier consumo.

🔷 Identificación de empleados

RFN09: El sistema debe generar un código QR único para cada empleado registrado.

RFN10: El sistema debe permitir la identificación del empleado mediante el código QR.

RFN11: El sistema debe validar la autenticidad del código QR antes de permitir el acceso al servicio.

🔷 Gestión del consumo

RFN12: El sistema debe permitir al empleado acceder al servicio de alimentación en restaurantes afiliados.

RFN13: El sistema debe permitir al restaurante registrar la solicitud de consumo del empleado.

RFN14: El sistema debe validar si el empleado está autorizado para consumir.

RFN15: El sistema debe verificar la existencia de un convenio vigente entre la empresa y el restaurante.

RFN16: El sistema debe calcular el valor del consumo de acuerdo con las condiciones del convenio.

RFN17: El sistema debe registrar el consumo realizado por el empleado.

RFN18: El sistema debe evitar el registro duplicado de consumos para un mismo evento.

🔷 Control y seguimiento

RFN19: El sistema debe permitir la consulta de los consumos realizados por parte de los actores autorizados.

RFN20: El sistema debe generar reportes de consumo por empresa, restaurante y empleado.

RFN21: El sistema debe consolidar la información necesaria para la gestión de pagos y facturación.

