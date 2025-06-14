# GPT-BOT-RD
GPT-Bot RD es una solución dominicana que une IA y automatización para transformar la experiencia en restaurantes, hogares y empresas. Incluye una demo de menú digital inteligente y la base para futuras integraciones robóticas. Creado por Ángel Manuel Díaz Batista.
📦 GPT-Bot RD — Proyecto de Innovación Robótica Dominicana
Índice
Descripción del Proyecto
Estructura de Carpetas y Archivos
Descripción de Carpetas y Archivos Importantes
Instalación y Uso
Tecnologías Utilizadas
Autor y Créditos
Descripción del Proyecto
GPT-Bot RD es un proyecto de innovación tecnológica desarrollado para ITLA, que propone un robot asistente físico con inteligencia artificial basada en la API de ChatGPT. El robot puede conversar en tiempo real, asistir en tareas diversas y personalizar sus interacciones según el usuario.

Estructura de Carpetas y Archivos
/
├── README.md                 # Guía e información del proyecto
├── bun.lockb                 # Lockfile dependencias (si usas Bun)
├── components.json           # Definición/configuración de componentes
├── eslint.config.js          # Configuración ESLint
├── index.html                # HTML base sobre el cual se carga React
├── package-lock.json         # Lockfile de dependencias npm
├── package.json              # Definición de dependencias y scripts
├── postcss.config.js         # Configuración de PostCSS (procesador CSS)
├── public/
│   ├── favicon.ico
│   └── placeholder.svg
├── src/
│   ├── App.tsx               # Componente raíz React
│   ├── main.tsx              # Entrada principal de la app
│   ├── index.css             # Estilos globales
│   ├── components/
│   │   ├── ApplicationsSection.tsx
│   │   ├── ContactForm.tsx
│   │   ├── DevelopmentTimeline.tsx
│   │   ├── FeaturesSection.tsx
│   │   ├── LandingHero.tsx
│   │   ├── ObjectivesSection.tsx
│   │   ├── RestaurantMenu.tsx
│   │   └── ui/               # Componentes UI reutilizables de shadcn/ui
│   ├── hooks/                # Hooks personalizados
│   ├── lib/                  # Funciones auxiliares (helpers)
│   ├── pages/
│   │   ├── Index.tsx         # Landing principal
│   │   ├── NotFound.tsx      # Página 404
│   │   └── Restaurante.tsx   # Demo restaurante inteligente
│   └── vite-env.d.ts         # Tipado global para Vite
├── tailwind.config.ts        # Configuración Tailwind CSS
├── tsconfig.app.json         # Tipado TypeScript para la app
├── tsconfig.json             # Configuración global TypeScript
├── tsconfig.node.json        # Tipado TypeScript para Node.js
└── vite.config.ts            # Configuración avanzada de build/dev
Descripción de Carpetas y Archivos Importantes
/public/
Archivos estáticos accesibles directamente (íconos, imágenes, etc.).

/src/

App.tsx: Componente raíz que vincula todas las rutas.
main.tsx: Punto de entrada desde donde React renderiza la app.
index.css: Estilos globales; configuración inicial de Tailwind.
components/
Componentes reutilizables y secciones de la landing page y la demo.
components/ui/
Componentes atómicos y elementos visuales basados en la librería shadcn/ui (botones, modales, toasts, tabs, etc.).
hooks/
Funciones React para lógica reutilizable (ej: notificaciones).
lib/
Helpers y utilidades generales para la lógica del proyecto.
pages/
Archivos para cada ruta principal:
Index.tsx: Página principal (landing)
Restaurante.tsx: Demo del menú digital y el robot.
NotFound.tsx: Página para rutas no existentes (404).
README.md:
Este documento, esencial para orientación y colaboración.

package.json:
Manejo de dependencias, scripts de start/build y metadatos del proyecto.

tailwind.config.ts:
Define los colores, fuentes y utilidades de Tailwind CSS usadas globalmente.

vite.config.ts:
Alias, paths y opciones para build y desarrollo rápido con Vite.

Instalación y Uso
Clona el repositorio:


git clone https://github.com/TUUSUARIO/TUREPO.git
cd TUREPO
Instala dependencias:


npm install
Ejecuta el proyecto:


npm run dev
El proyecto estará disponible en http://localhost:8080

Tecnologías Utilizadas
React (TypeScript)
Vite (build y desarrollo)
Tailwind CSS (diseño moderno y responsivo)
shadcn/ui (componentes UI profesionales reutilizables)
Lucide-react (íconos SVG)
@tanstack/react-query (data-fetching)
Otros: ESLint, PostCSS, hooks propios.
Autor y Créditos
Desarrollado por: Ángel Manuel Díaz Batista
Institución: ITLA — Instituto Tecnológico de Las Américas
Asignatura: Proyecto Integrador / Innovación Tecnológica
Año: 2025
