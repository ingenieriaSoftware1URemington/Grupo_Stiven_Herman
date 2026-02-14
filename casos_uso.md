# Casos de uso 
## Brayan  Rodriguez, Colin Morales, Herman Ospina
###


Este repositorio contiene la documentación oficial para el desarrollo de la plataforma de pagos y conciliación bancaria de **FinPagTech**. El proyecto busca eliminar procesos manuales, asegurar la trazabilidad de la información y garantizar la estabilidad del sistema bajo alta demanda.

---

## 👥 Equipo de Desarrollo
* **Brayan Rodriguez**
* **Colin Moralez**
* **Herman Ospina**

---

## 📑 Historias de Usuario (HU)

### [HU: 01] Solución a Problemas Financieros
| Atributo | Detalle |
| :--- | :--- |
| **Módulo** | Desarrollo |
| **Rol** | Arquitecto de Software |
| **Prioridad** | Alta |
| **Riesgo** | Alta |
| **Desarrollador** | Brayan Rodriguez |

**Descripción:** Implementación de una plataforma de pagos para procesar operaciones en efectivo y electrónicas, eliminando hojas de cálculo. Incluye un módulo de conciliación bancaria detallado para alcanzar un 95% de éxito en el proceso.

**Actores:** Arquitecto de software, Contabilidad, Gerencia, Área operativa.  
> **Observaciones:** El sistema puede generar fallos en conciliaciones y registros por factores humanos o técnicos.

* **RF01 - Conciliación bancaria:** Este debe de solicitar que todo usuario se autentique para acceder al sistema .
* **NRF02  - Protocolo de protección de datos:** Este debe de solicitar que todo usuario se autentique para acceder al sistema.

---

### [HU: 02] Seguridad en la Red
| Atributo | Detalle |
| :--- | :--- |
| **Módulo** | Desarrollo |
| **Rol** | Arquitecto de Software |
| **Prioridad** | Alta |
| **Riesgo** | Alta |
| **Desarrollador** | Herman Ospina |

**Descripción:** Mejoras en cumplimiento normativo para asegurar el tratamiento legal de los datos, garantizando que la privacidad de los usuarios no se vea comprometida.

**Actores:** Coordinador de ciberseguridad, Gerencia.  
> **Observaciones:** Implementación de controles de acceso estrictos, segmentación de red y encriptación.

* **RF02 - Manejo de información:** Se requiere solicitar en la aplicación si es un repartidor o usuario en la aplicación
* **NRF03 - Documentación:** Aceptar los termino y condiciones que maneja la aplicación para dar acceso al usuario 
---

### [HU: 03] Estabilidad y Optimización del Sistema
| Atributo | Detalle |
| :--- | :--- |
| **Módulo** | Desarrollo |
| **Rol** | Arquitecto de Software |
| **Prioridad** | Alta |
| **Riesgo** | Alta |
| **Desarrollador** | Colin morales

**Descripción:** Implementación de infraestructura en la nube para soportar el aumento progresivo de usuarios, garantizando disponibilidad en horas pico y evitando caídas.

**Actores:** Gerencia, Equipo de sistemas, Arquitecto de software.  
> **Observaciones:** Requiere estrategias de escalabilidad para permitir el crecimiento del proyecto.

* **RF03 - Concurrencia de usuarios:** Soporte garantizado para al menos 1,000 usuarios simultáneos con crecimiento progresivo.
* **NRF03 - Estabilidad y rendimiento:** Respuesta óptima con un rendimiento del 99.1% asegurado.

---

## ✅ Control de Aprobación

| Rol | Nombre | Firma | Fecha |
| :--- | :--- | :--- | :--- |
| **Estudiante 1** | Brayan Rodriguez| ____________________ | 06/02/2026 |
| **Estudiante 2** | Herman Ospina | ____________________ | 06/02/2026 |
| **Estudiante 3** | Colin Morales | ____________________ | 06/02/2026 |

---

![diagrama](img/Diagrama%20(4).png)