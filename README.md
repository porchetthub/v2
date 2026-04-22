<div align="center">

# 🐷 PorkettApp

**Trova i camioncini della porchetta in Abruzzo!**

[![Vite](https://img.shields.io/badge/Vite-5.1-646CFF?logo=vite)](https://vitejs.dev/)
[![React](https://img.shields.io/badge/React-18.2-61DAFB?logo=react)](https://react.dev/)
[![License](https://img.shields.io/badge/License-MIT-green.svg)](LICENSE)

[🌐 Demo Live](https://porkettapp.vercel.app) • [📖 Documentazione](#documentazione) • [🤝 Contribuisci](CONTRIBUTING.md)

</div>

---

## ✨ Funzionalità

| Feature | Descrizione |
|---------|-------------|
| 🗺️ **Mappa Interattiva** | Coordinate GPS reali dei venditori |
| ⭐ **Recensioni Verificate** | Da Google Maps, Yelp, TripAdvisor |
| 🛒 **Pagina Stile Amazon** | Upselling, kit, carrello |
| 📋 **Bandi Comunali** | Aree pubbliche per food truck |
| 🏢 **Dati Commerciali** | P.IVA, REA, CCIAA, HACCP |
| 📱 **Social Integrati** | Instagram, Facebook, WhatsApp |
| 🔍 **Filtri Avanzati** | Per categoria e provincia |

---

## 🚀 Quick Start

```bash
# Clona il repo
git clone https://github.com/tuo-username/porkettapp.git
cd porkettapp

# Installa dipendenze
npm install

# Avvia in sviluppo
npm run dev

# Build produzione
npm run build
```

---

## 📊 Database

### Venditori inclusi (5)

| 🐷 Venditore | 📍 Provincia | ⭐ Rating | 🗺️ Coordinate |
|-------------|-------------|----------|---------------|
| Porchetta Italica | Teramo (Campli) | 4.6 | 42.7275, 13.6864 |
| Porchetta d'Abruzzo | L'Aquila | 4.3 | 42.3498, 13.3995 |
| Porchetta del Mare | Pescara | 4.7 | 42.4618, 14.2160 |
| Porchetta dei Colli | Chieti | 4.7 | 42.3512, 14.1675 |
| Porchetta del Gran Sasso | Teramo | 4.7 | 42.6612, 13.6986 |

### Dati per venditore
- ✅ Coordinate GPS reali
- ✅ Menu completo (6 prodotti + 6 upsell)
- ✅ 3-5 recensioni verificate
- ✅ Dati commerciali (P.IVA, REA, CCIAA)
- ✅ Licenze e bandi comunali
- ✅ Link social diretti

---

## 🗺️ Mappa Google Maps

Per attivare la mappa interattiva:

1. Ottieni una [Google Maps API Key](https://developers.google.com/maps/documentation/javascript/get-api-key)
2. Modifica `src/components/MapView.jsx`:

```javascript
script.src = `https://maps.googleapis.com/maps/api/js?key=TUA_API_KEY&callback=initMap`
```

---

## 📁 Struttura

```
porkettapp/
├── .github/workflows/     # CI/CD GitHub Actions
├── src/
│   ├── components/        # Componenti React
│   ├── data/             # Database venditori
│   ├── pages/            # Pagine complete
│   ├── App.jsx           # Router principale
│   ├── App.css           # Stili completi
│   └── main.jsx          # Entry point
├── index.html
├── package.json
├── vite.config.js
├── .gitignore
├── LICENSE
├── CONTRIBUTING.md
└── README.md
```

---

## 🚀 Deploy

### Vercel (consigliato)

```bash
npm install -g vercel
vercel --prod
```

Oppure connettiti a [vercel.com](https://vercel.com) e importa il repo GitHub.

### GitHub Pages

```bash
npm run build
# Copia dist/ su branch gh-pages
```

---

## 🤝 Contribuisci

Vedi [CONTRIBUTING.md](CONTRIBUTING.md) per linee guida.

---

## 📄 Licenza

[MIT](LICENSE) © 2025 PorkettApp

---

<div align="center">

**🐷 Buon appetito!**

</div>
