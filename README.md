# SBÉ Institut Dermo-Capillaire — Site web

Site vitrine d'institut dermo-capillaire bâti avec [Astro](https://astro.build).

## Structure

```
src/
├── pages/          → Pages du site (index, services, a-propos, etc.)
├── components/     → Composants réutilisables (Header, Footer, Logo)
├── layouts/        → Layout de base (BaseLayout)
└── styles/         → CSS global
```

## Développement local

```bash
npm install
npm run dev
```

Le site sera accessible sur `http://localhost:4321`

## Déploiement

Le site est déployé automatiquement sur Vercel à chaque push sur la branche `main`.

## À configurer après le lancement

- [ ] Remplacer le lien Square dans `/src/pages/reservation.astro` (ligne avec `book.squareup.com`)
- [ ] Remplir l'adresse exacte dans `/src/components/Footer.astro` et `/src/pages/contact.astro`
- [ ] Ajouter le téléphone réel
- [ ] Ajouter les heures d'ouverture dans `/src/pages/contact.astro`
- [ ] Remplacer les placeholders [À configurer]
- [ ] Ajouter Google Analytics (optionnel)
- [ ] Configurer Google Business Profile (séparé du site)

## Couleurs

- Vert émeraude principal : `#276556`
- Vert forêt (accents) : `#004B23`
- Brun cacao : `#432818`
- Brun rustique : `#7A4419`
- Noir : `#000000`
- Crème : `#f5f1ea`

## Polices

- Titres : Cormorant Garamond (serif)
- Corps : Inter (sans-serif)
