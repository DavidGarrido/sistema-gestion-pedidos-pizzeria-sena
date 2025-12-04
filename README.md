# 🍕 Sistema de Gestión de Pedidos para Pizzería Local

## 📋 Descripción del Proyecto

Sistema integral de gestión de pedidos diseñado para optimizar las operaciones de una pizzería local. El sistema permite la toma de pedidos multicanal, control automático de inventario, gestión de cocina, seguimiento de entregas y análisis de negocio.

**Proyecto Académico - Programa de Análisis y Desarrollo de Software**  
**Ficha:** 228118  
**Competencia:** 220501092 - Establecer requisitos de la solución de software  
**Instructor:** Nelson Londoño Vergara

## 🎯 Objetivos del Sistema

- ✅ Facilitar pedidos a través de múltiples canales (web, móvil, teléfono)
- ✅ Automatizar control de inventario de ingredientes
- ✅ Optimizar procesos de preparación en cocina
- ✅ Mejorar seguimiento y gestión de entregas
- ✅ Proporcionar información en tiempo real para toma de decisiones

## 📊 Estado del Proyecto

[![GitHub issues](https://img.shields.io/github/issues/[tu-usuario]/sistema-gestion-pedidos-pizzeria-sena)](https://github.com/[tu-usuario]/sistema-gestion-pedidos-pizzeria-sena/issues)
[![GitHub closed issues](https://img.shields.io/github/issues-closed/[tu-usuario]/sistema-gestion-pedidos-pizzeria-sena)](https://github.com/[tu-usuario]/sistema-gestion-pedidos-pizzeria-sena/issues)

## 🏗️ Arquitectura del Sistema

### Componentes Principales
- **Aplicación Web:** Frontend React para clientes y administración
- **Aplicación Móvil:** React Native (iOS/Android)
- **Panel de Cocina:** Interfaz especializada para chefs
- **API Backend:** Node.js/Express con PostgreSQL
- **Base de Datos:** PostgreSQL para almacenamiento de datos

### Módulos del Sistema
1. **🏪 Gestión de Pedidos** - Toma y procesamiento de pedidos
2. **👨‍🍳 Gestión de Cocina** - Panel de visualización y control
3. **📦 Gestión de Inventario** - Control automático de stock
4. **🚚 Gestión de Entregas** - Asignación y seguimiento GPS
5. **💳 Gestión de Pagos** - Múltiples métodos de pago
6. **📊 Reportes y Analytics** - Dashboard ejecutivo

## 👥 Usuarios del Sistema

| Usuario | Rol | Funciones Principales |
|---------|-----|----------------------|
| 👤 **Cliente** | Usuario final | Realizar pedidos, seguimiento, pagos |
| 📞 **Operador** | Recepción telefónica | Registrar pedidos, atención al cliente |
| 👨‍🍳 **Chef** | Cocina | Visualizar pedidos, actualizar estados |
| 🚚 **Repartidor** | Entregas | Ver rutas, confirmar entregas |
| 👔 **Gerente** | Administración | Inventario, reportes, configuración |
| 🏢 **Propietario** | Dirección | Dashboard ejecutivo, análisis |

## 📋 Gestión de Requisitos

Este repositorio utiliza **GitHub Issues** para la gestión completa de requisitos según el estándar IEEE 830.

### 🏷️ Etiquetas (Labels)

| Etiqueta | Color | Descripción |
|----------|-------|-------------|
| `bug` | 🔴 | Errores o problemas identificados |
| `enhancement` | 🔵 | Nuevas funcionalidades o mejoras |
| `high priority` | 🔴 | Requisitos críticos (prioridad alta) |
| `medium priority` | 🟡 | Requisitos importantes (prioridad media) |
| `user story` | 🟢 | Historias de usuario (HU) |
| `use case` | 🔵 | Casos de uso (CU) |
| `non-functional` | 🟠 | Requisitos no funcionales (RNF) |

### 🎯 Milestones

- **MVP** - Producto Mínimo Viable (Marzo 2026)
- **Fase 1** - Gestión de Pedidos (Abril 2026)
- **Fase 2** - Gestión de Cocina (Mayo 2026)
- **Fase 3** - Entregas y Pagos (Junio 2026)

## 📚 Documentación del Proyecto

### Documentos de Requisitos
- [📄 Especificación IEEE 830 - Historias de Usuario](GA1_AA4_EV02_IEEE830_Historias_Usuario.html)
- [🛠️ Herramienta de Gestión de Requisitos](GA1_AA5_EV01_Herramienta_Gestion_Requisitos.html)
- [📋 Formulario de Recolección de Información](GA1_AA3_EV03_Formulario_Recoleccion_con_Analisis.md)
- [🏗️ Mapa de Procesos Organizacionales](mapa_de_procesos_pizzeria.md)

### Análisis y Levantamiento
- [📊 Matriz de Trazabilidad](documento_identificacion_procesos_pizzeria.html)
- [🔍 Análisis de Procesos](mapa_pizzeria.html)
- [📈 Formulario de Recolección](GA1_AA3_EV03_Formulario_Recoleccion_Analisis.html)

## 🚀 Historias de Usuario Prioritarias

### 🔥 Alta Prioridad
- **HU-001:** Como cliente, quiero realizar pedidos online para recibir mi comida favorita
- **HU-003:** Como chef, quiero ver pedidos en panel de cocina para organizarme correctamente
- **HU-004:** Como gerente, quiero control automático de inventario para evitar faltantes
- **HU-006:** Como cliente, quiero seguimiento en tiempo real para saber cuándo llega mi pedido

### 🟡 Media Prioridad
- **HU-002:** Como cliente frecuente, quiero guardar pedidos favoritos
- **HU-007:** Como gerente, quiero asignar múltiples pedidos por ruta
- **HU-010:** Como propietario, quiero reportes de ventas en tiempo real

## 🛠️ Tecnologías Utilizadas

### Frontend
- React.js
- React Native
- HTML5/CSS3/JavaScript

### Backend
- Node.js
- Express.js
- PostgreSQL
- Redis (cache)

### DevOps & Tools
- Git/GitHub
- Docker
- GitHub Actions (CI/CD)
- Postman (API testing)

## 📈 Métricas de Rendimiento

| Requisito | Métrica | Valor Objetivo |
|-----------|---------|----------------|
| Tiempo de Respuesta | < 2 segundos | 95% de requests |
| Disponibilidad | 99% uptime | Mensual |
| Usuarios Concurrentes | 200 usuarios | Pico de demanda |
| Procesamiento de Pedidos | 300 pedidos/hora | Horario pico |

## 🔒 Requisitos No Funcionales

- **Seguridad:** Encriptación SSL/TLS, PCI-DSS compliance
- **Usabilidad:** Interfaz intuitiva, capacitación < 1 hora
- **Escalabilidad:** Soporte hasta 300% crecimiento
- **Mantenibilidad:** Cobertura documentación 80%

## 📞 Contacto

**Desarrollador:** Alexander Garrido Hernandez  
**Programa:** Análisis y Desarrollo de Software  
**Ficha:** 228118  
**Instructor:** Nelson Londoño Vergara

## 📝 Licencia

Este proyecto es de carácter académico y está destinado únicamente para fines educativos dentro del programa de formación del SENA.

---

⭐ **Proyecto desarrollado como evidencia de aprendizaje en el marco de la competencia 220501092 - Establecer requisitos de la solución de software**
