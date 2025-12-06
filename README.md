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
a. ¿Cómo instalar el ambiente de desarrollo?
1. Requisitos previos

Antes de iniciar, debes tener instalado:

Visual Studio Code (VS Code)

Java JDK 17 o superior

Git

Extensión de Java para VS Code (solo se instala desde la tienda de extensiones de VS Code)

2. Clonar el repositorio

En tu computadora:
git clone https://github.com/tu-usuario/tu-repositorio.git
cd tu-repositorio
3. Abrir el proyecto en VS Code

En VS Code:

Archivo → Abrir carpeta

Selecciona el repositorio clonado

VS Code detectará que es un proyecto Java y descargará automáticamente las dependencias necesarias.

4. Ejecutar el programa

En VS Code:

Abre el archivo Main.java

Haz clic en Run (botón ▶️)

La aplicación se abrirá en una ventana gráfica

b. ¿Cómo ejecutar pruebas manualmente?

Como la aplicación es sencilla (una interfaz gráfica que guarda proveedores y marcas), las pruebas también son manuales.

1. Prueba de registro

Abre la aplicación

Ingresa un proveedor y una marca

Haz clic en Agregar

Verifica que aparezcan en la lista

2. Prueba de vacíos

Intenta agregar un registro sin llenar los campos

La aplicación debe mostrar un mensaje de error o evitar la acción

3. Prueba de persistencia (si aplica)

Si tienes habilitado almacenamiento (archivo .txt o en memoria):

Cierra la aplicación

Vuelve a iniciarla

Verifica si los datos se mantienen

4. Prueba de interfaz

Confirma que los botones responden

Confirma que la aplicación no se cierra al interactuar

c. ¿Cómo implementar la solución en producción?

La aplicación puede instalarse de dos formas: localmente o en la nube con Heroku.
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

a. ¿Cómo instalar el ambiente de desarrollo?
1. Requisitos previos

Antes de iniciar, debes tener instalado:

Visual Studio Code (VS Code)

Java JDK 17 o superior

Git

Extensión de Java para VS Code (solo se instala desde la tienda de extensiones de VS Code)

2. Clonar el repositorio

En tu computadora:
git clone https://github.com/tu-usuario/tu-repositorio.git
cd tu-repositorio
3. Abrir el proyecto en VS Code

En VS Code:

Archivo → Abrir carpeta

Selecciona el repositorio clonado

VS Code detectará que es un proyecto Java y descargará automáticamente las dependencias necesarias.

4. Ejecutar el programa

En VS Code:

Abre el archivo Main.java

Haz clic en Run (botón ▶️)

La aplicación se abrirá en una ventana gráfica
b. ¿Cómo ejecutar pruebas manualmente?

Como la aplicación es sencilla (una interfaz gráfica que guarda proveedores y marcas), las pruebas también son manuales.

1. Prueba de registro

Abre la aplicación

Ingresa un proveedor y una marca

Haz clic en Agregar

Verifica que aparezcan en la lista

2. Prueba de vacíos

Intenta agregar un registro sin llenar los campos

La aplicación debe mostrar un mensaje de error o evitar la acción

3. Prueba de persistencia (si aplica)

Si tienes habilitado almacenamiento (archivo .txt o en memoria):

Cierra la aplicación

Vuelve a iniciarla

Verifica si los datos se mantienen

4. Prueba de interfaz

Confirma que los botones responden

Confirma que la aplicación no se cierra al interactuar

c. ¿Cómo implementar la solución en producción?

La aplicación puede instalarse de dos formas: localmente o en la nube con Heroku.

✔ Opción 1: Implementación en ambiente local (más simple)

Exporta el proyecto como archivo .jar desde VS Code:

Presiona Ctrl + Shift + P

Escribe Java: Export Jar

Selecciona el archivo Main.java

VS Code generará un archivo:
/dist/registro-proveedores.jar
Para ejecutar el programa en cualquier computadora:
java -jar registro-proveedores.jar
4. Configuración

Esta sección explica cómo se configura el producto y cómo se ajustan los requerimientos necesarios para que funcione correctamente.

a. Configuración del producto (archivos de configuración)

Actualmente, la aplicación es sencilla y no requiere archivos de configuración complejos. Sin embargo, el proyecto incluye una estructura mínima que permite organizar la información y preparar el sistema para futuras expansiones.

Archivos y carpetas relevantes:
/src
   Main.java              → Archivo principal donde se ejecuta la aplicación
   Controlador.java       → Maneja la lógica del programa
   Proveedor.java         → Clase modelo (proveedor y marcas)
resources/
   config.properties      → Archivo para configuraciones simples (opcional)
README.md                 → Documentación del proyecto

Archivo opcional: config.properties

Si deseas agregar configuraciones básicas, puede incluir:

modo=local
guardar_datos=false
ruta_exportacion=./export/


(Esto no es obligatorio, pero sirve para mejor presentación del proyecto.)

b. Configuración de los requerimientos

