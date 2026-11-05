# Récitation du Coran — PWA personnelle

## Installation sur iPhone
1. Mets les fichiers du dossier sur un hébergement HTTPS gratuit : GitHub Pages, Netlify, Vercel ou Cloudflare Pages.
2. Ouvre l’URL dans **Safari** sur iPhone.
3. Appuie sur **Partager** → **Sur l’écran d’accueil** → **Ajouter**.
4. L’app s’ouvre en plein écran depuis l’icône, sans App Store.

## Fonctionnalités
- Sourates Al-Fatiha, Al-Ikhlas, Al-Falaq et An-Nas incluses.
- Reconnaissance vocale arabe via Safari/Web Speech.
- Comparaison mot à mot avec le verset affiché.
- Surlignage des mots manquants ou différents.
- Score de correspondance.
- Mode mémorisation : masque le verset arabe.
- Progression sauvegardée localement sur l’iPhone.

## Ajouter d’autres sourates
Dans `index.html`, cherche la constante `QURAN` et ajoute un objet :
```js
"2": { name: "Al-Baqarah", ayahs: [ { ar: "...", fr: "..." } ] }
```

## Remarque
La reconnaissance vocale automatique n’est pas une autorité religieuse : elle peut mal transcrire, surtout avec les règles de tajwid. Utilise-la comme aide à la mémorisation, pas comme remplacement d’un enseignant qualifié.
