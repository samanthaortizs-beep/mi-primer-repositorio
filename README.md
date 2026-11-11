# Configurar ususario
git config --global user.name "samanathaortizs-beep" 
git config --global user.email "samanthaortizs@ciencias.unam.mx"

# Clonar un repositorio
git clone https://github.com/raqcoss/Prueba1.git

# Mover a la carpeta del repositorio
cd Prueba1

# Crear un nuevo archivo
echo "Nuevo archivo" > ejemplo.txt

# Añadir cambios
git add ejemplo.txt

# Registrar cambios
git commit -m "Mi primer commit"

# Publicar cambios
git push

# Actualizar directorio local con directorio en linea.
git pull
