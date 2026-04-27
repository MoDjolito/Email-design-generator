# Email Prompt Generator

Générateur de prompts optimisés pour créer des sections email en image (Midjourney, DALL·E, Ideogram, Adobe Firefly).

## 🚀 Déploiement sur Vercel

### Option 1 — Via GitHub (recommandé)

1. Push ce dossier sur un repo GitHub
2. Va sur [vercel.com](https://vercel.com) → **Add New Project**
3. Importe ton repo GitHub
4. Vercel détecte automatiquement Vite → clique **Deploy**
5. C'est en ligne ✅

### Option 2 — Via Vercel CLI

```bash
npm install -g vercel
npm install
vercel
```

## 💻 Développement local

```bash
npm install
npm run dev
```

Ouvre [http://localhost:5173](http://localhost:5173)

## 🏗️ Build de production

```bash
npm run build
npm run preview
```

## 📁 Structure

```
email-prompt-generator/
├── index.html          # Point d'entrée HTML (fonts Google chargées ici)
├── vite.config.js      # Config Vite
├── package.json
├── public/
│   └── favicon.svg
└── src/
    ├── main.jsx        # Entrée React
    └── App.jsx         # Composant principal
```

