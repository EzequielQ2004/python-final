Hoy vamos a hacer actividad en Python en un día como programadores:

1. Abrir la terminal de Git Bash o terminal en Linux, debe ser como administrador en Window

2. Creamos una carpeta o directorio: 

mkdir python-final

3. Entramos en ella: 

cd python-final

4. Iniciamos el repositorio:

git init

5. Creamos un archivo:

touch finales.py

6. Abrimos VSC:

code .

7. En terminal ingresamos el comando para saber la versión de Python que tenemos instalada:

python -V

python3 -V

8. Creamos el entorno virtual en Python:

python3 -m venv venv #Creamos el entorno virtual

9. Activamos el entorno virtual:

source venv/bin/activate #Activamos el entorno virtual en Linux

venv/scripts/activate #En windows

10. Hacemos actualización del pip de Python

python3 -m pip install --upgrade pip #Actualizamos el pip

11. Investigar ¿Qué es el pip y porque lo actualizamos?

12. Hacer al primer commit de este trabajo y unirlo al repositorio remoto.

13. Enviar el enlace del repositorio remoto donde tiene que tener un README.md con todos los detalles de lo que les fui mostrando en comandos, y las respuesta del punto 11 de más arriba.

## Respuesta al punto 11:
## ¿Qué es pip y por qué lo actualizamos?

Pip es el acrónimo de Python Package Installer (Instalador de paquetes de Python). Es una herramienta fundamental para trabajar con Python, ya que te permite:

* Instalar bibliotecas y paquetes externos: Pip te facilita la búsqueda e instalación de las bibliotecas que necesitas para tus proyectos de Python. Puedes encontrar una gran variedad de paquetes en el Índice de paquetes de Python (PyPI), un repositorio online que alberga miles de bibliotecas creadas por la comunidad Python.
* Administrar las dependencias: Pip se encarga de gestionar las dependencias de tus proyectos, es decir, las bibliotecas que necesitan otras bibliotecas para funcionar correctamente. Pip se asegura de que todas las dependencias estén instaladas en la versión adecuada y evita conflictos entre ellas.
* Actualizar paquetes: Pip te permite mantener tus paquetes actualizados a la última versión. Las actualizaciones de paquetes pueden incluir nuevas funcionalidades, correcciones de errores y mejoras de seguridad.
* Desinstalar paquetes: Si ya no necesitas un paquete, puedes desinstalarlo fácilmente con pip.

En resumen, pip es una herramienta esencial para cualquier desarrollador de Python que te permite trabajar de forma eficiente y segura con bibliotecas y paquetes externos.

## ¿Por qué actualizar pip?

Existen varias razones por las que es importante actualizar pip:

* Seguridad: Las actualizaciones de pip suelen incluir correcciones de seguridad que protegen tu sistema de vulnerabilidades conocidas.
* Compatibilidad: Las nuevas versiones de Python pueden requerir versiones más nuevas de pip para funcionar correctamente.
* Nuevas funcionalidades: Las actualizaciones de pip pueden incluir nuevas funcionalidades que te facilitan el trabajo con paquetes y dependencias.
* Corrección de errores: Las actualizaciones de pip suelen corregir errores que pueden causar problemas al instalar, usar o desinstalar paquetes.

En general, se recomienda actualizar pip regularmente para asegurarte de que estás utilizando la versión más reciente y segura.

## Cómo actualizar pip

Actualizar pip es un proceso sencillo que se puede realizar desde la terminal. Los comandos para actualizar pip varían según el sistema operativo que estés utilizando:

En Windows:

```
python -m pip install --upgrade pip
```

En macOS:

```
python3 -m pip install --upgrade pip
```

En Linux:

El comando para actualizar pip puede variar según la distribución de Linux que estés utilizando. Puedes consultar la documentación de tu distribución para obtener instrucciones específicas.

En general, se recomienda actualizar pip cada vez que instalas una nueva versión de Python o cuando tengas problemas al instalar o usar paquetes.

Espero que esta información te haya sido útil. Si tienes alguna otra pregunta, no dudes en contactarme.