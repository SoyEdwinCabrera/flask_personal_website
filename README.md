# Flask Personal Website

Este proyecto es una aplicación web simple desarrollada con Flask. La aplicación incluye dos páginas principales: una página de inicio y una página "Acerca de". El diseño es minimalista y utiliza HTML, CSS y Flask para la estructura y funcionalidad.

## Estructura del Proyecto

El proyecto está organizado de la siguiente manera:

```
flask_personal_website/
├── Demo/
│   ├── static/
│   │   └── css/
│   │       └── main.css
│   ├── templates/
│   │   ├── about.html
│   │   ├── home.html
│   │   └── layout.html
│   ├── script1.py
│   └── README.md
```

### Archivos principales:

1. **`script1.py`**: Archivo principal que contiene la lógica de la aplicación Flask.
2. **`templates/`**: Carpeta que contiene las plantillas HTML para las páginas de la aplicación.
   - `layout.html`: Plantilla base que incluye el diseño común para todas las páginas.
   - `home.html`: Página de inicio.
   - `about.html`: Página "Acerca de".
3. **`static/css/main.css`**: Archivo CSS para el diseño y estilo de la aplicación.

---

## Cómo se desarrolló el proyecto

### 1. Configuración del entorno
1. Se instaló Python y Flask.
2. Se creó un entorno virtual para gestionar las dependencias del proyecto:
   ```bash
   python -m venv venv
   source venv/bin/activate  # En Linux/Mac
   venv\Scripts\activate     # En Windows
   ```
3. Se instaló Flask:
   ```bash
   pip install flask
   ```

### 2. Creación de la estructura del proyecto
Se organizó el proyecto en carpetas para separar los archivos estáticos, las plantillas y el código Python.

### 3. Desarrollo de la aplicación Flask
1. Se creó el archivo `script1.py` con las rutas principales (`/` para la página de inicio y `/about/` para la página "Acerca de").
2. Se configuró el servidor Flask para ejecutarse en modo de depuración.

### 4. Diseño de las plantillas HTML
1. Se creó una plantilla base `layout.html` que incluye el encabezado, el menú de navegación y un bloque de contenido dinámico.
2. Se extendió la plantilla base para las páginas `home.html` y `about.html`.

### 5. Estilización con CSS
1. Se diseñó un archivo CSS (`main.css`) para dar estilo a las páginas.
2. Se incluyeron estilos para el encabezado, el cuerpo y los elementos de navegación.

---

## Cómo ejecutar el proyecto

1. Clona este repositorio:
   ```bash
   git clone https://github.com/SoyEdwinCabrera/flask_personal_website.git
   cd flask_personal_website/Demo
   ```

2. Activa el entorno virtual:
   ```bash
   source venv/bin/activate  # En Linux/Mac
   venv\Scripts\activate     # En Windows
   ```

3. Instala Flask si no está instalado:
   ```bash
   pip install flask
   ```

4. Ejecuta la aplicación:
   ```bash
   python script1.py
   ```

5. Abre tu navegador y ve a `http://127.0.0.1:5000/`.

---

## Funcionalidades

- **Página de Inicio**: Muestra un mensaje de bienvenida y una breve descripción.
- **Página "Acerca de"**: Proporciona información adicional sobre la aplicación.
- **Navegación**: Un menú en el encabezado permite cambiar entre las páginas.

---

## Mejoras futuras

- Agregar más páginas y funcionalidades.
- Implementar un sistema de autenticación.
- Mejorar el diseño con frameworks como Bootstrap.
- Conectar la aplicación a una base de datos para manejar datos dinámicos.

---

## Créditos

Este proyecto fue desarrollado como un ejemplo educativo para aprender Flask y la estructura básica de una aplicación web.