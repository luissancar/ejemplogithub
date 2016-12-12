# Utilización GITHUB
Configuración:
git config --global user.name "luissancar"  
git config --global user.email "luissancar@yahoo.es"  
ssh-keygen  
copiar el contendido del fichero con la extensión .pub  
En la página de gibhub: settings/ssh  
- Crear una nueva clave ssh y copiar el contenido.    

git init  
git add fichero  
git status  
git remote add origin git@github.com:luissancar/ejemplogithub.git (dirección repositorio en ssh, clone with ssh(en la web de github))  
git pull --allow-unrelated-histories origin master  (baja archivos)
git push origin master   (sube archivos)
