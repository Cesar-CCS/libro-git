## Cesar Castro Salazar ##
## 18100157 ##
## Ejercicios basicos con git ##
### Ejercicio 1 ###
Configurar Git definiendo el nombre del usuario, el correo electrónico y activar el coloreado de la salida. Mostrar la configuración final.
git config –-global color.ui auto
> ![1](https://user-images.githubusercontent.com/78839789/190549823-bc5c576a-3bab-4354-944e-b40305a3b2fa.png)
### Ejercicio 2 ###
Crear un repositorio nuevo con el nombre libro y mostrar su contenido.
> ![2](https://user-images.githubusercontent.com/78839789/190550041-cbbdea7f-5a82-48e2-aa3d-3bff066a2961.png)
### Ejercicio 3 ###
1. Comprobar el estado del repositorio.
2. Crear un fichero indice.txt con el siguiente contenido:
<pre><code>Capítulo 1: Introducción a Git
Capítulo 2: Flujo de trabajo básico
Capítulo 3: Repositorios remotos</pre></code>
1. Comprobar de nuevo el estado del repositorio.
2. Añadir el fichero a la zona de intercambio temporal.
3. Volver a comprobar una vez más el estado del repositorio.
> ![3](https://user-images.githubusercontent.com/78839789/190550169-f253bd40-e282-4b04-9cd5-a059f0fbd40e.png)
### Ejercicio 4 ###
Realizar un commit de los últimos cambios con el mensaje “Añadido índice del libro.” y ver el estado del repositorio.
> ![4](https://user-images.githubusercontent.com/78839789/190550234-03458947-7e23-494c-b1f3-73b5fa6393c9.png)
### Ejercicio 5 ###
1. Cambiar el fichero indice.txt para que contenga lo siguiente:
<pre><code> Capítulo 1: Introducción a Git
Capítulo 2: Flujo de trabajo básico
Capítulo 3: Gestión de ramas
Capítulo 4: Repositorios remotos </pre></code>
2. Mostrar los cambios con respecto a la última versión guardada en el repositorio.
3. Hacer un commit de los cambios con el mensaje “Añadido capítulo 3 sobre gestión de ramas”.
> ![5](https://user-images.githubusercontent.com/78839789/190550322-f0be18b5-533d-44c4-ac9a-e2a9cae28467.png)
### Ejercicio 6 ###
1. Mostrar los cambios de la última versión del repositorio con respecto a la anterior.
2. Cambiar el mensaje del último commit por “Añadido capítulo 3 sobre gestión de ramas al índice.”
3. Volver a mostrar los últimos cambios del repositorio.
> ![6](https://user-images.githubusercontent.com/78839789/190550411-68d2acc1-d465-4a6e-ad24-e94b3b4f3447.png)
## Ejercicios de manejo del historial de cambios ##
### Ejercicio 1 ###
1. Mostrar el historial de cambios del repositorio.
2. Crear la carpeta capitulos y crear dentro de ella el fichero capitulo1.txt con el siguiente texto.
<pre><code>Git es un sistema de control de versiones ideado por Linus Torvalds.</pre></code>
3. Añadir los cambios a la zona de intercambio temporal.
4. Hacer un commit de los cambios con el mensaje “Añadido capítulo 1.”
5. Volver a mostrar el historial de cambios del repositorio.
> ![1](https://user-images.githubusercontent.com/78839789/190558259-37a807aa-79f2-4c1f-b5a1-3814f13db694.png)
### Ejercicio 2 ###
1. Crear el fichero capitulo2.txt en la carpeta capitulos con el siguiente texto.
<pre><code>El flujo de trabajo básico con Git consiste en: 1- Hacer cambios en 
el repositorio. 2- Añadir los cambios a la zona de intercambio temporal. 
3- Hacer un commit de los cambios. </pre></code>
2. Añadir los cambios a la zona de intercambio temporal.
3. Hacer un commit de los cambios con el mensaje “Añadido capítulo 2.”
4. Mostrar las diferencias entre la última versión y dos versiones anteriores.
> ![2](https://user-images.githubusercontent.com/78839789/190558394-5a5006c9-acbf-48dd-a06f-d7fb62d980de.png)
### Ejercicio 3 ###
1. Crear el fichero capitulo3.txt en la carpeta capitulos con el siguiente texto.
<pre><code>Git permite la creación de ramas lo que permite tener distintas versiones 
del mismo proyecto y trabajar de manera simultanea en ellas.</pre></code>
2. Añadir los cambios a la zona de intercambio temporal.
3. Hacer un commit de los cambios con el mensaje “Añadido capítulo 3.”
4. Mostrar las diferencias entre la primera y la última versión del repositorio.
> ![3](https://user-images.githubusercontent.com/78839789/190558486-6fb90c22-ff80-4867-b34c-8e14ed0c003a.png)
### Ejercicio 4 ###
1. Añadir al final del fichero indice.txt la siguiente línea:
<pre><code>Capítulo 5: Conceptos avanzados</pre></code>
2. Añadir los cambios a la zona de intercambio temporal.
3. Hacer un commit de los cambios con el mensaje “Añadido capítulo 5 al índice.”.
4. Mostrar quién ha hecho cambios sobre el fichero indice.txt.
> ![4](https://user-images.githubusercontent.com/78839789/190558555-f01e8d09-dafd-4555-8dca-a50124bc8944.png)

## Ejercicios de deshacer cambios ##
### Ejercicio 1 ###
1. Eliminar la última línea del fichero indice.txt y guardarlo.
2. Comprobar el estado del repositorio.
3. Deshacer los cambios realizados en el fichero indice.txt para volver a la versión anterior del fichero.
4. Volver a comprobar el estado del repositorio.
> ![1](https://user-images.githubusercontent.com/78839789/190561084-31b15c54-17ac-4d9e-845b-b184edd2fa92.png)
### Ejercicio 2 ###
1. Eliminar la última línea del fichero indice.txt y guardarlo.
2. Añadir los cambios a la zona de intercambio temporal.
3. Comprobar de nuevo el estado del repositorio.
4. Quitar los cambios de la zona de intercambio temporal, pero mantenerlos en el directorio de trabajo.
5. Comprobar de nuevo el estado del repositorio.
6. Deshacer los cambios realizados en el fichero indice.txt para volver a la versión anterior del fichero.
7. Volver a comprobar el estado del repositorio.
> ![2](https://user-images.githubusercontent.com/78839789/190561144-58e62b98-ce02-45c4-9c03-17fff8d1bbd8.png)
### Ejercicio 3 ###
1. Eliminar la última línea del fichero indice.txt y guardarlo.
2. Eliminar el fichero capitulos/capitulo3.txt.
3. Añadir un fichero nuevo captitulos/capitulo4.txt vacío.
4. Añadir los cambios a la zona de intercambio temporal.
5. Comprobar de nuevo el estado del repositorio.
6. Quitar los cambios de la zona de intercambio temporal, pero mantenerlos en el directorio de trabajo.
7. Comprobar de nuevo el estado del repositorio.
8. Deshacer los cambios realizados para volver a la versión del repositorio.
9. Volver a comprobar el estado del repositorio.
>![3](https://user-images.githubusercontent.com/78839789/190561215-f027a5fa-9662-424c-abfd-d543d4de62ae.png)
### Ejercicio 4 ###
1. Eliminar la última línea del fichero indice.txt y guardarlo.
2. Eliminar el fichero capitulos/capitulo3.txt.
3. Añadir los cambios a la zona de intercambio temporal y hacer un commit con el mensaje “Borrado accidental.”
4. Comprobar el historial del repositorio.
5. Deshacer el último commit pero mantener los cambios anteriores en el directorio de trabajo y la zona de intercambio temporal.
6. Comprobar el historial y el estado del repositorio.
7. Volver a hacer el commit con el mismo mensaje de antes.
8. Deshacer el último commit y los cambios anteriores del directorio de trabajo volviendo a la versión anterior del repositorio.
9. Comprobar de nuevo el historial y el estado del repositorio.
>![4](https://user-images.githubusercontent.com/78839789/190561273-63282fc7-a6d2-40fd-bc16-d710886f077a.png)