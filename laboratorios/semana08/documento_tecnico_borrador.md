# Estacionamiento inteligente

## 1. Introducción

El proyecto **Estacionamiento inteligente** tiene como objetivo facilitar el acceso a información sobre la disponibilidad de espacios de estacionamiento dentro de la universidad. Busca evitar que la comunidad universitaria llegue y encuentre los estacionamientos llenos, permitiendo consultar previamente los espacios libres y ocupados antes de salir. Para ello, se propone utilizar inteligencia artificial generativa y agentes, apoyados en cámaras o sensores que permitan identificar el estado de los espacios. El sistema deberá funcionar de manera segura, eficiente y responsable, garantizando la protección de la privacidad y el manejo adecuado de los datos.

## 2. Alcance

**El proyecto incluye:**

- La identificación de espacios libres y ocupados mediante cámaras o sensores.
- La consulta de disponibilidad de estacionamiento por parte de la comunidad universitaria.
- La gestión de datos como identificadores de espacios, estados de ocupación, fechas, horas, imágenes y registros históricos.
- El almacenamiento, uso, retención y eliminación responsable de los datos.
- La aplicación de controles de seguridad, privacidad y supervisión de resultados de IA.

**El proyecto no incluye:**

- La recolección de datos personales o sensibles que no sean necesarios para su funcionamiento.
- El uso de fotografías identificables, matrículas o credenciales en herramientas de IA sin autorización institucional.
- La compartición de datos reales sin autorización institucional.
- La implementación de funciones adicionales no especificadas en el proyecto.

## 3. Requisitos funcionales

- **RF-1.** El sistema deberá identificar los espacios de estacionamiento libres y ocupados mediante cámaras o sensores.
- **RF-2.** El sistema deberá registrar el estado, identificador, fecha y hora de detección de cada espacio.
- **RF-3.** El sistema deberá permitir a la comunidad universitaria consultar la disponibilidad de estacionamiento antes de salir.
- **RF-4.** El sistema deberá almacenar registros históricos de ocupación para su consulta y análisis.
- **RF-5.** El sistema deberá gestionar el ciclo de vida de los datos, incluyendo su captura, almacenamiento, uso, compartición, retención y eliminación.

## 4. Requisitos no funcionales

- **RNF-1. Seguridad y privacidad:** El sistema deberá proteger los datos mediante controles de acceso, avisos de privacidad y eliminación de información innecesaria.
- **RNF-2. Precisión y transparencia:** El sistema deberá informar sobre el uso de IA, supervisar sus resultados y verificar la precisión de la identificación de espacios.
- **RNF-3. Cumplimiento y gestión de riesgos:** El sistema deberá considerar la LFPDPPP de México, la Ley de IA de la Unión Europea y el NIST AI Risk Management Framework como referencias para su operación responsable.
