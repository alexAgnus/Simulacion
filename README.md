# Simulacion
Simulación de accidentes en bicicleta

===> para clonar el proyecto
git clone https://github.com/alexAgnus/Simulacion.git
===> corroborar que se descague todo el repo 2.4 y cacho gigas
===> si todo salio bien cambiamos de rama con
git checkout feature/movimiento  
===> despues se agregan los archivos que cambiaron y se hace commit con
git add .
git commit -m "mis cambios"
git push https://github.com/alexAgnus/Simulacion.git feature/movimiento


===>si ocurre algun error en la descarga o carga de archivos lfs del repo
git config http.sslVerify false
===> si fue error de descarga
git lfs pull https://github.com/alexAgnus/Simulacion.git
===> si fue error de carga
git lfs push https://github.com/alexAgnus/Simulacion.git feature/movimiento

git config http.sslVerify false
git lfs pull https://github.com/alexAgnus/Simulacion.git

/////////////////////////////////////////////////////////////////////cambiar de rama///////////////////////////////////////////
git add .
git commit -m "mensaje"
gir push origin feature/rama
git reset --hard
git clean -f
git checkout feaure/rama
git status
