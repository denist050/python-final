## CLASE 11 Actividad en Python

1. Abrir la terminal de Git Bash o terminal en Linux, debe ser como administrador en Windows.

2. Crear una carpeta o directorio:

    ```sh
    mkdir python-final
    ```

3. Entrar en ella:

    ```sh
    cd python-final
    ```

4. Iniciar el repositorio:

    ```sh
    git init
    ```

5. Crear un archivo:

    ```sh
    touch finales.py
    ```

6. Abrir VSC:

    ```sh
    code .
    ```

7. En terminal, ingresar el comando para saber la versión de Python que tenemos instalada:

    ```sh
    python -V
    python3 -V
    ```

8. Crear el entorno virtual en Python:

    ```sh
    python3 -m venv venv # Crear el entorno virtual
    ```

9. Activar el entorno virtual:

    ```sh
    source venv/bin/activate # Activar el entorno virtual en Linux
    venv/scripts/activate # En Windows
    ```

10. Hacer actualización del pip de Python:

    ```sh
    python3 -m pip install --upgrade pip # Actualizar el pip
    ```

### ¿Qué es pip?

pip es un administrador de paquetes para Python. Es la herramienta estándar para instalar, actualizar y eliminar paquetes Python de PyPI (Python Package Index), el repositorio oficial de paquetes para Python. Pip facilita la gestión de las dependencias de tu proyecto Python, lo que te permite concentrarte en el desarrollo de tu código sin preocuparte por la instalación manual de bibliotecas y módulos.

### Características principales de pip:

- **Instalación de paquetes**: Pip te permite instalar paquetes Python desde PyPI usando comandos simples. Puedes instalar un paquete específico por su nombre, o instalar los requisitos enumerados en un archivo `requirements.txt`.
- **Actualización de paquetes**: Pip te permite actualizar paquetes Python a la última versión disponible en PyPI. Esto es importante para asegurarte de que estás utilizando las últimas correcciones de errores y mejoras de seguridad.
- **Desinstalación de paquetes**: Pip te permite desinstalar paquetes Python que ya no necesitas. Esto puede ser útil para liberar espacio en disco o para evitar conflictos con otros paquetes.
- **Manejo de dependencias**: Pip puede resolver automáticamente las dependencias de un paquete, lo que significa que instalará automáticamente todos los paquetes necesarios para que el paquete principal funcione correctamente.
- **Creación de paquetes**: Pip te permite crear y distribuir tus propios paquetes Python. Puedes subir tus paquetes a PyPI para que otros usuarios puedan instalarlos.

### ¿Por qué actualizar pip?

Es importante actualizar pip por varias razones:

- **Seguridad**: Las actualizaciones de pip a menudo incluyen correcciones de errores de seguridad que pueden proteger tu sistema de vulnerabilidades.
- **Nuevas funciones**: Las actualizaciones de pip a menudo incluyen nuevas funciones que pueden hacer que la administración de paquetes sea más fácil y eficiente.
- **Compatibilidad**: Las actualizaciones de pip pueden mejorar la compatibilidad con las nuevas versiones de Python y otros paquetes.
- **Corrección de errores**: Las actualizaciones de pip pueden corregir errores que pueden estar causando problemas con la instalación o actualización de paquetes.

En general, se recomienda actualizar pip regularmente para asegurarse de que está utilizando la última versión y aprovechar las últimas funciones y mejoras de seguridad.

### Cómo actualizar pip

Actualizar pip es un proceso sencillo. Puedes usar el siguiente comando:

```sh
python -m pip install --upgrade pip