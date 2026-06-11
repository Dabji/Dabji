# 🎨 DISEÑO_BANNER_GEMINI — Brief completo para generar el banner con Gemini

> **Objetivo:** un banner horizontal **3:1** (mínimo **1500 × 500 px**) para el perfil
> [github.com/Dabji](https://github.com/Dabji), que comunique tu perfil híbrido:
> **Ingeniería de Software × Dirección de Marketing (Severapp) × Edición de Video**.
>
> Cuando lo tengas: guárdalo como `assets/banner.png` y reemplaza el bloque
> `capsule-render` al inicio del `README.md` por
> `<img src="assets/banner.png" alt="Banner" width="100%" />`.

---

## 1. Concepto de diseño: "Tres mundos, un perfil"

Composición horizontal dividida sutilmente en **tres zonas que se funden entre sí**
(sin bordes duros, transiciones con partículas de luz y degradados):

| Zona | Contenido | Simboliza |
|---|---|---|
| **Izquierda (30%)** | Tu retrato recortado, con luz de borde cian/violeta sobre fondo oscuro | La persona |
| **Centro (40%)** | Nombre + tagline sobre espacio negativo limpio | La marca personal |
| **Derecha (30%)** | Collage en marcos *glassmorphism*: UI de RailLink, app de Severapp, línea de tiempo de edición de video | Los tres mundos: código, producto, visuales |

**Paleta obligatoria (Tokyo Night, idéntica al README):**
- Fondo: `#0d1117` → `#1a1b27` (degradado)
- Acento primario: cian `#7aa2f7`
- Acento secundario: violeta `#bb9af7`
- Texto: `#c0caf5`

**Texto a renderizar en el banner** (pídele a Gemini que lo deje legible y sin deformar):
- Línea 1 (grande): `Juan David Ordóñez Ferreira`
- Línea 2 (pequeña): `Full-Stack Developer · CMO @ Severapp · Video & Visuales`

---

## 2. Qué debes adjuntarle TÚ a Gemini en el chat

Para que la fusión sea impecable, adjunta estas imágenes **en este orden** y nómbralas:

### 📸 Foto 1 — Tu rostro (obligatoria)
- **Estilo:** corporativo-tech relajado (camisa o polo, sin traje formal).
- **Encuadre:** del pecho hacia arriba, cuerpo en ligero 3/4 girado hacia la derecha
  (así "mira" hacia el centro del banner), rostro hacia la cámara con sonrisa leve.
- **Fondo:** neutro y liso (pared blanca/gris), Gemini lo eliminará — evita fondos con objetos.
- **Luz:** natural y uniforme sobre la cara, sin sombras duras ni contraluz.
- **Calidad:** la mayor resolución posible, sin filtros ni recortes previos.

### 🖥️ Foto 2 — Captura de RailLink
- Captura de pantalla **completa y nítida** de la interfaz gráfica de RailLink,
  idealmente mostrando el **grafo de rutas / cálculo de ruta más corta** (lo más visual).
- Exporta en resolución nativa, sin comprimir por WhatsApp.

### 📱 Foto 3 — Severapp
- Mockup o captura del app móvil (pantalla principal o marketplace), o en su defecto
  el logo de Severapp en alta resolución + una métrica de crecimiento si quieres presumir.

### 🎬 Foto 4 (opcional) — Edición de video
- Captura de tu línea de tiempo en CapCut con un proyecto real abierto.
  Si no la adjuntas, Gemini representará este mundo con iconografía abstracta de video.

---

## 3. Prompt exacto para pegar en Gemini

Copia esto junto con las imágenes adjuntas:

```
Crea un banner horizontal de relación de aspecto exacta 3:1 (1500x500 px) para mi
perfil de GitHub, estilo premium tech con estética "Tokyo Night".

FONDO: degradado oscuro de #0d1117 a #1a1b27, con trazos sutiles de circuitos y
partículas de luz en cian #7aa2f7 y violeta #bb9af7 fluyendo horizontalmente.

COMPOSICIÓN EN TRES ZONAS QUE SE FUNDEN SUAVEMENTE:

1) IZQUIERDA (30%): usa la FOTO 1 (mi retrato). Recórtame del fondo e intégrame
   con una luz de borde (rim light) cian por un lado y violeta por el otro, estilo
   editorial tech. Que el degradado del fondo me envuelva de forma natural.

2) CENTRO (40%): espacio negativo limpio con este texto perfectamente legible,
   tipografía sans-serif moderna (estilo Inter/Fira Code), color #c0caf5:
   - Línea grande: "Juan David Ordóñez Ferreira"
   - Línea pequeña debajo: "Full-Stack Developer · CMO @ Severapp · Video & Visuales"
   Añade un subrayado o detalle de acento en degradado cian→violeta bajo el nombre.

3) DERECHA (30%): collage flotante de las capturas adjuntas (FOTO 2: RailLink,
   FOTO 3: Severapp, FOTO 4: edición de video) dentro de marcos tipo ventana de
   navegador/teléfono con efecto glassmorphism (vidrio esmerilado, bordes
   luminosos sutiles en cian/violeta), ligeramente rotados y superpuestos en
   profundidad, desvaneciéndose hacia el borde derecho.

REGLAS ESTRICTAS:
- Mantén mi rostro 100% fiel a la foto, sin retoques que lo deformen.
- El único texto del banner es el indicado; nada de texto inventado ni watermarks.
- Sin logos de terceros, sin personas adicionales.
- Estilo limpio, profesional y moderno; nada recargado.
- Entrega final en 3:1 exacto, alta resolución.
```

---

## 4. Mockup conceptual (referencia visual)

```
┌──────────────────────────────────────────────────────────────────────────────┐
│ ▒▒ partículas cian/violeta ▒▒                                    ░ circuitos ░│
│  ╭─────────╮                                                ┌────┐            │
│  │         │     Juan David Ordóñez Ferreira              ┌─┤Rail│─┐          │
│  │ RETRATO │     ━━━━━━━━━━━━━━━ (cian→violeta)           │ │Link│ │ ┌────┐   │
│  │ rim cian│     Full-Stack Developer · CMO @ Severapp    │ └────┘ │ │Seve│   │
│  │ /violeta│     · Video & Visuales                       │ glass  │ │rapp│   │
│  ╰─────────╯                                              └────────┘ └────┘   │
│ fondo #0d1117 ─────────── degradado ─────────── #1a1b27 ── fade derecha ──────│
└──────────────────────────────────────────────────────────────────────────────┘
                              proporción 3:1 (1500 × 500)
```

## 5. Checklist final

- [ ] Verifica que el resultado sea **exactamente 3:1** (Gemini a veces entrega 16:9 → pídele "recorta a 3:1 exacto").
- [ ] Tu nombre debe leerse perfecto: si las letras salen deformadas, pídele que regenere **solo el texto** o añádelo tú en Figma/Canva sobre la versión sin texto.
- [ ] Exporta como **PNG < 1 MB** (o WebP) para carga rápida.
- [ ] Súbelo a `assets/banner.png` y actualiza el README (instrucción al inicio de este archivo).
