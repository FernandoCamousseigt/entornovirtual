#1ero: verificar instalación de python y pip:
#python --version
#pip --version

#2do: 2do: instalar virtualenvwrapper-win (para quienes usan windows):
pip install virtualenvwrapper-win

(caso linux: sudo pip install virtualenvwrapper )

#3ro (opcional): verificar instalación de virtualenvwrapper-win:    
virtualenvwrapper-win --version

#4TO:crear entorno:  mkvirtualenv nombre-del-entorno-virtual (se recomienda sin guion ni tildes)

5to: pip install django
#para una version especifica con ==. ej: pip install django==3.2.4

#5.5 conocer version: python -m django version
#o python -m django-admin version

#6to si se quiere crear un requirements.txt:
pip freeze > requirements.txt -> para generar un respaldo de los paquetes instalados creando un
archivo requirements.txt

#7mo. instalar las dependencias desde un requirements, donde se especifican las dependencias: 
#en la consola pip install -r requirements-(entornocorrespondiente).txt

#Listar todos los entornos creados con el comando: lsvirtualenv
#o también se puede usar el comando: workon  

#-------------------------------------------------------------------------------------------------------------------------------------------------------------
#workon: permite activar(o “entrar” en) un entorno virtual existente especificando su
nombre
#deactivate : permite desactivar(o “salir” de) el entorno virtual activado, volviendo a darle
preferencia a las dependencias instaladas en el sistema

#------------------------------------------------------------------------------------------------------------------------------------------------------------
 Los comandos más utilizados serán:
 
●  pip install -r requirements.txt -> para instalar las dependencias desde un archivo
● pip freeze > requirements.txt -> para generar un respaldo de los paquetes instalados creando un
archivo requirements.txt
● pip install astral==2.2 -> para instalar una versión específica de un paquete que necesitemos, en
este ejemplo astral 2.2
#rmvirtualenv mientorno:  para eliminar el ambiente mientorno
