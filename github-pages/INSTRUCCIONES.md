# 📋 Instrucciones para subir a GitHub Pages

## Paso 1: Crear un repositorio en GitHub

1. Ve a [GitHub.com](https://github.com) e inicia sesión
2. Haz clic en el botón **"+"** (arriba a la derecha) → **"New repository"**
3. Completa:
   - **Repository name**: `amp-producto-6-1427200-4` (o el nombre que prefieras)
   - **Description**: "Página del producto Cable AMP 6-1427200-4"
   - **Visibilidad**: Público (para GitHub Pages gratuito)
   - ⚠️ **NO marques** "Add a README file", "Add .gitignore" ni "Choose a license"
4. Haz clic en **"Create repository"**

## Paso 2: Abrir PowerShell en la carpeta github-pages

1. Abre PowerShell
2. Navega a la carpeta `github-pages`:
   ```powershell
   cd "C:\Users\Developer 02\cisco\github-pages"
   ```

## Paso 3: Inicializar Git y subir archivos

Copia y pega estos comandos uno por uno (reemplaza `TU_USUARIO` y `TU_REPOSITORIO` con tus datos):

```powershell
# 1. Inicializar Git
git init

# 2. Agregar todos los archivos
git add .

# 3. Hacer el primer commit
git commit -m "Primera versión: Página producto AMP 6-1427200-4"

# 4. Agregar el repositorio remoto (REEMPLAZA TU_USUARIO y TU_REPOSITORIO)
git remote add origin https://github.com/TU_USUARIO/TU_REPOSITORIO.git

# 5. Cambiar a rama main
git branch -M main

# 6. Subir a GitHub
git push -u origin main
```

**Ejemplo real:**
Si tu usuario es `juanperez` y tu repositorio es `amp-producto`, el comando sería:
```powershell
git remote add origin https://github.com/juanperez/amp-producto.git
```

## Paso 4: Activar GitHub Pages

1. Ve a tu repositorio en GitHub (ej: `https://github.com/TU_USUARIO/TU_REPOSITORIO`)
2. Haz clic en **"Settings"** (Configuración) en el menú superior
3. En el menú lateral izquierdo, busca y haz clic en **"Pages"**
4. En la sección **"Source"**:
   - Selecciona **"Deploy from a branch"**
   - **Branch**: selecciona `main`
   - **Folder**: selecciona `/ (root)`
5. Haz clic en **"Save"**
6. Espera 1-2 minutos

## Paso 5: Ver tu página en línea

Tu página estará disponible en:
```
https://TU_USUARIO.github.io/TU_REPOSITORIO/
```

**Ejemplo:**
Si tu usuario es `juanperez` y tu repositorio es `amp-producto`:
```
https://juanperez.github.io/amp-producto/
```

## ✅ Verificación

- La página debería cargar correctamente
- El navbar debería aparecer
- Las imágenes deberían verse
- El diseño debería ser responsive

## 🔄 Actualizar la página

Si haces cambios y quieres actualizar la página:

```powershell
cd "C:\Users\Developer 02\cisco\github-pages"
git add .
git commit -m "Actualización: descripción de cambios"
git push
```

Los cambios se reflejarán en 1-2 minutos.

## ❓ Problemas comunes

### Error: "remote origin already exists"
```powershell
git remote remove origin
git remote add origin https://github.com/TU_USUARIO/TU_REPOSITORIO.git
```

### Error: "fatal: not a git repository"
Asegúrate de estar en la carpeta `github-pages`:
```powershell
cd "C:\Users\Developer 02\cisco\github-pages"
```

### La página no carga
- Verifica que el repositorio sea **público**
- Espera 2-3 minutos más
- Verifica que en Settings → Pages esté configurado correctamente

---

¡Listo! 🎉 Tu página estará en línea en unos minutos.

