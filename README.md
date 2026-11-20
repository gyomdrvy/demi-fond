# EPS Régularité

Application React/Vite de chronométrage de courses EPS sur boucles de 200 m.

## Démarrage

```bash
npm install
npm run dev
```

## Production / GitHub Pages

```bash
npm run build
```

Pour GitHub Pages, créer le dépôt `eps-regularite`, puis définir `base: '/eps-regularite/'` dans `vite.config.js` (déjà prévu). Publier `dist` avec GitHub Actions ou un hébergeur statique.

## Fonctionnalités

- Import Excel des élèves (Nom, Prénom, Groupe, Vitesse12, Vitesse6)
- Classes et séances enregistrées dans le navigateur
- Courses de 6 à 12 min, groupes A et B
- Pointage des tours 200 m en mode cartes ou liste
- Signal sonore à la fin, repères finaux par 25 m
- Vitesses par tour, comparaison avec projet, bilan et export Excel

**Important :** les données sont stockées dans le navigateur ; sauvegardez régulièrement les exports. L'application doit rester ouverte au premier plan pour chronométrer de façon fiable.
