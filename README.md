# Food & Flow - Sitio Web

## 🚀 Cómo Ejecutar el Proyecto Localmente

### Opción 1: Abrir Directamente en el Navegador
1. Haz doble clic en `index.html`
2. O desde PowerShell:
```powershell
Start-Process "index.html"
```

### Opción 2: Servidor HTTP Local con Python (Recomendado)
1. Abre PowerShell en la carpeta del proyecto
2. Ejecuta el siguiente comando:
```powershell
python -m http.server 8000
```
3. Abre tu navegador y ve a: `http://localhost:8000`
4. Para detener el servidor, presiona `Ctrl+C` en la terminal

### Opción 3: Live Preview (Extensión de Cursor/VS Code) ⭐ RECOMENDADO
**Extensión oficial de Microsoft que permite abrir el navegador directamente desde Cursor**

1. **Instalar la extensión:**
   - Presiona `Ctrl+Shift+X` para abrir el panel de extensiones
   - Busca "Live Preview" (por Microsoft)
   - Haz clic en "Install"

2. **Usar Live Preview:**
   - Abre `index.html` en Cursor
   - Haz clic derecho en `index.html` → Selecciona "Show Preview" o "Abrir Vista Previa"
   - O presiona `Ctrl+Shift+V` (vista previa integrada)
   - O busca en la barra lateral el ícono de "Live Preview" y haz clic en "Show Preview"
   - El navegador se abrirá automáticamente en `http://localhost:3000` (o puerto disponible)
   - Se actualiza automáticamente al guardar cambios

### Opción 4: Live Server (Extensión alternativa)
1. **Instalar la extensión:**
   - Presiona `Ctrl+Shift+X` para abrir extensiones
   - Busca "Live Server" (por Ritwick Dey)
   - Haz clic en "Install"

2. **Usar Live Server:**
   - Haz clic derecho en `index.html`
   - Selecciona "Open with Live Server"
   - El navegador se abrirá automáticamente y se actualizará al guardar cambios

### Opción 5: Vista Previa Integrada (Ctrl+Shift+V)
1. Abre el archivo `index.html` en Cursor
2. Presiona `Ctrl+Shift+V` para abrir la vista previa dentro de Cursor
3. La vista previa se actualiza automáticamente al guardar cambios
4. **Nota:** Algunas funciones (como Google Maps) pueden requerir un servidor HTTP real

## 📝 Notas Importantes

- **Google Maps API**: Necesitas reemplazar `YOUR_API_KEY` en la línea 12 de `index.html` con tu clave real de Google Maps API para que el mapa funcione correctamente.

## 📁 Estructura del Proyecto

```
.
├── index.html      # Archivo principal HTML
├── styles.css      # Estilos CSS
└── README.md       # Este archivo
```

## 🌐 Características

- Sitio web responsive
- Soporte multiidioma (Español/Inglés)
- Integración con Google Maps
- Lista de espera para Bogotá (almacenada en localStorage)
- Contador de tiempo restante en ubicaciones

