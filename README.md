# NourAI — Site Officiel

Site officiel de NourAI, l'assistante IA de prise de rendez-vous.

## 🌐 Site en ligne
[nourai.site](https://nourai.site)

## 📁 Structure
```
nourai-site/
├── index.html        # Page principale
├── _redirects        # Redirections Netlify/Cloudflare
├── _headers          # Headers de sécurité
├── README.md         # Documentation
└── .github/
    └── workflows/
        └── deploy.yml  # Auto-deploy GitHub Actions
```

## 🚀 Déploiement

### Netlify
1. Connecte ton repo GitHub sur app.netlify.com
2. Branch: `main`, Build command: vide, Publish directory: `.`
3. Chaque push sur `main` déploie automatiquement

### Cloudflare Pages
1. Connecte ton repo sur dash.cloudflare.com → Pages
2. Branch: `main`, Build command: vide, Output directory: `.`
3. Ajoute les secrets: `CLOUDFLARE_API_TOKEN` et `CLOUDFLARE_ACCOUNT_ID`

## 📧 Contact
contact@nourai.site
