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
/
├── README.md                 # Información general y guía del proyecto.
├── bun.lockb                 # Archivo de lock de dependencias (si usas Bun).
├── components.json           # Configuración/importación de componentes.
├── eslint.config.js          # Configuración de ESLint para mantener el código limpio.
├── index.html                # HTML base sobre el cual React monta la app.
├── package-lock.json         # Lockfile de dependencias npm.
├── package.json              # Archivo principal de configuración de npm y scripts.
├── postcss.config.js         # Configuración de PostCSS (optimización CSS).
├── public/                   # Archivos públicos (favicon, imágenes estáticas).
│   ├── favicon.ico
│   └── placeholder.svg
├── src/                      # Carpeta principal del código fuente.
│   ├── App.tsx                       # Componente principal de la app.
│   ├── main.tsx                      # Punto de entrada para renderizar la app.
│   ├── index.css                     # Estilos globales.
│   ├── components/                   # Componentes reutilizables y de la landing.
│   │   ├── ApplicationsSection.tsx
│   │   ├── ContactForm.tsx
│   │   ├── DevelopmentTimeline.tsx
│   │   ├── FeaturesSection.tsx
│   │   ├── LandingHero.tsx
│   │   ├── ObjectivesSection.tsx
│   │   ├── RestaurantMenu.tsx
│   │   └── ui/               # Componentes UI reutilizables (shadcn/ui)
│   ├── hooks/                          # Hooks personalizados (lógica reutilizable)
│   ├── lib/                            # Funciones utilitarias, helpers
│   ├── pages/                          # Páginas principales de la app
│   │   ├── Index.tsx              # Landing page principal
│   │   ├── NotFound.tsx           # Página 404
│   │   └── Restaurante.tsx        # Demo restaurante inteligente
│   └── vite-env.d.ts
├── tailwind.config.ts         # Configuración de Tailwind CSS.
├── tsconfig.app.json          # Configuración de TypeScript para la app.
├── tsconfig.json              # Configuración global de TypeScript.
├── tsconfig.node.json         # Configuración de TypeScript para entorno Node.js.
└── vite.config.ts             # Configuración de Vite (build, desarrollo, aliases).
/
├── README.md
├── bun.lockb
├── components.json
├── eslint.config.js
├── index.html
├── package-lock.json
├── package.json
├── postcss.config.js
├── public/
│   ├── favicon.ico
│   └── placeholder.svg
├── src/
│   ├── App.tsx
│   ├── main.tsx
│   ├── index.css
│   ├── components/
│   │   ├── ApplicationsSection.tsx
│   │   ├── ContactForm.tsx
│   │   ├── DevelopmentTimeline.tsx
│   │   ├── FeaturesSection.tsx
│   │   ├── LandingHero.tsx
│   │   ├── ObjectivesSection.tsx
│   │   ├── RestaurantMenu.tsx
│   │   └── ui/
│   ├── hooks/
│   ├── lib/
│   ├── pages/
│   │   ├── Index.tsx
│   │   ├── NotFound.tsx
│   │   └── Restaurante.tsx
│   └── vite-env.d.ts
├── tailwind.config.ts
├── tsconfig.app.json
├── tsconfig.json
├── tsconfig.node.json
└── vite.config.ts


import React, { useState } from "react";
import { CheckCircle, CircleChevronRight } from "lucide-react";
import { Button } from "@/components/ui/button";

const PLATOS = [
  {
    nombre: "Chillo al Ajillo",
    desc: "Fresco pescado local en salsa de ajos, con vegetales y guarnición.",
    precio: 480,
  },
  {
    nombre: "Pechuga Suprema",
    desc: "Pechuga rellena de queso y jamón, sobre crema de maíz.",
    precio: 370,
  },
  {
    nombre: "Risotto Dominicano",
    desc: "Arroz cremoso con coco, camarones y plátano verde crujiente.",
    precio: 420,
  },
  {
    nombre: "Ensalada Robot AI",
    desc: "Mezcla de verdes, mango, aguacate y nueces, recomendada por IA.",
    precio: 270,
  },
  {
    nombre: "Juguito de Chinola",
    desc: "Bebida natural, refrescante y antioxidante.",
    precio: 90,
  },
];

