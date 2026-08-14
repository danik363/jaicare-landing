# Su bienestar es tu tranquilidad

### Guion — Video institucional/emocional JaiCARE

**Va en:** Landing B2C, sección "Porque su bienestar es tu tranquilidad"
**Duración:** ~20 segundos
**Reproducción:** Con audio (narración) — no pensado para loop mudo
**Imagen base:** `img/vieja.jpg` (mujer mayor, parque, luz cálida de mañana, reloj JaiCARE real visible en la muñeca)
**Estado:** Por producir (image-to-video + voz en off)

---

## Concepto

Testimonio en primera persona, en voz de la protagonista, sobre lo que significa para ella la independencia que le da el reloj — no un mensaje de venta hacia la familia, sino la mirada de la persona mayor sobre su propia libertad. Un solo plano continuo, animado a partir de la foto real (`vieja.jpg`), con movimiento sutil (viento en el pelo, parpadeo, leve sonrisa, brisa en el fondo) mientras se escucha la narración.

Complementa al video de producto de la sección de arriba: ese muestra el dispositivo, este muestra lo que el dispositivo permite sentir.

---

## Tono y dirección

- **Un plano, cero cortes.** Animación continua a partir de la imagen base, sin edición de montaje.
- **Cámara:** fija o empuje (push-in) muy sutil de principio a fin.
- **Voz en off, no lip-sync.** La protagonista no habla a cámara — no hace falta sincronizar labios. Es narración sobre la imagen, como un testimonio pensado en voz alta.
- **Sin dramatización ni emergencias.** El mensaje es calma y autonomía, no un riesgo resuelto.
- **Dignidad, no fragilidad.** Mirada de disfrute y libertad, no de necesidad de cuidado.
- **El reloj debe quedar legible** — la ventaja de partir de `vieja.jpg` es que el dispositivo real ya está en la foto, así que el generador de video solo tiene que animarlo, no inventarlo. Verificar que la herramienta no lo distorsione en los frames generados.

---

## Plano único · 0:00–0:20

**Descripción:** Mujer mayor de pie en un parque, luz cálida de mañana entrando de costado, árboles de fondo. Sonríe levemente, mirada hacia un costado, reloj JaiCARE visible en la muñeca. Movimiento sutil: brisa que mueve el pelo y las hojas de fondo, parpadeo natural, leve cambio de peso o inclinación de cabeza. Sensación de estar en medio de una caminata tranquila, no posando.

**Cámara:** fija, o push-in muy sutil de principio a fin — nunca paneo ni corte.

---

## Guion de narración (voz en off)

**Voz:** mujer, español rioplatense/argentino, tono cálido, pausado, cercano — no publicitario.
**Duración de lectura:** ~20 segundos a ritmo conversacional.

> "Mis hijos ya no me llaman cada cinco minutos preguntando si estoy bien. Y no es que dejaron de importarles... es que ahora, con solo mirar el reloj, ya lo saben. Yo sigo caminando, tomando sol, viviendo mi vida. Y ellos, tranquilos. Eso, para mí, también es libertad."

(48 palabras — a ritmo pausado entra cómodo en 18-20 segundos)

---

## Prompt sugerido — generación de video (image-to-video)

Para pegar en una herramienta image-to-video (Higgsfield, Runway, Kling, Pika) usando `img/vieja.jpg` como imagen base:

```
Animate this photo of an elderly woman standing in a sunlit park in the
morning. Subtle, natural motion only: gentle breeze moving her hair and
the leaves in the background, natural slow blinking, a soft warm smile
forming, slight relaxed weight shift. Keep the smartwatch on her wrist
fully visible and unchanged — do not redesign or distort it. Camera:
static or an almost imperceptible slow push-in. No cuts, no zoom bursts,
no extra people entering frame. Calm, warm, documentary-style motion,
not cinematic drama. Duration: 20 seconds.
```

## Prompt sugerido — narración (TTS, ej. ElevenLabs)

- **Idioma/acento:** español, voz femenina, acento argentino/rioplatense (buscar voz "Argentina" o similar en la librería de voces).
- **Tono:** cálido, pausado, íntimo — como quien piensa en voz alta, no como locución publicitaria.
- **Texto:** el guion de narración de arriba, tal cual.
- **Nota:** generar el audio por separado y mezclarlo sobre el video animado en edición (no requiere lip-sync porque la protagonista no habla directo a cámara).

---

## Especificaciones técnicas

| | |
|---|---|
| **Duración final** | ~20 segundos |
| **Formato** | MP4, H.264, faststart |
| **Audio** | Narración en off, español argentino, voz femenina |
| **Loop** | No aplica (pieza con narración, no loop mudo) |
| **Aspect ratio** | 4:5 o 1:1 |
| **Imagen base** | `img/vieja.jpg` |

---

## Notas de producción

- **Evitar iconografía clínica** — nada de guardapolvos, hospitales o sillas de ruedas.
- **Paleta:** ya resuelta por la foto base (luz cálida, parque). Si hay margen en la mezcla de color, un acento sutil hacia el celeste (`#00609a`) o verde (`#006d2f`) de marca.
- Verificar en el resultado final que el reloj generado siga siendo reconocible como el reloj real de JaiCARE y no una versión alterada por la IA.

---

*Preparado para GrupoCesa · JaiCARE — 12 de agosto de 2026*
