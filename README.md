# LibreIncu — Sitio Web Oficial

Sitio web oficial del proyecto **LibreIncu**, una iniciativa de soberanía tecnológica y alimentaria desarrollada colaborativamente por [AlterMundi](https://altermundi.net) y la [Comunidad, Trabajo y Organización (CTO)](https://www.facebook.com/comunidadtrabajoorganizacion), junto con organizaciones de la Agricultura Familiar, Campesina e Indígena (AFCI) de Córdoba, Argentina.

---

## ¿Qué es LibreIncu?

LibreIncu es una incubadora avícola con tecnología de monitoreo y control en línea, diseñada específicamente para las necesidades de la AFCI. Su objetivo es romper la **triple dependencia** que enfrenta la producción avícola familiar:

1. **Genética** — El oligopolio mundial del pollito bebé híbrido (Cobb-Vantress / Aviagem)
2. **Alimentaria** — La dieta industrial basada en insumos del agronegocio
3. **Tecnológica** — Incubadoras comerciales inaccesibles o diseñadas para hobbistas

---

## Tecnología

| Tecnología | Versión |
|---|---|
| [Next.js](https://nextjs.org) | 14.2.5 |
| [React](https://react.dev) | 18 |
| [TypeScript](https://www.typescriptlang.org) | 5 |
| [Tailwind CSS](https://tailwindcss.com) | 3 |
| [Lucide React](https://lucide.dev) | latest |

---

## Secciones del sitio

| Ruta | Descripción |
|---|---|
| `/` | Inicio — presentación del proyecto, características y acceso rápido |
| `/nosotros` | Sobre el proyecto — origen, triple dependencia, prensa y difusión |
| `/app-movil` | Demo interactivo de la aplicación Android |
| `/aplicacion` | Manual de Usuario de la app LibrePollo |
| `/manual` | Manual de armado de la incubadora |
| `/especificaciones` | Material técnico — hardware, firmware y software |
| `/ecosistema` | Ecosistema tecnológico e IoT |
| `/huevos` | Guía de recolección, selección e incubación de huevos |
| `/buenas-practicas` | Buenas prácticas de manejo avícola |
| `/solucion-problemas` | Solución de problemas comunes |
| `/impacto` | Avances y registro de impacto territorial |
| `/contacto` | Canales de comunicación y redes sociales |
| `/cto` | Comunidad, Trabajo y Organización (CTO) |

---

## Paleta de colores

El sitio usa una paleta de marca propia definida en `tailwind.config.js`:

```
lp-yellow      #F5C518   (amarillo principal)
lp-yellowLight #F7D04E   (amarillo claro)
lp-yellowDark  #C9A010   (amarillo oscuro)
lp-gray        #E5E5E5   (gris claro)
lp-grayDark    #6B6B6B   (gris oscuro)
lp-black       #1A1A1A   (negro)
lp-white       #FAFAFA   (blanco)
```

---

## Desarrollo local

```bash
# Clonar el repositorio
git clone https://github.com/SairaAsua/libreIncu-web.git
cd libreIncu-web

# Instalar dependencias
npm install

# Iniciar servidor de desarrollo
npm run dev
```

El sitio estará disponible en `http://localhost:3000`.

```bash
# Build de producción
npm run build
npm start
```

---

## Estructura del proyecto

```
src/
├── app/                    # Páginas (App Router de Next.js)
│   ├── page.tsx            # Inicio
│   ├── nosotros/
│   ├── app-movil/
│   ├── aplicacion/
│   ├── manual/
│   ├── ecosistema/
│   ├── especificaciones/
│   ├── huevos/
│   ├── buenas-practicas/
│   ├── solucion-problemas/
│   ├── impacto/
│   ├── contacto/
│   └── cto/
├── components/             # Componentes reutilizables
│   ├── Navigation.tsx
│   ├── Footer.tsx
│   ├── AppDemo.tsx         # Demo interactivo de la app (client component)
│   └── PageHeader.tsx
public/
└── images/                 # Imágenes del proyecto
```

---

## Licencia

Este proyecto es software libre. Podés usarlo, modificarlo y distribuirlo bajo los términos de la licencia [Creative Commons Attribution-ShareAlike 4.0](https://creativecommons.org/licenses/by-sa/4.0/).

---

Desarrollado con amor por **AlterMundi** y **CTO** para las comunidades campesinas e indígenas de Córdoba.
