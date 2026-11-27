# INSTALACIÓN DE ODOO EN LINUX Y WINDOWS

## Instalaciçon en w10/w11

- Nombre equipo: SERVER-SGEA-\[HOST-CLASE\]
- Descargar e instalar odoo (cod. fuente) [web odoo](https://www.odoo.com/documentation/18.0/es_419/administration/on_premise/source.html)
  - Descargar repositorios
  - Instalar Python y pip 
  - Instalar PotgreSql
  - Instalar PgAdmin
  - Instalar dependencias
  - Ejecutar Odoo
- Crear la empresa RODRIGUEZ-\[HOST-CLASE\]
  - Correo de administrador: victor@rodriguex-\[HOST-CLASE\].com
- Configurar foto y nombre del usuario admin, configurar zona horaria, idioma y firma de correo electrónico. Activar el modo administrador
- Instalar un módulo diferente a ventas/sales. Localizar desde PgAdmin alguna de las clases generadas tras la instalación de este módulo.
- Localiza en la base de datos cómo y dónde se almacena la contraseña del usuario administrador que has creado (victor@rodriguez-\[HOST-CLASE\].com)
- Reinicia los servicios

## Instalación en Linux

- Nombre equipo: server-sgea-\[HOST-CLASE\]
- Mediante repositorios oficiales, instala la última versión de Odoo y sus dependencias, así como PgAdmin.
- Configura una conexión con el PgAdmin con el usuario odoo y contraseña odoo-\[HOST-CLASE\]
- Reinicia los servicios creados durante la instalación

## Instalación en AWS

- Crear la instancia EC2 con una imagen Ubuntu Server 22.04 LTS o posrterior, con RAM y disco suficientes
- Genera un par de claves SSH y asegura la conectividad de red desde el exterior
- Accede desde tu terminal Linux o WINDOWS.
- Instala odoo y sus dependencias del modo que tú prefieras
- Accede a odoo desde tu navegador
- Localiza el fichero de log de odoo
