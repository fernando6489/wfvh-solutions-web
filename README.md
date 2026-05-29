# wfvh-solutions-web

# 📑 Creación de página web – WFVH Solutions

## 1. Documento de Visión del Proyecto
**Información general**

| Campo     | Descripción |
|-----------|-------------|
| Proyecto  | Sistema Web para Gestión Documental |
| Cliente   | Consorcio MEB |
| Fecha     | 29/05/2026 |
| Versión   | 1.0 |
| Analista  | Equipo de Desarrollo – WFVH Solutions |

**Problemática identificada**  
Actualmente el consorcio gestiona sus documentos de manera manual y dispersa, lo que genera:  
- Dificultad para localizar archivos en tiempo real.  
- Riesgo de pérdida de información por falta de respaldo digital.  
- Procesos lentos en la aprobación de documentos.  
- Escasa trazabilidad de cambios y versiones.  
- Baja seguridad en el acceso a información sensible.  

👉 En resumen: **ineficiencia, falta de control y riesgo de pérdida de información crítica.**

**Objetivo del proyecto**  
Diseñar e implementar una plataforma web que permita a los usuarios almacenar, organizar, consultar y compartir documentos de manera segura y eficiente.  

**Alcance inicial**  
Incluye:  
- Registro e inicio de sesión de usuarios.  
- Carga y almacenamiento de documentos.  
- Búsqueda avanzada por metadatos.  
- Control de versiones.  
- Panel administrativo para gestión de permisos.  

No incluye:  
- Aplicación móvil.  
- Integración con sistemas externos (fase futura).  
- Automatización de flujos de aprobación complejos (fase futura).  

---

## 2. Identificación de Stakeholders

| Stakeholder       | Cargo              | Interés | Influencia |
|-------------------|--------------------|---------|------------|
| María López       | Gerente General    | Alto    | Alto       |
| Juan Pérez        | Jefe de Archivo    | Alto    | Medio      |
| Usuarios internos | Personal del consorcio | Alto | Medio      |
| Equipo técnico    | Desarrolladores WFVH Solutions | Alto | Medio |
| Administración    | Finanzas           | Medio   | Alto       |

---

## 3. Elicitación de Requisitos

**Entrevista a la Gerente**  
- Problema actual: dificultad para localizar documentos y riesgo de pérdida.  
- Deseo de mejora: acceso rápido y seguro desde cualquier lugar.  
- Funcionalidades indispensables: carga de documentos, búsqueda avanzada, control de versiones, permisos de acceso.  
- Reportes necesarios: documentos más consultados, historial de modificaciones, usuarios activos.  

**Encuesta a usuarios internos (20 participantes)**  
- Búsqueda avanzada (90%).  
- Control de versiones (80%).  
- Acceso remoto (75%).  
- Seguridad y permisos (70%).  

👉 Conclusión: la **búsqueda avanzada y el control de versiones** son las necesidades principales.  

**Observación directa**  
- Tiempo promedio para localizar un documento: 10 minutos.  
- Errores frecuentes en versiones duplicadas.  
- Congestión en solicitudes de documentos en horas pico.  

---

## 4. Catálogo de Requisitos

**Requisitos funcionales**  
- RF-001: El usuario podrá registrarse mediante correo electrónico.  
- RF-002: El usuario podrá iniciar sesión.  
- RF-003: El usuario podrá cargar documentos.  
- RF-004: El sistema permitirá búsqueda avanzada por metadatos.  
- RF-005: El sistema gestionará control de versiones.  
- RF-006: El administrador podrá asignar permisos de acceso.  
- RF-007: El sistema generará reportes de uso.  

**Requisitos no funcionales**  
- RNF-001: Tiempo de respuesta menor a 2 segundos.  
- RNF-002: Contraseñas cifradas.  
- RNF-003: Soporte para 500 usuarios concurrentes.  
- RNF-004: Disponibilidad del 99%.  
- RNF-005: Diseño adaptable a móviles.  

---

## 5. Casos de Uso
- CU-01: Cargar documento.  
- CU-02: Buscar documento.  
- CU-03: Consultar historial de versiones.  
- CU-04: Administrar permisos.  

---

## 6. Prototipos funcionales
Maquetación inicial en HTML/CSS con dashboard tipo cards: carga, búsqueda, reportes.  

---

## 7. Reglas de negocio
- RN-01: No se podrán cargar documentos mayores a 50 MB.  
- RN-02: Cada documento debe tener metadatos obligatorios (autor, fecha, categoría).  
- RN-03: Solo administradores podrán eliminar documentos.  

---

## 8. Priorización MoSCoW

| Requisito            | Prioridad   |
|-----------------------|-------------|
| Búsqueda avanzada     | Must Have   |
| Control de versiones  | Must Have   |
| Registro usuarios     | Must Have   |
| Reportes de uso       | Should Have |
| Comentarios en docs   | Could Have  |

---

## 9. Matriz de trazabilidad

| Requisito | Caso de uso | Prueba |
|-----------|-------------|--------|
| RF-003    | CU-Cargar   | TP-01  |
| RF-004    | CU-Buscar   | TP-02  |
| RF-005    | CU-Versiones| TP-03  |

---

## 10. Acta de Validación
**Fecha:** 29/05/2026  
**Participantes:**  
- María López (Gerente)  
- Juan Pérez (Jefe de Archivo)  
- Equipo técnico WFVH Solutions  

**Observaciones:**  
- Requisitos completos y aprobados.  
- Sin inconsistencias detectadas.  

**Firma de aprobación:**  
Gerente: ___________________  
Analista: ___________________  
