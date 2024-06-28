## CLASE 11 Actividad en Python
<sub>
1. Abrir la terminal de Git Bash o terminal en Linux, debe ser como administrador en Window</sub>
<sub>
2. Creamos una carpeta o directorio: </sub>

```sh
mkdir python-final
```
<sub>
3. Entramos en ella: </sub>

```sh
cd python-final
```
<sub>
4. Iniciamos el repositorio:</sub>

```sh
git init
```
<sub>
5. Creamos un archivo:</sub>

```sh
touch finales.py
```
<sub>
6. Abrimos VSC:</sub>

```sh
code .
```
<sub>
7. En terminal ingresamos el comando para saber la versión de Python que tenemos instalada:</sub>

```sh
python -V
python3 -V
```
<sub>
8. Creamos el entorno virtual en Python:</sub>

```sh
python3 -m venv venv #Creamos el entorno virtual
```
<sub>
9. Activamos el entorno virtual:</sub>

```sh
source venv/bin/activate #Activamos el entorno virtual en Linux
venv/scripts/activate #En windows
```
<sub>
10. Hacemos actualización del pip de Python</sub>

```sh
python3 -m pip install --upgrade pip #Actualizamos el pip
```
<sub>
¿Qué es pip?
pip es un administrador de paquetes para Python. Es la herramienta estándar para instalar, actualizar y eliminar paquetes Python de PyPI (Python Package Index), el repositorio oficial de paquetes para Python. Pip facilita la gestión de las dependencias de tu proyecto Python, lo que te permite concentrarte en el desarrollo de tu código sin preocuparte por la instalación manual de bibliotecas y módulos.
</sub>
<sub>
Características principales de pip:
</sub>
<sub>
Instalación de paquetes: Pip te permite instalar paquetes Python desde PyPI usando comandos simples. Puedes instalar un paquete específico por su nombre, o instalar los requisitos enumerados en un archivo requirements.txt.
Actualización de paquetes: Pip te permite actualizar paquetes Python a la última versión disponible en PyPI. Esto es importante para asegurarte de que estás utilizando las últimas correcciones de errores y mejoras de seguridad.
Desinstalación de paquetes: Pip te permite desinstalar paquetes Python que ya no necesitas. Esto puede ser útil para liberar espacio en disco o para evitar conflictos con otros paquetes.
Manejo de dependencias: Pip puede resolver automáticamente las dependencias de un paquete, lo que significa que instalará automáticamente todos los paquetes necesarios para que el paquete principal funcione correctamente.
Creación de paquetes: Pip te permite crear y distribuir tus propios paquetes Python. Puedes subir tus paquetes a PyPI para que otros usuarios puedan instalarlos.
</sub>
</sub>
¿Por qué actualizar pip?
Es importante actualizar pip por varias razones:

Seguridad: Las actualizaciones de pip a menudo incluyen correcciones de errores de seguridad que pueden proteger tu sistema de vulnerabilidades.
Nuevas funciones: Las actualizaciones de pip a menudo incluyen nuevas funciones que pueden hacer que la administración de paquetes sea más fácil y eficiente.
Compatibilidad: Las actualizaciones de pip pueden mejorar la compatibilidad con las nuevas versiones de Python y otros paquetes.
Corrección de errores: Las actualizaciones de pip pueden corregir errores que pueden estar causando problemas con la instalación o actualización de paquetes.
En general, se recomienda actualizar pip regularmente para asegurarse de que está utilizando la última versión y aprovechar las últimas funciones y mejoras de seguridad.

Cómo actualizar pip
Actualizar pip es un proceso sencillo. Puedes usar el siguiente comando:</sub>

```sh
python -m pip install --upgrade pip
```
<sub>
Este comando utilizará la versión actual de pip para descargar e instalar la última versión de sí mismo.

También puedes usar un administrador de paquetes de terceros para actualizar pip. Por ejemplo, en Windows, puedes usar Chocolatey:

choco install pip -f https://chocolatey.org/public/python
Este comando instalará Chocolatey si aún no está instalado, y luego lo usará para instalar o actualizar pip.

Conclusión
Pip es una herramienta esencial para cualquier desarrollador de Python. Al mantener pip actualizado, te aseguras de que estás utilizando la última versión y aprovechando las últimas funciones y mejoras de seguridad. La actualización de pip es un proceso sencillo que solo toma unos pocos minutos.</sub>