export function RestaurantMenu() {
  const [pedido, setPedido] = useState<number[]>([]);
  const [enviado, setEnviado] = useState(false);

  const alternarPlato = (idx: number) => {
    setPedido((prev) =>
      prev.includes(idx) ? prev.filter((i) => i !== idx) : [...prev, idx]
    );
  };

  const subtotal = pedido.reduce((acc, idx) => acc + PLATOS[idx].precio, 0);

  const enviarPedido = () => {
    setEnviado(true);
    setTimeout(() => setEnviado(false), 4000);
    setPedido([]);
  };

  return (
    <div className="max-w-xl w-full bg-white rounded-2xl shadow-lg border border-gpt-blue/10 px-6 py-8 animate-fade-in">
      <h2 className="text-2xl font-bold font-playfair text-gpt-blue mb-4 text-center">
        Elige tu pedido
      </h2>
      <ul className="divide-y">
        {PLATOS.map((plato, idx) => (
          <li
            key={plato.nombre}
            className={`flex gap-2 items-start py-4 cursor-pointer group ${
              pedido.includes(idx) ? "bg-gpt-blue-fog/80" : ""
            } rounded transition-colors`}
            onClick={() => alternarPlato(idx)}
            aria-pressed={pedido.includes(idx)}
            tabIndex={0}
          >
            <span className="mt-1 text-gpt-blue">
              {pedido.includes(idx) ? <CheckCircle className="w-6 h-6 text-gpt-green" /> : <CircleChevronRight className="w-6 h-6 opacity-30" />}
            </span>
            <div>
              <div className="font-semibold text-gray-800">{plato.nombre}</div>
              <div className="text-sm text-gray-500">{plato.desc}</div>
              <div className="font-bold text-gpt-blue mt-1">${plato.precio}</div>
            </div>
          </li>
        ))}
      </ul>

      <div className="mt-7 flex flex-col sm:flex-row sm:items-center justify-between gap-4">
        <div className="text-lg font-bold text-gpt-blue">
          Total: ${subtotal}
        </div>
        <Button
          disabled={pedido.length === 0 || enviado}
          onClick={enviarPedido}
          className="px-6 py-2 rounded-full font-bold bg-gpt-blue hover:bg-gpt-cyan text-white shadow transition active:scale-95"
        >
          {enviado ? "¡Pedido enviado!" : "Enviar pedido"}
        </Button>
      </div>
      <p className="mt-4 text-center text-gray-500 text-xs">* Pedido simulado para demo. El Robot IA te lo traería a la mesa 😎</p>
    </div>
  );
}


import React from "react";
import { RestaurantMenu } from "@/components/RestaurantMenu";
import { ArrowLeft } from "lucide-react";
import { Link } from "react-router-dom";

export default function RestaurantePage() {
  return (
    <div className="min-h-screen bg-gpt-blue-fog flex flex-col">
      <header className="flex items-center px-4 py-4 bg-white/70 shadow animate-fade-in">
        <Link to="/" className="flex items-center gap-2 text-gpt-blue font-semibold hover:underline">
          <ArrowLeft className="w-5 h-5" /> Volver a inicio
        </Link>
        <h1 className="text-2xl md:text-3xl font-playfair text-gpt-blue mx-auto font-bold">
          Restaurante Demo · Menú Digital IA 🍽️
        </h1>
      </header>
      <main className="flex-1 flex justify-center items-center px-2 py-10">
        <RestaurantMenu />
      </main>
      <footer className="text-center text-xs text-gray-400 py-8">
        GPT-Bot RD · Demo de restaurante inteligente · 2025
      </footer>
    </div>
  );
}

import { Toaster } from "@/components/ui/toaster";
import { Toaster as Sonner } from "@/components/ui/sonner";
import { TooltipProvider } from "@/components/ui/tooltip";
import { QueryClient, QueryClientProvider } from "@tanstack/react-query";
import { BrowserRouter, Routes, Route } from "react-router-dom";
import Index from "./pages/Index";
import NotFound from "./pages/NotFound";
import RestaurantePage from "./pages/Restaurante";

const queryClient = new QueryClient();

const App = () => (
  <QueryClientProvider client={queryClient}>
    <TooltipProvider>
      <Toaster />
      <Sonner />
      <BrowserRouter>
        <Routes>
          <Route path="/" element={<Index />} />
          <Route path="/restaurante" element={<RestaurantePage />} />
          {/* ADD ALL CUSTOM ROUTES ABOVE THE CATCH-ALL "*" ROUTE */}
          <Route path="*" element={<NotFound />} />
        </Routes>
      </BrowserRouter>
    </TooltipProvider>
  </QueryClientProvider>
);

export default App;
// Landing page para GPT-Bot RD

import React from "react";
import LandingHero from "@/components/LandingHero";
import FeaturesSection from "@/components/FeaturesSection";
import ObjectivesSection from "@/components/ObjectivesSection";
import ApplicationsSection from "@/components/ApplicationsSection";
import DevelopmentTimeline from "@/components/DevelopmentTimeline";
import ContactForm from "@/components/ContactForm";
import { Link } from "react-router-dom";

const Index = () => {
  return (
    <div className="bg-background w-full min-h-screen flex flex-col">
      <nav className="w-full flex justify-end px-6 pt-6">
        <Link
          to="/restaurante"
          className="px-5 py-2 bg-gpt-blue text-white text-sm font-bold rounded-full shadow hover:bg-gpt-cyan transition hover:scale-105 animate-fade-in"
        >
          Demo Restaurante IA
        </Link>
      </nav>
      <LandingHero />
      <FeaturesSection />
      <ObjectivesSection />
      <ApplicationsSection />
      <DevelopmentTimeline />
      <ContactForm />
      <footer className="text-center text-xs text-gray-400 py-8 mt-auto">
        GPT-Bot RD · Un proyecto de innovación – Ángel Manuel Díaz Batista | ITLA · 2025
      </footer>
    </div>
  );
};

export default Index;
