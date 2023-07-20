los pasos que debes realizar para subir un proyecto a Git.
1.Inicializar un repositorio local con el comando git init
2.Agregar el o los archivos al repositorio con el comando git add .
3.Realizar un commit con el comando git commit -m "comentario"
4.Crear un repositorio remoto en GitHub (debes tener cuenta en GitHub)
5.Copias dentro del GitHub tienes dos opciones y escoges cual pegas en Visual:
        opcion 1: 
        echo "# repo2" >> README.md
        git add README.md
        git init
        git commit -m "first commit"
        git branch -M main
        git remote add origin https://github.com/JanetRW/repositorioReto2.git
        git push -u origin main

        opcion2: si has seguido los pasos anteriores 1,2,3
	git remote add origin https://github.com/JanetRW/repositorioReto2.git
        git branch -M main
        git push -u origin main

El comando git remote add origin https://github.com/JanetRW/repositorioReto2.git ;conectamos el repositorio local con el repositorio remoto. El comando git push sube los cambios de tu repositorio local al repositorio remoto. Y con estos pasos ya esta subido el proyecto a Git.