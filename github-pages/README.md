# Página de Producto AMP - GitHub Pages

Página web responsive del producto **Cable UTP AMP Categoría 6 Chaqueta CMR 23AWG 6-1427200-4** optimizada para GitHub Pages.

## 🚀 Cómo subir a GitHub Pages

### Paso 1: Crear un repositorio en GitHub

1. Ve a [GitHub](https://github.com) y crea un nuevo repositorio
2. Nómbralo como quieras (ej: `amp-product-page` o `cable-amp-6-1427200-4`)
3. **NO** inicialices con README, .gitignore o licencia

### Paso 2: Subir los archivos

Abre PowerShell o Git Bash en la carpeta `github-pages` y ejecuta:

```bash
# Inicializar git
git init

# Agregar todos los archivos
git add .

# Hacer commit
git commit -m "Initial commit: Página producto AMP"

# Agregar el repositorio remoto (reemplaza TU_USUARIO y TU_REPOSITORIO)
git remote add origin https://github.com/TU_USUARIO/TU_REPOSITORIO.git

# Subir a GitHub
git branch -M main
git push -u origin main
```

### Paso 3: Activar GitHub Pages

1. Ve a tu repositorio en GitHub
2. Click en **Settings** (Configuración)
3. En el menú lateral, busca **Pages**
4. En **Source**, selecciona la rama **main** y la carpeta **/ (root)**
5. Click en **Save**
6. Espera unos minutos y tu página estará disponible en:
   ```
   https://TU_USUARIO.github.io/TU_REPOSITORIO/
   ```

## 📁 Estructura de archivos

```
github-pages/
├── index.html          # Página principal
├── css/
│   └── style.css       # Estilos personalizados
├── components/
│   └── navbar.html     # Componente de navegación
├── assets/
│   └── image.png       # Imagen del producto
└── README.md           # Este archivo
```

## ✨ Características

- ✅ Diseño completamente responsive
- ✅ Optimizado para móviles, tablets y desktop
- ✅ Usa Tailwind CSS (CDN)
- ✅ Font Awesome para iconos
- ✅ Modal para ver imágenes ampliadas
- ✅ Acordeones para información adicional
- ✅ Diseño moderno y profesional

## 🔧 Tecnologías utilizadas

- HTML5
- Tailwind CSS (CDN)
- Font Awesome 6.5.1
- JavaScript vanilla

## 📝 Notas

- La página está lista para funcionar en GitHub Pages
- Todas las rutas están ajustadas para funcionar desde la raíz del repositorio
- Los recursos externos (imágenes de logos, etc.) se cargan desde URLs externas

## 🌐 URL de ejemplo

Una vez configurado, tu página estará disponible en:
```
https://TU_USUARIO.github.io/TU_REPOSITORIO/
```

¡Listo! Tu página estará en línea en unos minutos. 🎉

