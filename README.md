# 📺 Tino TV Master PRO - v5.5 Multiplataforma

Bienvenido a la estación de streaming definitiva. **Tino TV Master** es una aplicación web híbrida diseñada para ofrecer una experiencia de televisión premium, blindada contra publicidad y optimizada para cualquier dispositivo (iPhone, Android, PC).

---

## 🚀 Características Principales

### 🛡️ Seguridad y Blindaje (Ultra-Secure)
*   **Verification Shield:** Sistema de doble confirmación antes de conectar con servidores externos para evitar ataques de redirección.
*   **Anti-Popup Engine:** Implementación de Iframe Sandbox que aniquila el 100% de las ventanas emergentes de publicidad.
*   **Anti-Malware Block:** Bloqueo forzado de descargas automáticas para prevenir la entrada de archivos maliciosos (.exe, .apk).
*   **Referrer Masking:** Enmascaramiento de origen para saltar bloqueos de seguridad de los proveedores de señal.

### 📱 Experiencia de Usuario (UX/UI)
*   **PWA Ready:** Instalable como una aplicación nativa en el Home Screen de tu móvil.
*   **Diseño Responsivo Híbrido:** Interfaz que se adapta automáticamente desde un Notch de iPhone hasta un monitor 4K.
*   **Reproductor PiP (Picture-in-Picture):** Navega por la lista de canales sin perder de vista la transmisión actual.
*   **Buscador Inteligente:** Filtrado instantáneo por nombre de canal o categoría.

### 📢 Sistema Publicitario Integrado
*   **Banner Izquierdo:** Scroll infinito de imágenes promocionales (Carrusel de alta velocidad).
*   **Banner Derecho:** Dual Video Player. Muestra dos clips publicitarios en HD simultáneamente en bucle infinito.

---

## 📂 Estructura del Proyecto

```text
tinoclone/
├── index.html          # Interfaz de usuario y motor de lógica principal
├── tino_tv_data.js     # Base de datos maestra de canales e IDs
├── manifest.json       # Configuración para instalación como App (PWA)
├── vercel.json         # Reglas de seguridad y optimización para Vercel
├── README.md           # Este manual de instrucciones
└── images/             # Carpeta de recursos publicitarios
    ├── banner1.png     # Imagen publicitaria 1
    ├── banner2.png     # Imagen publicitaria 2
    ├── banner_video.mp4 # Video publicitario 1
    └── ...
```

---

## 🌐 Despliegue en Vercel (Paso a Paso)

Para tener tu App viva en internet con un link seguro `https`:

1.  **Sube este proyecto a GitHub:** Crea un repositorio llamado `TV` y sube todos los archivos de la carpeta `tinoclone`.
2.  **Conecta con Vercel:** 
    *   Entra en [Vercel.com](https://vercel.com).
    *   Selecciona **"Add New Project"**.
    *   Importa tu repositorio `TV`.
3.  **Configuración:** Vercel detectará automáticamente el archivo `vercel.json` y aplicará las reglas de seguridad.
4.  **Listo:** Obtendrás un link permanente para compartir y usar en tu móvil.

---

## 🛠️ Personalización de Canales

Para añadir o quitar canales, simplemente edita el archivo `tino_tv_data.js`. Cada canal sigue este formato:

```javascript
{ id: "id_canal", name: "Nombre Visible", cat: "CATEGORÍA", source: "cablevision o ksd" }
```

---

## 📝 Requisitos Técnicos
*   Navegador moderno con soporte para HTML5 y HLS.
*   Conexión a internet estable para el bypass de señales.

---
*Desarrollado para Agustín Pizarro - Estación de Streaming de Alto Rendimiento.*
