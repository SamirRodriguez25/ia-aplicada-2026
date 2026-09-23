| Columna original   | Qué le hiciste | Técnica         | Por qué                                                                           |
| ------------------ | -------------- | --------------- | --------------------------------------------------------------------------------- |
| ID_persona         | Seudonimizar   | Seudonimización | Permite identificar registros sin revelar la identidad real.                      |
| Nombre             | Eliminar       | Supresión       | No era necesario para detectar anomalías.                                         |
| Correo electrónico | Enmascarar     | Enmascaramiento | Protege datos personales manteniendo algo de contexto.                            |
| Teléfono           | Eliminar       | Supresión       | No aporta valor al análisis de accesos.                                           |
| Fecha de acceso    | Conservar      | Conservación    | Necesaria para analizar patrones temporales.                                      |
| Hora de acceso     | Generalizar    | Generalización  | Se agrupó en madrugada, mañana, tarde y noche para reducir precisión innecesaria. |
| Área               | Conservar      | Conservación    | Es clave para detectar accesos inusuales.                                         |
| Empresa            | Conservar      | Conservación    | Ayuda a identificar inconsistencias y relaciones entre registros.                 |
| Motivo             | Conservar      | Conservación    | Permite validar si el acceso tiene sentido.                                       |
| Semana             | Generalizar    | Generalización  | Sustituye la fecha exacta por un período más amplio.                              |
| Fecha válida       | Conservar      | Conservación    | Sirve para detectar errores en los datos.                                         |
| Hora laboral       | Conservar      | Conservación    | Ayuda a identificar accesos fuera de horario.                                     |
