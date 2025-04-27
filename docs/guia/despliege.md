# Guía de Despliegue de Entornos en Windows

Esta guía describe cómo ejecutar el programa Entornos en un sistema operativo Windows después de su instalación.

## Ejecución Básica

La forma más común de ejecutar Entornos en Windows es la siguiente:

1.  **Abre el Explorador de Archivos.**

2.  **Navega hasta la carpeta de instalación de Entornos.** La ubicación predeterminada suele ser una de las siguientes, dependiendo de si instalaste una versión de 32 o 64 bits:
    * `C:\Program Files\Entornos`
    * `C:\Archivos de programa (x86)\Entornos`

    Si elegiste una ubicación diferente durante la instalación, navega hasta esa carpeta.

3.  **Busca el archivo ejecutable de Entornos.** Este archivo probablemente tendrá la extensión `.exe` y un nombre similar al del programa (por ejemplo, `Entornos.exe`).

4.  **Haz doble clic en el archivo ejecutable (`.exe`) de Entornos.** Esto iniciará el programa.

## Ejecución desde la Línea de Comandos (Opcional)

Si prefieres ejecutar Entornos desde la línea de comandos (Símbolo del sistema o PowerShell):

1.  **Abre el Símbolo del sistema:** Presiona la tecla de Windows, escribe `cmd` y selecciona "Símbolo del sistema". O abre PowerShell buscando "PowerShell" en el menú de inicio.

2.  **Navega hasta la carpeta de instalación de Entornos** utilizando el comando `cd`. Por ejemplo:
    ```bash
    cd C:\Program Files\Entornos
    ```
    o
    ```bash
    cd "C:\Archivos de programa (x86)\Entornos"
    ```
    (Nota las comillas si la ruta contiene espacios).

3.  **Ejecuta el programa.** Escribe el nombre del ejecutable (sin la extensión `.exe` a veces es suficiente) y presiona Enter:
    ```bash
    Entornos
    ```
    o
    ```bash
    Entornos.exe
    ```

    Si Entornos acepta argumentos de línea de comandos, puedes añadirlos después del nombre del ejecutable. Consulta la documentación específica del programa para conocer las opciones disponibles.

## Notas Adicionales

* Es posible que se cree un acceso directo a Entornos en tu escritorio o en el menú de inicio durante la instalación. Puedes usar esos accesos directos para iniciar el programa más fácilmente.
* Consulta la documentación completa de Entornos para opciones de configuración o despliegue más avanzadas específicas de Windows.

Asegúrate de reemplazar los nombres de carpeta y el nombre del ejecutable (`Entornos.exe` es un ejemplo) con los nombres reales utilizados por tu programa "Entornos".