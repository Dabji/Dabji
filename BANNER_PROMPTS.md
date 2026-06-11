# 🎨 Prompts para el Banner del Perfil

**Concepto:** Un banner oscuro-minimalista con acentos cian/violeta (paleta *Tokyo Night*, igual que las tarjetas de estadísticas del README), que comunique "ingeniero full-stack en formación, código limpio y arquitectura".

**Especificaciones técnicas:**
- Relación de aspecto: **3:1** (recomendado: 1500 × 500 px o superior)
- Paleta: fondo `#0d1117` / `#1a1b27`, acentos `#7aa2f7` (azul), `#bb9af7` (violeta), `#c0caf5` (texto)
- Una vez generado, guárdalo como `assets/banner.png` y reemplaza el bloque `capsule-render` al inicio del README por:
  ```html
  <img src="assets/banner.png" alt="Banner" width="100%" />
  ```

---

## Prompt 1 — Minimalista oscuro con circuito de código (Midjourney)

```
Ultra-wide minimalist developer banner, deep dark navy background hex 0d1117,
elegant glowing circuit board traces flowing horizontally like data streams,
soft cyan hex 7aa2f7 and violet hex bb9af7 neon accents, subtle floating code
symbols and brackets dissolving into particles, clean negative space in the
center-left for text overlay, flat modern vector aesthetic, premium tech
branding style, no people, no text, cinematic soft glow, high detail
--ar 3:1 --v 6 --style raw --no text, words, letters, watermark
```

**Uso en DALL-E 3:** "A 3:1 ultra-wide minimalist tech banner: deep dark navy background (#0d1117) with elegant glowing circuit-board traces flowing horizontally like data streams, soft cyan (#7aa2f7) and violet (#bb9af7) neon accents, subtle floating code brackets dissolving into light particles, generous empty space on the left for future text, flat modern vector style, no text or letters anywhere."

---

## Prompt 2 — Cyberpunk sutil: skyline + terminal (Midjourney)

```
Wide cinematic banner of a stylized night city skyline silhouette at the bottom
edge, viewed through a translucent terminal window with glowing command-line
glyphs, dark background gradient from hex 0d1117 to hex 1a1b27, neon rim
lighting in cyan hex 7aa2f7 and purple hex bb9af7, faint grid horizon,
low-poly geometric style mixed with glassmorphism, moody but clean, professional
developer portfolio aesthetic, no people, no readable text
--ar 3:1 --v 6 --style raw --no text, words, letters, watermark, logo
```

**Uso en DALL-E 3:** "A 3:1 cinematic developer banner: stylized low-poly night city skyline silhouette along the bottom, seen through a translucent glassmorphism terminal window with abstract glowing glyphs, dark gradient background from #0d1117 to #1a1b27, neon rim lighting in cyan (#7aa2f7) and purple (#bb9af7), faint perspective grid on the horizon, moody but clean professional aesthetic, absolutely no readable text."

---

## Prompt 3 — Arquitectura abstracta: nodos y grafos (Midjourney)

> Guiño a RailLink y a las estructuras de datos hechas desde cero 🚂

```
Abstract wide banner of an elegant graph network: luminous nodes connected by
smooth bezier edges forming a constellation that subtly resembles a railway
map, dark charcoal background hex 0d1117, nodes glowing in gradient from cyan
hex 7aa2f7 to violet hex bb9af7, one highlighted shortest-path route in brighter
light, depth of field, soft bokeh particles, minimal flat design with subtle 3D
depth, scientific elegance, premium fintech branding mood, no text
--ar 3:1 --v 6 --style raw --no text, words, letters, watermark, people
```

**Uso en DALL-E 3:** "A 3:1 abstract banner of an elegant graph network: luminous nodes connected by smooth curved edges forming a constellation that subtly resembles a railway map, dark charcoal background (#0d1117), nodes glowing in a cyan (#7aa2f7) to violet (#bb9af7) gradient, one shortest-path route highlighted brighter than the rest, soft bokeh particles and gentle depth of field, minimal flat design with subtle 3D depth, no text or letters."

---

## 💡 Consejos

1. **Midjourney:** genera 4 variantes con cada prompt, haz *upscale* de la mejor y usa `--ar 3:1` siempre (GitHub recorta banners no panorámicos).
2. **Texto:** pide la imagen **sin texto** y agrega tu nombre después en Figma/Canva — la IA suele deformar las letras.
3. **Peso:** exporta a PNG < 1 MB (o WebP) para que el perfil cargue rápido.
4. **Coherencia:** los tres prompts usan la misma paleta Tokyo Night del README, así el perfil se ve diseñado como un todo.
