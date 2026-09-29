## **1\. Alcance**

Esta política aplica a los datos utilizados por el sistema de estacionamiento inteligente para detectar espacios libres y ocupados dentro de la universidad.

| Identificador | Dato | Categoría |
| ----- | ----- | ----- |
| D1 | Estado del espacio (libre u ocupado) | Dato operativo |
| D2 | Identificador del espacio de estacionamiento | Dato operativo |
| D3 | Fecha y hora de detección | Dato de registro |
| D4 | Imagen capturada por la cámara (si aplica) | Dato técnico |
| D5 | Historial de ocupación de espacios | Dato de análisis |

---

## **2\. Ciclo de vida**

El tratamiento de los datos sigue el diagrama de ciclo de vida elaborado para el proyecto.

| Etapa | Descripción | Responsable |
| ----- | ----- | ----- |
| Captura | Las cámaras o sensores detectan si un espacio está libre u ocupado. | Sistema de monitoreo del estacionamiento |
| Almacenamiento | La información de ocupación se guarda en una base de datos. | Administrador de base de datos |
| Uso | La aplicación muestra en tiempo real los espacios disponibles. | Usuarios de la aplicación |
| Compartición | La información se comparte entre la aplicación, el servidor y los paneles informativos. | Administrador del sistema |
| Retención | Los registros históricos se conservan para análisis y mejora del servicio. | Líder del proyecto |
| Eliminación | Los registros que ya no son necesarios se eliminan del sistema. | Administrador del sistema |

---

## **3\. Normativa aplicable**

### **LFPDPPP (México)**

Aplica porque el sistema puede manejar información obtenida mediante cámaras y registros electrónicos. Exige transparencia, proporcionalidad, seguridad y protección de los datos tratados.

### **Ley de IA de la Unión Europea (UE AI Act)**

Sirve como referencia para implementar transparencia, documentación de riesgos y supervisión humana en sistemas que utilizan inteligencia artificial.

### **NIST AI Risk Management Framework (AI RMF)**

Aplica como guía de buenas prácticas para identificar, medir y gestionar riesgos asociados al uso de inteligencia artificial durante todo el ciclo de vida del sistema.

---

## **4\. Controles comprometidos**

| Acción | Responsable |
| ----- | ----- |
| Informar a los usuarios que el sistema utiliza inteligencia artificial. | Administrador del sistema |
| Publicar y mantener actualizado el aviso de privacidad. | Líder del proyecto |
| Recolectar únicamente los datos necesarios para detectar espacios disponibles. | Administrador de base de datos |
| Documentar y actualizar los riesgos identificados en el sistema. | Líder del proyecto |
| Mantener supervisión humana sobre los resultados generados por la IA. | Administrador del sistema |
| Definir y aplicar un periodo de conservación de registros. | Líder del proyecto |
| Eliminar de forma segura los datos que ya no sean necesarios. | Administrador del sistema |
| Verificar periódicamente la precisión del modelo de detección. | Sistema de monitoreo y líder del proyecto |
| Proteger el acceso a la información mediante credenciales y permisos. | Administrador del sistema |
| Utilizar conexiones seguras (HTTPS) para la transmisión de datos. | Administrador del sistema |

---

## **5\. Manejo de datos con herramientas de IA**

Para el uso de herramientas como ChatGPT, Gemini, DeepSeek, Dify u otras similares, se establecen las siguientes reglas:

### **Datos que sí pueden ingresarse**

* Datos ficticios utilizados para pruebas.  
* Estadísticas generales de ocupación.  
* Datos anonimizados que no permitan identificar personas.  
* Ejemplos simulados para entrenamiento o documentación.

### **Datos que no pueden ingresarse**

* Fotografías que permitan identificar personas.  
* Matrículas de vehículos.  
* Credenciales institucionales.  
* Datos personales de estudiantes, docentes o empleados.  
* Información sensible obtenida por las cámaras.

### **Condiciones de uso**

* Los datos deberán anonimizarse antes de ser utilizados en herramientas de IA.  
* Se dará preferencia al uso de datos ficticios para pruebas y desarrollo.  
* No se compartirán datos reales con servicios externos sin autorización institucional.  
* Se revisará que la información enviada no permita identificar directa o indirectamente a una persona.

---

## **6\. Revisión**

Esta política será revisada **cada seis meses** o cuando exista un cambio importante en el funcionamiento del sistema, en la normativa aplicable o en los datos tratados.

La aprobación y actualización de esta política será responsabilidad del **Líder del Proyecto**, con apoyo del **Administrador del Sistema** y del **Administrador de Base de Datos**.

