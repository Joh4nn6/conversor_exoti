# 🤖 Claude Converter Pro

Una aplicación web profesional para convertir **Markdown**, **HTML** y texto plano en documentos **PDF**, **DOCX**, **PNG**, **HTML** y **TXT** de alta calidad, con una interfaz moderna, funcionalidades con IA y vista previa en tiempo real.

![Claude Converter Pro](https://img.shields.io/badge/Claude-Converter%20Pro-blue?style=for-the-badge&logo=robot)
![Version](https://img.shields.io/badge/version-2.0-brightgreen?style=for-the-badge)
![GitHub Pages](https://img.shields.io/badge/deploy-GitHub%20Pages-orange?style=for-the-badge&logo=github)

## 🚀 Características Principales

### ✨ **Interfaz Premium**
- 🎨 **Tema oscuro/claro** con animaciones suaves
- 🌌 **Fondo galáctico animado** estilo Netflix Premium  
- 📱 **Diseño totalmente responsive** (móvil, tablet, escritorio)
- ⚡ **Carga instantánea** sin dependencias pesadas
- 🔧 **Configuración avanzada** personalizable

### 📝 **Editor Avanzado**
- 🛠️ **Barra de herramientas** con formato rápido (negrita, cursiva, enlaces, tablas)
- 📊 **Estadísticas en tiempo real** (caracteres, palabras, líneas, tiempo de lectura)
- 🎯 **Auto-detección de formato** (Markdown, HTML, texto plano)
- 💾 **Auto-guardado** inteligente con recuperación de sesión
- 📁 **Carga múltiple** de archivos (.md, .html, .txt, .rtf)
- 🎨 **Auto-formateo** con un clic

### 📄 **Exportación Premium**
- 🏆 **PDF de alta calidad** con:
  - Headers y footers automáticos
  - Tabla de contenidos generada automáticamente
  - Numeración de páginas
  - Formato A4 profesional
  - Calidad configurable (estándar, alta, máxima)
- 📝 **DOCX** con estructura de encabezados preservada
- 📸 **PNG** de alta resolución con fondo blanco
- 🌐 **HTML** standalone con estilos embebidos
- 📄 **TXT/MD** limpios sin front-matter
- 🗜️ **ZIP** con todos los formatos (próximamente)

### 🎨 **Vista Previa en Vivo**
- 📋 **Hoja A4 realista** que muestra exactamente lo que se exportará
- 🔍 **Control de zoom** (50% - 200%)
- 🖥️ **Modo pantalla completa** para vista previa
- 🔄 **Actualización automática** mientras escribes
- 📑 **Tabla de contenidos** generada automáticamente

### 🤖 **Funcionalidades con IA** (Próximamente)
- ✨ **Optimización automática** del contenido
- 🎯 **Sugerencias de formato** inteligentes
- 📚 **Plantillas profesionales** predefinidas
- 🔧 **Corrección de estructura** automática

### 🛡️ **Seguridad y Robustez**
- 🧹 **Sanitización HTML** automática (elimina scripts maliciosos)
- 🔒 **Procesamiento local** (sin envío de datos a servidores)
- ⚡ **Manejo de errores** robusto
- 💾 **Límites de archivo** configurables (10MB por defecto)
- 🖼️ **Conversión automática** de imágenes remotas para evitar CORS

## 🎯 **Plantillas Incluidas**

### 🎓 **Documento Académico**
Estructura completa para ensayos, papers y tesis con:
- Portada con metadatos
- Resumen ejecutivo
- Tabla de contenidos automática
- Secciones organizadas
- Referencias bibliográficas

### 💼 **Reporte Corporativo**  
Template profesional para empresas con:
- Executive summary
- Análisis financiero con tablas
- Gráficos y métricas
- Recomendaciones estratégicas
- Plan de acción

### 📋 **Currículum Profesional**
CV moderno y completo con:
- Header con información de contacto
- Perfil profesional
- Experiencia laboral estructurada
- Educación y certificaciones
- Habilidades técnicas

### 🔧 **Documentación Técnica**
Manual técnico completo con:
- Tabla de contenidos detallada
- Requisitos del sistema
- Instrucciones de instalación
- Ejemplos de código
- Troubleshooting

## 🚀 **Instalación y Uso**

### **Opción 1: GitHub Pages (Recomendado)**
1. Haz fork de este repositorio
2. Ve a **Settings → Pages**
3. Selecciona `main` branch y `/ (root)` folder
4. Tu conversor estará disponible en `https://tu-usuario.github.io/claude-converter-pro/`

### **Opción 2: Netlify/Vercel**
1. Conecta tu repositorio con Netlify/Vercel
2. Deploy automático con cada commit
3. URL personalizada disponible

### **Opción 3: Servidor Local**
```bash
# Clona el repositorio
git clone https://github.com/tu-usuario/claude-converter-pro.git
cd claude-converter-pro

# Inicia servidor local (Python)
python -m http.server 8000

# O con Node.js
npx serve .

# Abre http://localhost:8000
```

> ⚠️ **Importante**: No uses `file:///` directamente. Las librerías CDN requieren protocolo HTTP/HTTPS.

## 💡 **Guía de Uso**

### **Escribiendo Contenido**
1. **Pega o escribe** tu contenido en el editor izquierdo
2. **Usa la barra de herramientas** para formato rápido
3. **Observa las estadísticas** en tiempo real
4. **La vista previa** se actualiza automáticamente

### **Usando Plantillas**
1. Haz clic en **📄 Plantillas**
2. Selecciona el tipo de documento
3. **Personaliza** el contenido base
4. **Exporta** en tu formato preferido

### **Exportando Documentos**
1. **PDF Premium**: Máxima calidad con headers/footers
2. **DOCX**: Para edición posterior en Word
3. **PNG**: Imagen de alta resolución
4. **HTML**: Página web standalone
5. **TXT/MD**: Formatos de texto puro

### **Configuración Avanzada**
- **Calidad PDF**: Estándar (menor tamaño) → Máxima (mejor calidad)
- **Escala de exportación**: 1x (rápido) → 3x (alta resolución)
- **Auto-guardado**: Guarda automáticamente cada 30 segundos
- **Tema**: Oscuro/claro según tu preferencia

## 🎨 **Personalización**

### **Colores y Estilos**
Los colores inline en HTML se respetan tanto en vista previa como en exportación:
```html
<span style="color: #e50914;">Texto en rojo</span>
<span style="background: #f0f9ff; padding: 4px 8px; border-radius: 4px;">Destacado</span>
```

### **Imágenes**
```markdown
![Descripción](https://ejemplo.com/imagen.jpg)
<!-- Las imágenes remotas se convierten automáticamente para evitar CORS -->
```

### **Tablas Avanzadas**
```markdown
| Característica | Básico | Premium | Pro |
|----------------|--------|---------|-----|
| Exportar PDF   | ✅     | ✅      | ✅  |
| Plantillas     | ❌     | ✅      | ✅  |
| IA             | ❌     | ❌      | ✅  |
```

## 🛠️ **Tecnologías Utilizadas**

### **Frontend**
- **HTML5** semántico y accesible
- **CSS3** moderno con custom properties
- **JavaScript ES6+** con async/await
- **Responsive Design** con CSS Grid/Flexbox

### **Librerías (CDN)**
- **[Marked.js](https://marked.js.org/)** - Parser Markdown
- **[html2pdf.js](https://github.com/eKoopmans/html2pdf.js)** - Generación PDF
- **[html2canvas](https://html2canvas.hertzen.com/)** - Capturas PNG  
- **[docx](https://github.com/dolanmiu/docx)** - Generación DOCX
- **[FileSaver.js](https://github.com/eligrey/FileSaver.js/)** - Descarga de archivos

### **Características Técnicas**
- 🔄 **Sin frameworks** pesados (Vanilla JS)
- ⚡ **
