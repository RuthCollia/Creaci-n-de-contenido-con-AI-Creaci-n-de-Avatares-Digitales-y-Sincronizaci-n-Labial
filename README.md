# Coberturas Florales — Video Vocero Institucional con IA

**Módulo 4 · Producción Multimedia Unificada (texto + imagen + voz + música)**
Vocero: **Ana** (personaje de marca consistente, definido en Módulo 3)
Plataforma de ensamble: **HeyGen**

> Tagline de marca: *"No vendemos flores. Acompañamos con ellas."*

---

## 1. Objetivo del entregable

Generar una pieza de video-marketing profesional que unifique todos los activos de marca creados en módulos anteriores, integrando voz IA (ElevenLabs/TTS) y música (Suno) sobre el avatar consistente de **Anah** en HeyGen, para una comunicación **institucional general** de Coberturas Florales (ambas líneas: envío a domicilio y florería para cementerio).

## 2. Estructura del repositorio

```
coberturas_florales_video/
├── assets/
│   ├── close-up_portrait_of_a_woman_202607011903.png            # Imagen consistente del personaje (M3)
│   ├── ElevenLabs_2026-07-11T18_30_25_Anah.mp3                  # Audio de voz IA (ElevenLabs / TTS)
│   ├── Petals at Dawn.mp3             # Música de fondo (Suno)
│   ├── guion_ana_institucional.txt  # Guion vocero
│   ├── voz_elevenlabs_prompts.txt   # Config y prompts de voz
│   └── musica_suno_prompt.txt       # Prompt de música
├── output/
│   └── Coberturas_Florales_-_Acompañamos_con_flores_-_v4_with_captions.mp4  # Video final exportado (720p, con marca de agua = válido)
└── README.md
```

## 3. Guion utilizado (~45s)

Voz de Ana, tono cálido y sereno, voseo rioplatense. Ver `assets/guion_ana_institucional.txt`.
El guion abre institucional, diferencia sutilmente las dos líneas de servicio (celebración vs. acompañamiento en el duelo) y cierra con el tagline de marca. Incluye pausas marcadas para gesto/parpadeo del avatar.

## 4. Descripción de la voz

- **Herramienta:** ElevenLabs.
- **Perfil buscado:** mujer ~38 años, timbre medio-cálido, empático, no comercial.
- **Ajustes clave:** Stability 55–65%, Style bajo (15–25%) para calidez natural.
- Detalle completo en `assets/voz_elevenlabs_prompts.txt`.

## 5. Música de marca

- **Herramienta:** Suno (plan gratis, instrumental sin voz).
- **Estilo:** guitarra acústica cálida + piano suave, emotivo y esperanzador, sin percusión fuerte.
- **Crédito:** música generada con Suno — uso no comercial con atribución (trabajo académico).
- Prompt completo en `assets/musica_suno_prompt.txt`.

## 6. Proceso de sincronización en HeyGen

1. **Photo Avatar:** subir `close-up_portrait_of_a_woman_202607011903.png.
2. **Upload Audio:** cargar `ElevenLabs_2026-07-11T18_30_25_Anah.mp3`.
3. **Precision / lip-sync:** activar el modo de precisión disponible para que los visemas coincidan con la dicción.
4. **Música de fondo:** integrar `Petals at Dawn.mp3` al 15–20% de volumen, con fade-in/out de 2s.
5. **Background:** fondo coherente con el manual de identidad visual (M3) — paleta salvia/marfil, cálido y neutro.
6. **Gestos:** aprovechar las pausas del guion para parpadeo y micro-movimientos de cabeza (evita el efecto "avatar inmortal").

## 7. Exportación

- Resolución: **1080p**.
- Formato: MP4.
- Duración: ≤ 1 minuto.
- Guardar en `output/Coberturas_Florales_-_Acompañamos_con_flores_-_v4_with_captions.mp4`.

## 8. Checklist de criterios de aceptación

- [✓] Sincronización labial natural (sin saltos bruscos).
- [✓] Voz generada con IA e integrada al avatar (no grabación humana cruda).
- [✓] Personaje Ana mantiene consistencia visual del M3.
- [✓] Música integrada y nivelada al 15–20%.
- [✓] Audio limpio (sin ruido de fondo → sin vibración de labios).
- [✓] Pausas con gesto/parpadeo insertadas.

---

*Producción académica — Máster en Marketing con IA. Coberturas Florales (negocio real de suscripción floral por WhatsApp).*
