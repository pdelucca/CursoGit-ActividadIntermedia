 ![Clonado de Repositorio](imagenesActividadIntermedia/ipapcabecera.png)

# 1er Repositorio Curso Git - [pdelucca](https://github.com/pdelucca)

## _Actividad Intermedia_

Repositorio de demostración de conocimientos adquiridos hasta la clase 2. Se describen las tareas realizadas mediante captura de pantallas y texto que muestra el paso a paso de los objetivos planteados en actividad intermedia.

## Objetivos

- [Creación del Repositorio en una herramienta en la nube](#creaci%C3%B3n-del-repositorio-en-una-herramienta-en-la-nube)
- [Clonación local desde consola en VS Code](#clonaci%C3%B3n-local-desde-consola-en-vs-code)
- Creación de directorio de imagenes registrando con capturas el paso a paso de las tareas
- [Generación del Primer Commit con el estado hasta el momento](#generaci%C3%B3n-del-primer-commit-con-el-estado-hasta-el-momento)
- [Creación de directorio de documentación de modulos hasta la clase 2 y otras modificaciones](#creaci%C3%B3n-de-directorio-de-documentaci%C3%B3n-de-modulos-hasta-la-clase-2-y-otras-modificaciones)
- Creación del segundo Commit con el estado hasta el momento
- Agregar documento Cuestionario.md del cuestionario planteado en la actividad junto con sus respuestas


## Creación del Repositorio en una herramienta en la nube

Se crea el repositorio CursoGit-ActividadIntemedia mediante la interfaz gráfica de Github:

![Creación del Repositorio](imagenesActividadIntermedia/1-crearepo.png)

## Clonación local desde consola en VS Code
Dentro de la consola de vs code se ejecuta el comando
```sh
git clone https://github.com/pdelucca/CursoGit-ActividadIntermedia.git
```

![Clonado de Repositorio](imagenesActividadIntermedia/2-clonadorepositorio.png)

## Generación del Primer Commit con el estado hasta el momento
   - Se ejectua git status para ver el estado actual de los archvios del proyecto
   - Luego de agregar los archivos al stage con el comando:
   
      ```sh
      git add .
      ```
   - Finalmente generar la versión con commit en el repositorio local:
     
   -  ```sh
      git commit -m "Primer commit del proyecto"
      ```

      Los resultados del add y del commit se detallan en la siguiente captura:


      ![Clonado de Repositorio](imagenesActividadIntermedia/3-addcommit.png)

  ## Creación de directorio de documentación de modulos hasta la clase 2 y otras modificaciones

  Se crea la carpeta Documentación módulos con archivos hasta la clase 2 y tambien se copia al directorio raiz el archivo de actividad intermedia.
  También se agrega el logo del ipap al archivo readme.md
