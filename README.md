# Fase4-Resultados
# Proyecto: Registro de Proveedores y Marcas – FaboToys

## 📌 Resumen Ejecutivo

El presente proyecto consiste en el desarrollo de una aplicación sencilla destinada a mejorar el control y organización de proveedores y marcas dentro de la empresa FaboToys.  

Durante el proceso se identificó que la empresa no cuenta con una herramienta centralizada y accesible que permita registrar y consultar información básica de sus proveedores y las marcas que manejan. Esto genera problemas como duplicidad de datos, falta de precisión en compras y poca visibilidad sobre qué productos entran a la empresa.

A pesar de no dominar completamente conceptos avanzados de programación, GitHub o arquitectura de software, se logró implementar la funcionalidad principal: una interfaz sencilla que permite ingresar proveedores y marcas, visualizarlos y mantener un registro organizado.

Como siguiente fase, el objetivo es agregar la función para exportar esta libreta digital a un archivo de Excel, facilitando aún más la administración de datos.

---

## 🛑 Problema Identificado

- La empresa no cuenta con un registro claro, estructurado o centralizado de proveedores y marcas.
- La información se administra de manera manual o dispersa, lo que provoca:
  - Ineficiencia en compras.
  - Falta de control sobre entradas.
  - Dificultad para analizar tendencias.
  - Posibles errores al registrar proveedores nuevos.

---

## ✔️ Solución Propuesta

Se creó una aplicación básica que permite:

- Registrar proveedores.
- Registrar las marcas asociadas a cada proveedor.
- Visualizar los registros en pantalla.
- Mantener un pequeño sistema tipo “libreta digital”.

Esta herramienta permitirá comenzar a construir un sistema de control interno y sentar las bases para futuras funciones, como exportación a Excel y manejo de reportes.

---

## 🏗️ Arquitectura del Proyecto

La arquitectura es simple y está diseñada pensando en facilidad de uso y aprendizaje:

### **1. Lenguaje y herramientas**
- Python
- Tkinter (interfaz gráfica)
- VS Code

### **2. Componentes del sistema**
- **Interfaz gráfica (Tkinter):**  
✅ 2. Requerimientos del Proyecto
a. Servidores de aplicación, web o bases de datos

Dado que el proyecto es una aplicación local y sencilla, no requiere servidores externos ni bases de datos avanzadas.
Por ahora, todo se ejecuta en el equipo local del usuario.

Infraestructura mínima requerida:

Equipo local con Windows, macOS o Linux.

No se requiere servidor web.

No se requiere servidor de aplicaciones.

No se requiere base de datos externa.

La aplicación funciona enteramente en la memoria del sistema mientras está activa.

Nota: En futuras versiones (GA), se podría agregar:

Base de datos SQLite o MySQL.

API para consultas externas.

Exportación automática a servicios en la nube.

b. Paquetes adicionales necesarios

Para su ejecución solo se requieren los siguientes componentes:

Paquetes obligatorios:

Tkinter (viene integrado con Python en la mayoría de instalaciones).

No requiere instalaciones adicionales para la versión actual.

Paquetes opcionales (para futuras mejoras):
Versión del lenguaje y herramientas
Lenguaje principal utilizado:

Python 3.10+
(Funciona también en versiones 3.8 o superiores)

IDE / Entorno de desarrollo:

Visual Studio Code

Extensión recomendada: Python by Microsoft

Librerías incluidas:

Tkinter (GUI)

Listas nativas de Python para manejo de datos
| Componente               | Requerido   | Especificación               |
| ------------------------ | ----------- | ---------------------------- |
| Servidor Web             | ❌ No        | App local                    |
| Servidor de Aplicaciones | ❌ No        | Ejecución directa            |
| Base de Datos            | ❌ No        | Datos almacenados en memoria |
| Lenguaje                 | ✔ Sí        | Python 3.10+                 |
| Librerías                | ✔ Sí        | Tkinter                      |
| Paquetes adicionales     | Opcional    | pandas y openpyxl (futuro)   |
| IDE                      | Recomendado | VS Code                      |
| Sistema Operativo        | ✔           | Windows / macOS / Linux      |
