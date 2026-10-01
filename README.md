# BibliotecaTec
# Objetivo
Aprender, crear e implementar una correcta estructuración de la manera en como se organizan y comentan los commits dentro de un repositorio de github.

# Estructura
El repositorio tendrá la siguiente estructura estándar para un proyecto de software:
- /docs: Contendrá la documentación del proyecto (manuales, requerimientos).
- /src: Contendrá el código fuente del sistema (ECS - Entidades de Configuración de Software).
- /pruebas: Contendrá las pruebas unitarias y de integración.
- /assets: Contendrá recursos gráficos, imágenes o archivos estáticos.

# Regla nombres
Subir los archivos con la siguiente nomenclatura: 
-los archivos deben iniciar con la fecha de subida siguiendo el formato ISO 8601: AAAA_MM_DD.
-Deben usar guiones bajos(_) en lugar de espacios en blanco
-Se debe separar la fecha, el nombre y la version mediante un guion bajo, y no usar caracteres especiales(ejemplo de archivo:20260930_Codigo1_v2.1.py).

# Regla versiones
Utilizaremos la regla de version incremental simple con decimal. Es un metodo sencillo para llevar el control de los cambios realizados en el proyecto. Utiliza un numero principal y, cuando es necesario, un numero decimal para identificar modificaciones menores. 
 Formato
 vN.n
El primer numero indica una versión principal del proyecto.
El numero decimal indica cambios, mejoras o correcciones menosres realizadas sobre esa version

por ejemplo
v1.0 = Primera version del proyecto
v1.1 = Se realizaron pequeños cambios
v1.2 = Se agregaron nuevas mejoras
v2.0 = Se Realizo un cambio immportante 
v2.1 = Se realizaron ajustes menores sobre la version 2

# Regla commits
Reglas para mensajes de commit

1. Usar un verbo en modo imperativo**
Los mensajes deben comenzar con un verbo en modo imperativo, como `Agregar`, `Cambiar`, `Corregir` ​​o `Eliminar`, para describir de forma clara la acción realizada.

2. No utilizar punto final ni puntos suspensivos**
Los mensajes de commit deben finalizar directamente con el contenido descriptivo, sin utilizar punto final (`.`) ni puntos suspensivos (`...`).

3. Limitar el mensaje a un máximo de 50 caracteres**
El mensaje principal del commit debe ser breve y no superar los 50 caracteres, facilitando su lectura y visualización en herramientas de control de versiones.

4. Agregar el contexto necesario en el cuerpo del commit**
Cuando el cambio requiera una explicación adicional, se debe utilizar el cuerpo del commit para proporcionar el contexto necesario, incluyendo detalles relevantes sobre el cambio realizado.


