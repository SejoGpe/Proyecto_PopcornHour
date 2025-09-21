Incluye instrucciones concretas — copia/pega esto en tu README.md.

# PopcornHour

Portal para recomendar, calificar y discutir sobre películas y series. Usuarios: `moderador` y `estándar`.

## Requisitos
- Python 3.10+
- virtualenv (recomendado)
- Dependencias en `requirements.txt`

## Instalación (local)
1. Clona el repositorio:


git clone https://github.com/tu-usuario/popcornhour.git

cd popcornhour

2. Crear virtualenv e instalar dependencias:


python -m venv venv
source venv/bin/activate # Linux/macOS
venv\Scripts\activate # Windows
pip install -r requirements.txt

3. Crear archivo `.env` con variables (ejemplo):


FLASK_APP=run.py
FLASK_ENV=development
DATABASE_URL=sqlite:///app.db
SECRET_KEY=tu_clave_secreta

4. Inicializar base de datos:


flask db init
flask db migrate -m "Initial"
flask db upgrade

5. Ejecutar:


flask run

Visita `http://127.0.0.1:5000/`.

## Estructura del proyecto
(Agregar la estructura de carpetas que aparece en el repo)

## Entregables
Colocar todos los PDFs, capturas y videos en la carpeta `Entregables/`.

