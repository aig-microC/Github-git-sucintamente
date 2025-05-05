
Ediciones: 20250505/20250430

**GitHub y git, sucintamente** tiene la intención de ser un tutorial *mínimo* para saber cómo crear una cuenta en Github y como manejar un proyecto con git.

En esta versión se incluyen los ficheros fuentes para generar esta documentación con *rst2html* y *rst2pdf*. Puedes descargarte directamente el fichero *pdf* como documento completo. Si te quieres bajar solamente el *html* deberás bajarte el subdirectorio *imágenes* también.

Para clonar el repositorio (hacer una copia local en tu PC) necesitas tener instalado git. Para ello, si no lo tienes instalado puedes hacerlo con:

*sudo apt install git*

y para clonar el reprositorio

*git clone https://github.com/aig-microC/Github-git-sucintamente*

Para construir el documento en *html* el comando es *rst2html -l es Tuto_github.rst > Tuto_github.html*

Para construir el documento en *pdf* el comando es *rst2pdf  -l es -b 1 Tuto_github.rst -o Tuto_github.pdf  -s estilo-001.yaml --repeat-table-rows*

Si hay alguna actualización en el repositorio de *github* (puedes verlo en la fechas de *Ediciones* que aparece al principio de este README.md) puedes actualizar tu repositorio local con el comando:

*git pull*   


**Nota**: Si deseas que en el *html* no aparezca al principio *###Title### - Sección: ###Section###* y al final *###Page###* debes eliminar, o comentar, las líneas:
```
.. header:: ###Title### - Sección: ###Section###
.. footer:: ###Page###
```
que aparecen al principio del documento *Tuto_github.rst*.
