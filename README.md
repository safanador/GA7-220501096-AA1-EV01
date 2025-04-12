Herramientas y Tecnologías de Versionamiento para CI


Descripción
Este proyecto consiste en una página web informativa que presenta las herramientas y tecnologías más relevantes para el versionamiento de componentes en procesos de Integración Continua (CI). La interfaz está diseñada para ser moderna, responsiva y de fácil navegación, ofreciendo información útil para desarrolladores y equipos de DevOps.
Características

✅ Diseño moderno con gradientes y efectos visuales
✅ Interfaz completamente responsiva (adaptable a móviles, tablets y escritorio)
✅ Organización por categorías de herramientas
✅ Visualización del flujo de trabajo CI/CD
✅ Efectos de hover y transiciones suaves

Tecnologías Utilizadas

HTML5
CSS3 (Flexbox, Grid, Variables CSS)
Diseño responsivo sin dependencias externas

Estructura del Proyecto
/
├── index.html          # Archivo principal HTML
├── styles/             # Directorio de estilos CSS
│   └── main.css        # Estilos principales (incluidos en index.html)
├── images/             # Iconos e imágenes (opcional)
└── README.md           # Este archivo
Secciones Principales
1. Herramientas de Control de Versiones
Incluye información sobre:

Git
Subversion (SVN)
Mercurial

2. Plataformas de Gestión de Repositorios
Presenta detalles sobre:

GitHub
GitLab
Bitbucket

3. Herramientas de Versionamiento Semántico
Explica conceptos y herramientas como:

SemVer
Conventional Commits
Auto-versioning

4. Flujo de Trabajo CI/CD con Versionamiento
Visualización del proceso de cinco pasos:

Desarrollo
Integración
Versionamiento
Construcción
Despliegue

Instalación y Uso

Clona este repositorio:
bashgit clone https://github.com/tu-usuario/herramientas-versionamiento-ci.git

Abre el archivo index.html en cualquier navegador moderno:
bashcd herramientas-versionamiento-ci
open index.html   # En macOS
# O simplemente haz doble clic en el archivo

No se requiere servidor web, pero puedes usar uno para desarrollo:
bash# Usando Python
python -m http.server 8000

# Usando Node.js con npx
npx serve


Personalización
Cambiar Colores
El esquema de colores se basa en variables CSS que puedes modificar fácilmente:
css:root {
  --primary-color: #4a6fdc;
  --secondary-color: #2c3e72;
  --background-color: #f0f5ff;
  --text-color: #333;
  --card-background: white;
}
Añadir Nuevas Herramientas
Para incluir nuevas herramientas, replica la estructura de las tarjetas existentes:
html<div class="tool-card">
    <div class="tool-header">
        <div class="tool-icon">XX</div>
        <h3 class="tool-name">Nombre de la Herramienta</h3>
    </div>
    <p class="tool-description">Descripción de la herramienta.</p>
    <ul class="features-list">
        <li>Característica 1</li>
        <li>Característica 2</li>
        <li>Característica 3</li>
        <li>Característica 4</li>
    </ul>
</div>
Compatibilidad con Navegadores

Chrome (última versión)
Firefox (última versión)
Safari (última versión)
Edge (última versión)
Opera (última versión)

Contribución
Las contribuciones son bienvenidas. Por favor, sigue estos pasos:

Haz fork del repositorio
Crea una rama para tu función: git checkout -b feature/nueva-herramienta
Realiza tus cambios y haz commit: git commit -m 'Añadir nueva herramienta'
Envía tus cambios: git push origin feature/nueva-herramienta
Abre un Pull Request

Licencia
Este proyecto está licenciado bajo MIT License.