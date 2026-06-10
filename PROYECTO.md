# Portfolio Sebastian Delgado — Estado del Proyecto

## Info general
- **Repo GitHub:** `s3ba1999/seba-portfolio`
- **Deploy Vercel:** https://sebastian-delgado.vercel.app
- **Knockout site Vercel:** https://knockout-gym.vercel.app
- **Stack:** HTML estático + Tailwind CDN + Vanilla JS
- **Archivos principales:** `index.html`, `condaty.html`, `pipebolagro.html`, `knockout.html`

---

## Puntuación actual: ~84/100

### Historial de puntuación
- Inicio de sesión: 58/100
- Tras mejoras de sesión: ~84/100

---

## Lo que se completó en esta sesión

### index.html
- [x] Hero limpio: eliminado video de fondo, foto Pexels y orb purple. Solo dot-grid + 2 orbs (cyan + blue)
- [x] Marquee de herramientas eliminado (era redundante)
- [x] Hero card derecha: avatar "S" reemplazado por foto real `img/sebas.jpg`
- [x] Hero card: skill bars con % eliminadas → reemplazadas por lista de proyectos recientes
- [x] Badge "Top Rated" eliminado
- [x] Badge "Freelance" → "Full-time · Freelance"
- [x] Botón CV → Google Drive: https://drive.google.com/drive/folders/13Ia9wAGQMgnOYzqhM-0kMrQlsxJBypPu
- [x] Email actualizado: `jsdelgadovasquez99@gmail.com` en todo el sitio
- [x] Email en mobile muestra "Escribir mensaje" (texto corto)
- [x] Narrativas de proyectos reescritas con hook de problema real
- [x] Knockout: narrativa incluye páginas de campeones WAKO + soporte ES/PT/EN
- [x] Sección Testimonial agregada (María Fernanda Rojas, Condaty, mención Mencargo)
- [x] Sección "Cómo trabajo" personalizada con anécdotas reales:
  - Descubrir: Pipebolagro (credibilidad internacional) + Condaty (2 semanas antes de Figma)
  - Diseñar: guardia con guantes como ejemplo UX real
  - Desarrollar: ingeniería = mismo idioma que devs
  - Iterar: Pipebolagro como cierre narrativo
- [x] Sección Credenciales en About (4 certs verificables):
  - Diseño UI: Visual + Figma 2026 (Udemy) → link verificación
  - Diseño UX: UX/UI + Figma 2023 (Udemy) → link verificación
  - Product Management Fundamentals (Coursera) → link verificación
  - Google AI Specialization (Google/Coursera) → link verificación
- [x] Foto About: `object-position: center 15%` para mostrar rostro y cuerpo
- [x] i18n ES/EN completo en todos los elementos nuevos

### condaty.html
- [x] "Lead Product Designer" corregido a "Product Designer"
- [x] Sección "Mi proceso en Condaty" agregada (4 pasos narrativos, bilingüe):
  - Descubrir: auditar diseño anterior + entrevistas + heurísticas + benchmarking
  - Diseñar: papel primero, wireframes a mano, hi-fi con design system
  - Entregar: design system documentado, specs reales para devs
  - Iterar: campañas, eventos, App Store/Play Store assets
- [x] Todos los em-dashes "—" reemplazados por ":", "." o "," en textos visibles

### pipebolagro.html
- [x] Sección "Mi proceso en Pipebolagro" (4 pasos narrativos, bilingüe):
  - Entender el problema: contactos internacionales sin presencia digital
  - Construir la identidad: logo, paleta, dominio, hosting, correos corporativos
  - Diseñar y prototipar: Figma, arquitectura de info, foco conversión B2B
  - Desarrollar y publicar: HTML5/Tailwind, responsive, pipebolagro.com
