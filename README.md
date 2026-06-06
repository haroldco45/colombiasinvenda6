# Colombia Sin Venda — Día 6: Las Tomas que Arrasaron Pueblos 🔥
## Con IA Conversacional + Voz

**Reto 20 días · Colombia Sin Venda**
App PWA de conciencia social para jóvenes del Bajo Cauca — con chat de voz integrado.

## Estructura

```
/
├── index.html              # App completa con chat flotante de voz
├── netlify.toml            # Config Netlify
├── netlify/
│   └── functions/
│       └── chat.js         # Proxy seguro a Anthropic API
└── README.md
```

## Deploy en Netlify

1. Conectar repo en netlify.com
2. Site configuration → Environment variables:
   - `ANTHROPIC_API_KEY` = tu clave de Anthropic
3. Deploy ✅

## Tecnologías

- HTML/CSS/JS vanilla
- Netlify Functions (proxy de API)
- Web Speech API (micrófono + TTS)
- Claude Sonnet (Anthropic) como motor de IA

---

Desarrollada por **Vibras Positivas HM** — Derechos de Autor Reservados
Harold Augusto Marín Machado · Caucasia, Antioquia, Colombia
