# mercedev.es - Página web de Mercedes Domínguez: mercedev.es

## Descripción
Un portfolio interactivo y dinámico diseñado para mostrar mis habilidades como desarrolladora, incorporando animaciones, un diseño visualmente atractivo y funcionalidades avanzadas.

## Tecnologías

* **Frontend:** Astro, SASS (BEM), Vue.js, React, Svelte, Vanilla JS, Alpine.js
* **Backend:** Django, Python
* **Despliegue:** DigitalOcean

## Objetivo

Aumentar mis habilidades y conocimientos profundos del back y del frontend.

## Instalación y Ejecución Local

### Clonar el repositorio
### git clone <URL_DEL_REPOSITORIO>

### Navegar a la carpeta del proyecto

### Configurar entorno virtual de Python (en backend/)
python -m venv backend/venv
source backend/venv/bin/activate

### Instalar dependencias del backend
pip install -r backend/requirements.txt # (este archivo se creará más tarde)

### Instalar dependencias del frontend (dentro de src/)
cd src && npm install && cd ..

### Levantar el servidor de desarrollo de Django
cd backend && python manage.py runserver && cd ..

### Levantar el servidor de desarrollo de Astro
cd src && npm run dev && cd ..

## Próximos Pasos

- Configurar la estructura de directorios para SASS y BEM.
- Desarrollar el fondo interactivo.
- Implementar la mascota "Mercí".
- Configurar herramientas de calidad de código (linters, formatters).