- [x] comp-card ::before fix: overflow:hidden para que no desborde esquinas
- [x] Screenshots hi-fi: carrusel de 5 slides (Home/Productos/Servicios/Nosotros/Contacto)
- [x] Wireframes: 2 tabs (Escritorio/Móvil) cada una con carrusel de 5 slides
  - Imágenes en `img/Pipebol/`: iniciopc/pm, serviciopc/pm, productopc/pm, aboutpc/pm, contactopc/pm
  - Imágenes hi-fi en `img/Pipebol/`: pipeindex, pipeproduct, pipeservicios, pipeabout, pipecontact
- [x] Logo hero linkea a https://www.pipebolagro.com/ (sin texto "en producción")
- [x] Proceso: fondo oscuro directo en `<section>` para garantizar visibilidad en light mode
- [x] Texto del proceso: `text-white` puro (visible en cualquier modo)

### knockout.html
- [x] Sección "Mi proceso en Knockout" (4 pasos, bilingüe):
  - El contexto como ventaja: 4 años entrenando ahí (Kickboxing + MMA)
  - La propuesta: campeones WAKO, páginas individuales, timeline de carrera
  - Alcance internacional: ES/PT/EN
  - Estado actual: en negociación, badge "Proyecto en curso" animado

---

## Archivos de imagen en el repo

```
img/
├── sebas.jpg           ← foto perfil (usada en hero card + About)
├── Pipebol/
│   ├── pipeindex.png   ← hi-fi Home
│   ├── pipeproduct.png ← hi-fi Productos
│   ├── pipeservicios.png
│   ├── pipeabout.png
│   ├── pipecontact.png
│   ├── iniciopc.png / iniciopm.png     ← wireframes
│   ├── serviciopc.png / serviciopm.png
│   ├── productopc.png / productopm.jpg
│   ├── aboutpc.png / aboutpm.png
│   └── contactopc.png / contactopm.png
├── Knockout/
│   ├── hero.jpg
│   └── logo-knock.png
└── [condaty images: admindash, guardiadash, residendash, flows, etc.]
```

---

## Pendientes para llegar a 90+

| Prioridad | Tarea | Impacto | Notas |
|---|---|---|---|
| 🔴 Alta | Wireframes visuales en Condaty | +5 pts | Sebastian los hace (papel/Figma), yo los integro |
| 🔴 Alta | 4to proyecto real y completo | +5 pts | Futuro |
| 🟡 Media | Email con dominio propio | +2 pts | ej: hola@sebastiandelgado.com (~$12/año) |
| 🟡 Media | Contextualizar flujos de Condaty como proceso visual | +3 pts | Ya existen: residenflow.png, adminflow.png, guardiaflow.png |
| 🟡 Media | Agregar Dribbble | +1 pt | Crear cuenta y linkear |
| 🟢 Baja | Metodología detrás de métricas de Condaty | +1 pt | Explicar cómo se midió el 30% y los 390 usuarios |
| 🟢 Baja | Simplificar About en mobile | +1 pt | Demasiado scroll en pantallas pequeñas |

### Tarea próxima más impactante:
**Contextualizar los flujos de Condaty** — los archivos ya están (`residenflow.png`, `adminflow.png`, `guardiaflow.png`). Solo falta agregarlos visualmente en condaty.html con una sección de "Arquitectura de flujos" que muestre los 3 user journeys con caption explicativo. Yo lo puedo hacer sin que Sebastian prepare nada.

---

## Notas técnicas importantes
- Carruseles: función `carGo(id, n)` + `carState{}` en pipebolagro.html. Swipe touch incluido.
- Lightbox: `e.target.closest('[data-lb]')` — el atributo data-lb en el elemento o su padre activa el lightbox
- i18n: sistema T.es / T.en con `data-i18n` en HTML. Siempre actualizar ambos bloques.
- Em-dashes "—": NO usar en textos visibles (parecen generados por IA). Usar ":", ".", "," según contexto.
- `overflow:hidden` en secciones con fondo absoluto puede fallar en light mode → siempre poner el background directamente en el `<section>`
- Imágenes nuevas: siempre hacer `git add img/carpeta/` antes del commit o Vercel no las despliega
