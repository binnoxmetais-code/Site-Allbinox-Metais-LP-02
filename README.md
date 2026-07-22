# ALLBINOX METAIS — Site Institucional

Site imersivo B2B da **ALLBINOX METAIS** — indústria nacional de lixeiras e utilitários em aço inox (Suzano/SP).

**A força do inox em cada detalhe.**

## Sobre

Página única (`index.html`) 100% estática, com:

- Tipografia editorial monumental (Fraunces + Space Grotesk) com acabamento cromo e violeta
- Animações de scroll cinematográficas (GSAP + ScrollTrigger + Lenis + SplitType, via CDN)
- Vitrine de produtos filtrável por categoria (Lixeiras Inox, Coleta Seletiva, Bituqueiras, Utilitários)
- Seletor de segmentos B2B (Revendas, Facilities, Hotelaria, Saúde, Indústria)
- Formulário de orçamento expresso integrado ao WhatsApp comercial
- Fotos reais de produtos em `assets/`

## Rodar localmente

Basta abrir o `index.html` no navegador, ou servir a pasta:

```bash
npx http-server . -p 8123
```

## Deploy (Vercel)

Projeto estático, sem build:

- **Framework Preset:** Other
- **Build Command:** (vazio)
- **Output Directory:** `./`

---

© ALLBINOX METAIS. Todos os direitos reservados.
