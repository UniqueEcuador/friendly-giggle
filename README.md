# friendly-giggle
# 🧭 Forward Juntos — Framer Upgrade Toolkit

> Modulaire stappenplannen om forwardjuntos.nl en forwardjuntos.eu interactiever te maken via Framer.  
> Ontworpen voor gebruik op telefoon én desktop. Elke module staat op zichzelf en is later uitbreidbaar.

---

## 🚀 Direct starten

| Wat | Link |
|-----|------|
| 📱 **Interactief stappenplan (telefoon)** | Open `index.html` via GitHub Pages |
| 🖥️ **Desktop dashboard** | Open `dashboard.html` in je browser |
| ➕ **Nieuwe module toevoegen** | Zie [Module toevoegen](#-nieuwe-module-toevoegen) |

---

## 📁 Structuur

```
forwardjuntos-framer-toolkit/
│
├── index.html              ← Mobiel stappenplan (start hier op je telefoon)
├── dashboard.html          ← Desktop overzicht met alle modules en links
│
├── modules/
│   ├── 01-interacties.html     ← Scroll-triggers & animaties
│   ├── 02-ai-generator.html    ← Framer AI pagina-generator
│   ├── 03-cms-localisatie.html ← CMS voor NL + EU
│   ├── 04-ab-testing.html      ← A/B-testing setup
│   ├── 05-seo-performance.html ← SEO & Lighthouse
│   └── 06-marketplace.html     ← Marketplace componenten
│
├── assets/
│   └── fj-style.css        ← Gedeelde stijlen (Forward Juntos huisstijl)
│
└── README.md               ← Dit bestand
```

---

## 📱 Gebruik op je telefoon

1. Ga naar je GitHub repository → klik op **Settings → Pages**
2. Zet source op `main` branch, map `/root`
3. Je URL wordt: `https://[jouwgebruikersnaam].github.io/forwardjuntos-framer-toolkit/`
4. Voeg die URL toe aan je telefoon als **bladwijzer op je beginscherm**

Op je telefoon open je `index.html` — dat is je interactief doorloopbaar stappenplan.

---

## 🖥️ Gebruik op desktop

Open `dashboard.html` — daar staan alle modules met directe links naar Framer en je eigen sites.

---

## ➕ Nieuwe module toevoegen

1. Kopieer een bestaand modulebestand, bijv. `modules/06-marketplace.html`
2. Hernoem naar `modules/07-[jouw-module].html`
3. Pas de inhoud aan (zie het sjabloon onderaan elk modulebestand)
4. Voeg de module toe aan `index.html` en `dashboard.html` (zoek naar `<!-- MODULES -->`)

Dat is alles. Geen build-tools, geen npm — gewoon HTML-bestanden openen en aanpassen.

---

## 🌐 Directe links

| Site | Link |
|------|------|
| forwardjuntos.nl | https://forwardjuntos.nl |
| forwardjuntos.eu | https://forwardjuntos.eu |
| Framer inloggen | https://framer.com/r/login |
| Framer AI | https://framer.com/ai |
| Framer CMS | https://framer.com/cms |
| Framer Marketplace | https://framer.com/marketplace |
| Framer Analytics | https://framer.com/analytics |
| Framer Templates | https://framer.com/marketplace/templates |

---

## 📝 Licentie
