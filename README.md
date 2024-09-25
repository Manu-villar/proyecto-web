# proyecto-web
# Manuel crea repositorio
git clone git@github.com:Manu-villar/proyecto-web.git
Manuel hace archivo index.html con estructura básica 
git add .
git clone git@github.com:Manu-villar/proyecto-web.git
git push origin master
------------------------------------------------------------
# Manuel crea rama header
git branch header
git checkout header
git push origin header
------------------------------------------------------------
# Manuel  crea header en el index.html
git add .
git commit -m "creacion de header"
git push origin header
------------------------------------------------------------
# Manuel crea css 
git add . 
git commit -m "creacion de archivo css y estilos al header"
git push origin header
-------------------------------------------------------------
# Manuel lleva codigo de la rama header a la master
git checkout master
git pull origin header
git push origin master
-------------------------------------------------------------
# Manuel lleva los cambios de la rama master a header y pone comentarios en el codígo generado por Israel
git checkout header
git pull origin master
git add .
git commit -m "cambios hechos en el header"
git push origin header
------------------------------------------------------------
# Manuel resuelve conflictos cuando subimos código a la rama master
git checkout master
git pull origin header
git pull origin master
# resuelvo conflictos
git push origin master
--------------------------------------------------------------

#Israel clona el repositorio 
git clone git@github.com:Manu-villar/proyecto-web.git

#Israel trae los cambios en el repositorio master que ha hecho Manuel 
git pull origin master

#Israel crea la rama footer
git branch footer
git checkout footer
git push origin footer

#Israel crea el footer 
git add .
git commit -m "Creación de la sección footer"
git push origin footer

#Israel crea un archivo css y vincula HTML con CSS
git add . 
git commit -m "Creación de archivo css y enlace de html con css"
git push origin footer

#Israel lleva el codigo de la rama footer a la rama master
git checkout master
git pull origin footer
git pull origin master

#Se generan conflictos, ISrael lo resuelve 
git commit -m "Conflicto resuelto"
git push origin master

#Israel lleva los cambios de la rama master a la rama footer
git checkout footer
git pull origin master

#Israel pone un comentario en el header, la parte de manuel
git add .
git commit -m "Comentario en el header" 
git push origin footer

#Israel lleva los cambios de la rama footer a master
git checkout master
git pull origin footer
git push origin master


