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

# Para ignorar archivos se usa el ".gitignore". Este es un archivo de tipo texto en el cual agregaremos los ficheros o carpetas que queremos que sean ignorados.

# 1. Para esto, primero debemos tener los archivos y/o carpetas que queremos ignorar. En este caso los crearemos usando el comando "touch" y "mkdir" para crear un fichero y una carpeta.

![](https://github.com/J-Rojas29/devjumpers/blob/main/Pantallazos/privado%20txt.png)
![](https://github.com/J-Rojas29/devjumpers/blob/main/Pantallazos/privada.png)

# 2. Ya que tenemos el archivo y la carpeta, usamos un "echo -e" (la extensión "-e" se usa para que el comando echo pueda reconocer caracteres de secuencia) para crear y asignarle los archivos y carpetas que queremos ignorar al ".gitignore" de la siguiente manera:

![](https://github.com/J-Rojas29/devjumpers/blob/main/Pantallazos/gitignore.png)

# 3. Subimos los cambios realizados con "git add ." "git commit -m" y "git push".