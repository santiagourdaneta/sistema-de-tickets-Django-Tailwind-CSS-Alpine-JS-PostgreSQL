# sistema-de-tickets-Django-Tailwind-CSS-Alpine-JS-PostgreSQL
Un moderno sistema de tickets de soporte, diseñado para gestionar consultas de clientes, tareas internas y solicitudes de soporte con seguimiento de estado y permisos basados ​​en roles.

## 🚀 Características

- 🧑‍💼 Acceso basado en roles (Administrador, Agente de Soporte, Cliente)
- 📝 Crear, asignar y dar seguimiento a tickets
- 📁 Categorías, prioridades y etiquetas de estado
- 🔎 Filtrar y buscar por estado, categoría y prioridad
- 📊 Panel de control con estadísticas y registros de actividad

## 🛠️ Pila tecnológica

- **Backend**: Django
- **Base de datos**: PostgreSQL
- **Frontend**: Tailwind CSS + Alpine.js
- **Autenticación**: Autenticación integrada de Django + roles personalizados

## 💻 Instrucciones de configuración

# Clonar el repositorio
git clone https://github.com/santiagourdaneta/sistema-de-tickets-Django-Tailwind-CSS-Alpine-JS-PostgreSQL/
cd sistema-de-tickets-Django-Tailwind-CSS-Alpine-JS-PostgreSQL

# Crear entorno virtual
python -m venv venv
source venv/bin/activate # En Windows, usar `venv\Scripts\activate`

# Instalar dependencias
pip install -r requirements.txt

# Aplicar migraciones
python manage.py migration

# Crear superusuario
python manage.py createsuperuser

# Ejecutar el servidor de desarrollo
python manage.py runserver
