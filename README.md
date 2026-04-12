# Desarrollo de Aplicaciones Móviles 2026

Resumen de la materia Desarrollo de Aplicaciones Móviles - DAM 2026.

## 📚 Contenido

El resumen está escrito en AsciiDoc y se publica automáticamente en GitHub Pages.

## 🌐 Ver Online

El resumen está disponible en: `https://<tu-usuario>.github.io/2026-dam/`

## 🚀 Despliegue

El sitio se despliega automáticamente a GitHub Pages mediante GitHub Actions cada vez que se hace push a la rama `main`.

### Características del sitio:

- ✅ Tema oscuro personalizado
- ✅ Menú lateral con índice desplegable/colapsable
- ✅ Navegación jerárquica hasta 4 niveles
- ✅ Resaltado de sintaxis para código
- ✅ Responsive design

## 🛠️ Desarrollo Local

Para generar el HTML localmente:

```bash
# Instalar Asciidoctor
gem install asciidoctor

# Generar HTML
asciidoctor -o output/index.html resumen.adoc

# Copiar recursos
cp daro-dark.css output/
cp -R images output/
```

## 📝 Estructura

```
.
├── resumen.adoc          # Contenido principal
├── daro-dark.css         # Estilos personalizados
├── images/               # Imágenes del documento
├── material/             # Material adicional
└── .github/workflows/    # CI/CD para GitHub Pages
```
