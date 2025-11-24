# 🤝 Calendario Colaborativo - Limitaciones

## ⚠️ Importante

El archivo `colaborativo.html` usa **localStorage del navegador**, lo que significa:

### ✅ Funciona:
- Compartir link entre personas en **LA MISMA COMPUTADORA**
- Varias pestañas del mismo navegador ven los mismos cambios
- Actualización automática cada 10 segundos

### ❌ NO funciona:
- Compartir entre **diferentes computadoras**
- Compartir entre diferentes navegadores
- Colaboración en tiempo real entre dispositivos

## 🔧 Para colaboración real entre dispositivos

Necesitas un **backend** con base de datos. Opciones:

### 1. Firebase (Google) - Gratis
```javascript
// Requiere configuración de Firebase
// Tutorial: firebase.google.com
```

### 2. Supabase - Gratis
```javascript
// Alternativa open-source a Firebase
// Tutorial: supabase.com
```

### 3. JSONBin.io - API Gratuita
```javascript
// API REST simple
// Requiere registro y API key
```

## 💡 Recomendación

**Para tu caso (calendario Nu):**

- Si es para **un solo equipo/computadora**: Usa `colaborativo.html` ✅
- Si necesitas **compartir entre dispositivos**: Necesitas backend con Firebase o similar 🔥

## 🚀 Opción rápida: GitHub Pages + Firebase

1. Crea cuenta en Firebase (gratis)
2. Obtén credenciales
3. Agrega Firebase al HTML
4. Publica en GitHub Pages

¿Quieres que te ayude a implementar Firebase para colaboración real?

