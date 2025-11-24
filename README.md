# 🗓️ Calendario Nu Colombia 2025

Calendario interactivo con branding de Nu Colombia para noviembre-diciembre 2025.

## ✨ Características

- 🎨 **Branding Nu Colombia** - Diseño con el morado característico (#820AD1)
- 🔤 **Google Sans** - Tipografía oficial
- ✏️ **Notas editables** - Agrega nombres o recordatorios en cada día
- 💾 **Guardado automático** - Las notas persisten en el navegador
- 🔗 **Compartir por link** - Genera URL con toda la información cargada
- 📱 **Responsive** - Funciona en móvil y desktop
- 🌟 **Día actual destacado** - Se resalta automáticamente

## 🚀 Uso

1. **Clonar el repositorio**
   ```bash
   git clone https://github.com/tuusuario/calendario-nu-colombia.git
   cd calendario-nu-colombia
   ```

2. **Abrir el calendario**
   ```bash
   open index.html
   ```
   O arrastra `index.html` a tu navegador

3. **Editar días**
   - Haz clic en el espacio bajo cualquier día
   - Escribe nombres o notas
   - Las notas se guardan automáticamente

4. **Compartir calendario**
   - Haz clic en "🔗 Generar Link"
   - El link se copia automáticamente
   - Comparte el link y las notas se cargarán automáticamente

## 🔗 Compartir Calendarios

1. **Generar link:**
   - Llena el calendario con nombres/notas
   - Click en "🔗 Generar Link"
   - El link se copia automáticamente

2. **Usar link compartido:**
   - Abre el link recibido
   - Las notas se cargan automáticamente
   - Ejemplo: `index.html?data=eyJub3RlLTExLTI0IjoiSnVhbiJ9`

3. **Limpiar calendario:**
   - Click en "🗑️ Limpiar Todo" para borrar todas las notas

## 📂 Estructura

```
calendario-nu-colombia/
├── index.html          # Archivo principal
└── README.md          # Documentación
```

## 🎨 Colores Nu Colombia

- **Morado principal**: `#820AD1`
- **Morado hover**: `#F5E6FF`
- **Degradado**: `#820AD1` → `#A259FF`

## 🔧 Personalización

Para cambiar el año o agregar meses, edita las secciones `.month-section` en `index.html`:

```html
<div class="month-section">
    <div class="month-name">Mes</div>
    <div class="calendar-grid">
        <!-- Agregar días aquí -->
    </div>
</div>
```

## 📱 Compatibilidad

- ✅ Chrome / Edge
- ✅ Firefox
- ✅ Safari
- ✅ Mobile browsers

## 📄 Licencia

MIT License - Uso libre

---

Hecho con 💜 para Nu Colombia 🇨🇴
