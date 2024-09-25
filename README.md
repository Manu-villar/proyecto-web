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
# Manuel lleva los cambios de la rama master a footer y pone comentarios en el codígo generado por Israel
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