# SehatBridge AI

**From patient language to doctor-ready information.**

SehatBridge is a healthcare hackathon MVP that helps people describe health concerns in English, Urdu, or Roman Urdu, organizes the information, performs conservative warning-sign screening, and generates a structured handoff summary for a healthcare professional.

## MVP
- English / Urdu / Roman Urdu patient input
- Warning-sign screening: routine / attention / urgent
- Symptom extraction
- Doctor handoff summary
- Downloadable summary
- Responsive hackathon UI
- Clear non-diagnostic safety boundary

## Run
```bash
npm install
npm run dev
```

## Build
```bash
npm run build
```

The current MVP uses local rules so the demo runs without API keys. A future version can connect FastAPI + an LLM with structured output and a clinical safety layer.

## Safety
This is not a diagnostic tool and does not replace a qualified clinician. For emergency warning signs, users should seek urgent professional care.
