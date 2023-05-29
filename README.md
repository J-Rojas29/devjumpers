#                                          commit inicial

# 1. abrimos el git bash dentro de la carpeta en la cual queremos clonar nuestro repositorio.

# 2. Usamos "git clone" + el enlace del repositorio para clonar el repositorio de GitHub a nuestro equipo.

![](https://github.com/J-Rojas29/devjumpers/blob/main/Pantallazos/git%20clone.png)

# 3. Ahora, usamos el comando "cd" para entrar al repositorio que acabamos de clonar.

![](https://github.com/J-Rojas29/devjumpers/blob/main/Pantallazos/cd%20devjumpers.png)

# 4. Creamos el README con el comando "touch" (este comando sirve para crear un archivo vacío).

![](https://github.com/J-Rojas29/devjumpers/blob/main/Pantallazos/touch.png)

# 5. Creamos la carpeta "Pantallazos" con el comando "mkdir" (Comando que sirve para crear carpetas) en la cual agregaremos los pantallazos que usaremos en el README.

![](https://github.com/J-Rojas29/devjumpers/blob/main/Pantallazos/mkdir.png)

# 6. Usamos el comando "git add ." para preparar todos los cambios que hicimos en nuestro repositorio local.

![](https://github.com/J-Rojas29/devjumpers/blob/main/Pantallazos/git%20add.png)

# 7. Con el comando "git commit -m" hacemos el commit para dejar actualizados los cambios hechos con un comentario que da una breve descripción de lo que hemos hecho.

![](https://github.com/J-Rojas29/devjumpers/blob/main/Pantallazos/git%20commit.png)

# 8. Por último, usamos el comando "git push" para subir los cambios realizados a la nube de GitHub.

![](https://github.com/J-Rojas29/devjumpers/blob/main/Pantallazos/git%20push.png)

-----------------------------------------------------------------------------------------------------

#                                          gitignore

# Para ignorar archivos se usa el ".gitignore". Este es un archivo de tipo texto en el cual agregaremos los ficheros o carpetas que queremos que sean ignorados.

# 1. Para esto, primero debemos tener los archivos y/o carpetas que queremos ignorar. En este caso los crearemos usando el comando "touch" y "mkdir" para crear un fichero y una carpeta.

![](https://github.com/J-Rojas29/devjumpers/blob/main/Pantallazos/privado%20txt.png)
![](https://github.com/J-Rojas29/devjumpers/blob/main/Pantallazos/privada.png)

# 2. Ya que tenemos el archivo y la carpeta, usamos un "echo -e" (la extensión "-e" se usa para que el comando echo pueda reconocer caracteres de secuencia) para crear y asignarle los archivos y carpetas que queremos ignorar al ".gitignore" de la siguiente manera:

![](https://github.com/J-Rojas29/devjumpers/blob/main/Pantallazos/gitignore.png)

# 3. Subimos los cambios realizados con "git add ." "git commit -m" y "git push".

-----------------------------------------------------------------------------------------------------

#                                          Merge Directo 

# 1. Creamos el archivo "1.txt" usando "touch" y lo agregamos con "git add ." y luego "git commit -m" para confirmar los cambios.

# 2. Creamos la rama usando "git branch".

![](https://github.com/J-Rojas29/devjumpers/blob/main/Pantallazos/git%20branch.png)

# 3. cambiamos a la nueva rama usando "git checkout" + el nombre de la rama creada para desplazarnos a ella. Luego con "touch" creamos el archivo "2.txt" y usamos "git add ." y "git commit -m" (esto se debe hacer estando dentro de la rama porque ahi es donde lo queremos agregar).

![](https://github.com/J-Rojas29/devjumpers/blob/main/Pantallazos/git%20checkout.png)

# 4. Para subir la rama al repositorio remoto, usamos el comando "git branch" con las opciones "--set-upstream origin" + el nombre de la rama que queremos subir. Esto lo que hace es seleccionar nuestro repositorio remoto de origen y subira la rama que le indiquemos; por otro lado, si queremos subir todas las ramas podemos usar el comando "git push --all"

![](https://github.com/J-Rojas29/devjumpers/blob/main/Pantallazos/git%20push%20branch.png)

# 5. Ahora, para fusionar la rama que creamos con nuestro main, lo que debemos hacer es un "git checkout main" y por consiguiente un "git merge" + el nombre de la rama que queremos fusionar.

![]()

-----------------------------------------------------------------------------------------------------

#                                          Merge con Conflicto

# Nos posicionamos en la rama main y usando un "echo" le escribimos hola al archivo "1.txt" y hacemos commit.

![]()

# Cambiamos a la rama v0.2 y con un "echo" le escribimos adiós al archivo "1.txt" y hacemos commit.

# 