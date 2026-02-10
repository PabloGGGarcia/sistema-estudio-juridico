# Sistema de Gestión de Estudio Jurídico ⚖️

Este proyecto fue desarrollado como parte de la cursada de **Estructura y Base de Datos** en la **UTN - INSPT**. El objetivo principal fue diseñar e implementar desde cero una base de datos relacional capaz de gestionar las operaciones diarias de un estudio de abogados.

## 👥 Integrantes - Grupo 7

* Tamara Torres, Yaritza Noemi
* Corvalán Portillo, Carla Sofia
* García, Pablo Gustavo

## 🚀 Descripción del Proyecto

El proyecto nace de la identificación de necesidades específicas en un entorno legal, tales como el seguimiento de expedientes, la gestión de audiencias, el control de honorarios y la organización de la relación entre abogados y clientes.

### Fases del Desarrollo:

1. **Análisis de Requerimientos:** Definición de las necesidades del estudio jurídico.
2. **Diseño Conceptual:** Creación del modelo Entidad-Relación (DER).
3. **Diseño Lógico:** Pasaje del modelo conceptual al modelo relacional (DMR).
4. **Implementación (DML/DDL):** Creación de tablas, restricciones de integridad y carga de datos ficticios (generados mediante IA para pruebas de volumen).
5. **Validación:** Ejecución de consultas complejas, implementación de Triggers para automatización y configuración de seguridad mediante usuarios y roles.

## 🛠️ Tecnologías Utilizadas

* **Motor de Base de Datos:** MySQL / MariaDB.
* **Lenguaje:** SQL.
* **Documentación:** Microsoft Word / PDF.

## 📊 Estructura de la Base de Datos

El sistema incluye, entre otras, las siguientes entidades principales:

* **Abogados:** Gestión de matrículas y especialidades.
* **Clientes:** Registro completo de datos de contacto.
* **Casos/Expedientes:** Seguimiento del estado de los juicios.
* **Audiencias:** Cronograma de citas y observaciones.
* **Honorarios:** Control de pagos y facturación.

## 🔐 Funcionalidades Destacadas

* **Triggers de Integridad:** Automatización para validar formatos de email y fechas de carga de documentos.
* **Consultas de Seguimiento:** Reportes de casos abiertos por abogado y clientes con pagos pendientes.
* **Seguridad:** Implementación de roles (`rol_editor`, `rol_consulta`) y perfiles de usuario específicos (Administrador, Abogado, Secretaria, Cadete) para limitar el acceso según la jerarquía.

## 📂 Contenido del Repositorio

* `/estudio_juridico_tablas_carga.sql`: Script de creación de base de datos, tablas e inserción de datos.
* `/estudio_juridico_consultas_triggers_sguridad.sql`: Lógica avanzada, automatización y seguridad.
* `/Informe_Estudio_Juridico.pdf`: Documentación detallada del proceso de diseño y conclusiones.

---

**Institución:** Universidad Tecnológica Nacional (UTN)

**Ciclo Lectivo:** 2025

**Comisión:** 2603

---
