# Proyeco final
ProyectoFinal-Gaggero CoderHouse 2025
comision: 78110
profesor: Alan Prestia
tutora: Gabriela Edith Rossi
alumno: Dante Gaggero

link al video: https://youtu.be/VL210GSGfdw

✅ Instrucciones para correr el proyecto Django

1. Clonar el repositorio:
git clone https://github.com/tu_usuario/ProyectoFinal-Gaggero.git
cd ProyectoFinal-Gaggero

2. Crear el entorno virtual:
En Windows:
python -m venv venv
venv\Scripts\activate
En macOS/Linux:
python3 -m venv venv
source venv/bin/activate

3. Instalar dependencias:
pip install -r requirements.txt
pip freeze > requirements.txt

4. Aplicar migraciones:
python manage.py makemigrations
python manage.py migrate

5. Cargar datos iniciales (películas, directores, géneros):
python manage.py shell 
Una vez adentro, ejecutar:
exec(open("datos.py", encoding="utf8").read())
exit()

6. Correr el proyecto:
python manage.py runserver



✨ FUNCIONALIDADES GENERALES

1. 🏠 Inicio

Accedé a la página de bienvenida.

2. 🎥 Ver Películas

Visualizá un listado de películas conocidas con información básica.

Se incluyen título, año, director y género.

3. 👨‍🎨 Directores

Agregá directores nuevos y visualizá los existentes.

4.  Géneros

Visualizá todos los géneros de películas disponibles.

🔑 AUTENTICACIÓN DE USUARIOS

5. 🔐 Iniciar sesión

Ingresá con tu nombre de usuario y contraseña.

6. 🔓 Registrarse

Creá una cuenta completando usuario, email y contraseña.

7. 👤 Perfil

Visualizá tus datos personales, tu avatar y tu información biográfica.

Desde aquí podés acceder a:

✏️ Editar perfil

🔑 Cambiar contraseña

📝 RESEÑAS

8. 🎓 Crear reseña (requiere sesión iniciada)

Subí tu opinión sobre una película junto a una imagen opcional.

9. 🔍 Ver reseñas

Explorar todas las reseñas creadas por vos y otros usuarios.

Incluye buscador por título de película.

10. ✏️ Editar reseña (solo autor)

Si sos el autor, podés modificar el contenido y la imagen.

11. ❌ Eliminar reseña (solo autor)

Si sos el autor, podés borrar tu reseña.

👩‍🎓 OTRAS PÁGINAS

12. 📄 Acerca de mí

Conocé al desarrollador de esta página.

Se incluye una foto e información personal.

📅 PERSISTENCIA DE DATOS

Toda la información (películas, usuarios, reseñas, etc.) queda guardada en la base de datos.

Incluso si se detiene y vuelve a iniciar el servidor, los datos no se pierden.