Para que el proyecto funcione correctamente, se deben configurar las siguientes herramientas:

1. Configuración del entorno Java

Instalar Java JDK 17 o superior

Agregar la variable de entorno JAVA_HOME (si es necesario)

Verificar la instalación con:

java -version

2. Configuración en Visual Studio Code

En VS Code:

Instalar las siguientes extensiones:

Extension Pack for Java

Debugger for Java

Java Test Runner (opcional)

Abrir el proyecto:

Archivo → Abrir carpeta → seleccionar repositorio

VS Code descargará y configurará automáticamente:

Dependencias del proyecto

Classpaths

Sistema de compilación interno

3. Configuración del control de versiones (GitHub)

Para trabajar correctamente con el repositorio:

Iniciar git:

git init


Configurar tu nombre de usuario:

git config --global user.name "TuNombre"


Configurar tu correo:

git config --global user.email "tuemail@example.com"


Subir cambios al repositorio:

git add .
git commit -m "Primer commit"
git push origin main

4. Configuración futura (si el proyecto crece)

Estas configuraciones no son necesarias ahora, pero puedes mencionarlas porque muestran visión de escalabilidad:

Activar base de datos SQLite

Configurar exportación a Excel

Integración con API web

Variables de entorno para producción (Heroku o Render)

Ejemplo de variables futuras:

DB_HOST=localhost
DB_USER=root
DB_PASS=1234
EXPORTAR_EXCEL=true
5. Uso

Esta sección describe cómo utilizar la aplicación tanto desde la perspectiva del usuario final como del usuario administrador.
El propósito es asegurar que cualquier persona que abra la herramienta sepa cómo operar el sistema sin necesidad de conocimientos técnicos avanzados.

a. Manual de referencia para usuario final

Esta parte explica el funcionamiento básico de la aplicación para los usuarios que solo necesitan registrar y consultar información.

📌 Objetivo del usuario final

Permitir registrar proveedores y sus marcas asociadas de forma sencilla, rápida y con una interfaz amigable.

📌 Cómo usar la aplicación (paso a paso)
1. Abrir la aplicación

La ventana principal mostrará:

Campos para escribir:

Nombre del proveedor

Marca relacionada

Botón Agregar

Botón Limpiar

Lista con todos los registros agregados

2. Registrar un proveedor

Escribe el nombre del proveedor en el campo correspondiente.

Escribe la marca asociada.

Haz clic en el botón Agregar.

El registro aparecerá automáticamente en la lista de la parte inferior.

3. Ver los registros agregados

Todos los proveedores registrados se visualizarán en una tabla o lista.

Ejemplo:

Proveedor       | Marca
--------------------------
Proveedor A     | Marca 1
Proveedor B     | Marca 2

4. Limpiar los campos

Si deseas borrar lo que escribiste antes de agregar:

Haz clic en Limpiar

Ambos campos volverán a quedar vacíos

5. Cerrar la aplicación

Cierra la ventana desde la X cuando hayas terminado.
(No se eliminan datos accidentalmente.)

b. Manual de referencia para usuario administrador

Esta sección describe las funciones que un administrador o encargado del sistema necesita conocer para mantener la aplicación.

📌 Objetivo del administrador

Supervisar el correcto funcionamiento de la aplicación, realizar configuraciones y preparar futuras mejoras.

📌 Responsabilidades del administrador
1. Instalación y actualización del sistema

El administrador debe:

Instalar la aplicación en las computadoras de trabajo

Verificar que se tenga Java, Git y VS Code configurados

Actualizar la aplicación cuando haya nuevas versiones

Descargar los cambios desde GitHub

Ejemplo:

git pull origin main

2. Mantenimiento de los archivos de configuración

El administrador puede modificar parámetros en:

/resources/config.properties


Ejemplos de configuraciones:

modo=local
exportar_excel=false
ruta_logs=/logs/

3. Respaldo de datos (si aplica)

Si la aplicación guarda datos en archivos locales, el administrador debe:

Hacer una copia del archivo antes de actualizaciones

Guardarlo en una carpeta segura

Asegurar que no se borren los registros por error

4. Soporte a usuarios

El administrador deberá:

Ayudar al usuario final si no puede abrir la aplicación

Solucionar errores básicos (ejemplo: Java no instalado)

Reportar fallas o sugerencias en GitHub

5. Implementación en ambientes adicionales

Si la empresa decide implementar:

Exportación a Excel

Base de datos

Sincronización en la nube

Versión en Heroku

El administrador será quien configure estos servicios.

📌 Diferencias entre usuario final y administrador
Actividad	Usuario Final	Administrador
Registrar proveedor	✔ Sí	✔ Sí
Consultar registros	✔ Sí	✔ Sí
Instalar aplicación	❌ No	✔ Sí
Modificar configuración	❌ No	✔ Sí
Actualizar el sistema	❌ No	✔ Sí
Respaldo de información	❌ No	✔ Sí
Resolver problemas técnicos	❌ No	✔ Sí
