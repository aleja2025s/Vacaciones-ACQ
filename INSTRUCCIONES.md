# 📦 Subir a GitHub

## Pasos para publicar el calendario

### 1️⃣ Inicializar repositorio local
```bash
cd /Users/alejandra.pinzon
git init
git add index.html README.md .gitignore
git commit -m "✨ Calendario Nu Colombia 2025"
```

### 2️⃣ Crear repositorio en GitHub
1. Ve a https://github.com/new
2. Nombre: `calendario-nu-colombia`
3. Descripción: `Calendario interactivo Nu Colombia 2025`
4. **No** inicialices con README
5. Click en **Create repository**

### 3️⃣ Conectar y subir
```bash
git branch -M main
git remote add origin https://github.com/TU_USUARIO/calendario-nu-colombia.git
git push -u origin main
```

### 4️⃣ Activar GitHub Pages (opcional)
1. Ve a **Settings** → **Pages**
2. Source: `Deploy from branch`
3. Branch: `main` / `root`
4. Click **Save**
5. Tu calendario estará en: `https://TU_USUARIO.github.io/calendario-nu-colombia`

## 🔗 URLs

- **Repositorio**: `https://github.com/TU_USUARIO/calendario-nu-colombia`
- **Demo live**: `https://TU_USUARIO.github.io/calendario-nu-colombia`

## ✅ Archivos incluidos

- ✓ `index.html` - Calendario completo
- ✓ `README.md` - Documentación
- ✓ `.gitignore` - Archivos ignorados
- ✓ `INSTRUCCIONES.md` - Esta guía

