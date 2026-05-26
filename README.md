# LUMIK AR | Realidad Aumentada y Tecnología Inmersiva

[![GitHub Pages](https://img.shields.io/badge/GitHub-Pages-deployed?color=00d4ff&logo=github)](https://dr-ianX.github.io/LUMIK_WEBAR/)
[![License](https://img.shields.io/badge/license-MIT-blue.svg)](LICENSE)

## 🌟 Sobre el Proyecto | About the Project

LUMIK es una plataforma de tecnología inmersiva creada por un artista visual, dedicada a pushing the boundaries of experiencias interactivas 3D. Nos especializamos en Realidad Aumentada (AR), Realidad Mixta (MR), videomapping, laser mapping y creando instalaciones audiovisuales inmersivas.

LUMIK is an immersive technology platform created by a visual artist, dedicated to pushing the boundaries of interactive 3D experiences. We specialize in Augmented Reality (AR), Mixed Reality (MR), videomapping, laser mapping, and creating immersive audiovisual installations.

## 🚀 Características | Features

- ✨ **Experiencia AR Interactiva** - Visualiza modelos 3D en tu entorno real usando AR
- 🌐 **Contenido Bilingüe** - Español e Inglés para audiencias globales
- 🎨 **Diseño Moderno** - Animaciones fluidas y estética contemporánea
- 📱 **Responsive** - Optimizado para todos los dispositivos
- ⚡ **Ligero** - Construido para GitHub Pages, carga rápida
- 🎯 **UX Intuitiva** - Botón AR visible y opción de salir fácil

## 🛠️ Tecnologías | Technologies

- **HTML5/CSS3** - Estructura y estilos
- **JavaScript (ES6+)** - Interactividad y lógica
- **model-viewer** - Visualizador de modelos 3D de Google
- **WebXR** - Soporte para experiencias AR/VR
- **CSS Animations** - Animaciones fluidas y modernas

## 📦 Instalación Local | Local Installation

### Prerrequisitos | Prerequisites
- Node.js (v14 o superior)
- npm o yarn

### Pasos | Steps

1. Clona el repositorio:
```bash
git clone https://github.com/dr-ianX/LUMIK_WEBAR.git
cd LUMIK_WEBAR
```

2. Instala dependencias:
```bash
npm install
```

3. Inicia el servidor de desarrollo:
```bash
npm start
```

4. Abre tu navegador en `http://localhost:3000`

## 🌐 Despliegue en GitHub Pages | GitHub Pages Deployment

### Método Automático (Recomendado) | Automated Method (Recommended)

1. Ve a la configuración del repositorio en GitHub
2. Navega a **Settings** > **Pages**
3. En **Source**, selecciona **Deploy from a branch**
4. Elige la rama `main` y la carpeta `/ (root)`
5. Haz clic en **Save**

Tu sitio estará disponible en: `https://dr-ianX.github.io/LUMIK_WEBAR/`

### Método Manual | Manual Method

1. Construye el proyecto:
```bash
npm run build
```

2. Los archivos compilados estarán en la carpeta `dist/`
3. Sube el contenido de `dist/` a la rama `gh-pages`

## 📁 Estructura del Proyecto | Project Structure

```
LUMIK_WEBAR/
├── src/
│   ├── index.html          # Página principal
│   ├── index.js            # Lógica JavaScript
│   └── assets/
│       └── model.glb       # Modelo 3D
├── config/
│   └── webpack.config.js   # Configuración de Webpack
├── package.json            # Dependencias del proyecto
├── server.js               # Servidor de desarrollo
└── README.md              # Este archivo
```

## 🎨 Personalización | Customization

### Cambiar el Modelo 3D | Change the 3D Model

Reemplaza el archivo `src/assets/model.glb` con tu propio modelo 3D en formato GLB/GLTF.

### Modificar Colores | Modify Colors

Edita las variables CSS en `src/index.html`:

```css
:root{
--primary:#00d4ff;      /* Color principal */
--secondary:#ff00aa;    /* Color secundario */
--dark:#0a0a0a;         /* Color oscuro */
--darker:#050505;       /* Color más oscuro */
--light:#ffffff;        /* Color claro */
--gray:#888888;         /* Color gris */
--glass:rgba(0,0,0,0.7); /* Efecto vidrio */
}
```

### Editar Contenido | Edit Content

Todo el contenido está en `src/index.html`. Busca las secciones que quieres modificar y edita el texto HTML directamente.

## 🔧 Solución de Problemas | Troubleshooting

### El modelo 3D no carga
- Asegúrate de que el archivo `.glb` esté en la carpeta correcta
- Verifica que el modelo no sea demasiado grande (máximo 50MB recomendado)
- Comprueba que el modelo esté optimizado para web

### El botón AR no aparece
- Asegúrate de estar usando un dispositivo compatible con AR
- Verifica que el navegador soporte WebXR
- En iOS, usa Safari; en Android, usa Chrome

### El sitio no carga en GitHub Pages
- Verifica que la rama esté configurada correctamente en Settings > Pages
- Asegúrate de que los archivos estén en la raíz del repositorio
- Espera unos minutos después del push para que GitHub Pages se actualice

## 📞 Contacto | Contact

- **Email:** hello@lumik.ar
- **GitHub:** https://github.com/dr-ianX/LUMIK_WEBAR
- **Live Demo:** https://dr-ianX.github.io/LUMIK_WEBAR/

## 📄 Licencia | License

Este proyecto está bajo la Licencia MIT. Ver el archivo [LICENSE](LICENSE) para más detalles.

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.

## 🙏 Agradecimientos | Acknowledgments

- Google por la biblioteca [model-viewer](https://github.com/google/model-viewer)
- La comunidad de WebXR por sus contribuciones
- Todos los artistas y desarrolladores que inspiran este proyecto

---

**LUMIK Technology** ✦ 3D + AR + Videomapping + Laser Mapping ✦
