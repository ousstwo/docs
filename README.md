# Espace de documentation

Ce dépôt contient la documentation de qcmprepa. Les pages `*.mdx` sont prêtes à être éditées pour refléter votre contenu.

## Prévisualisation locale

1. Installez la [CLI Mintlify](https://www.npmjs.com/package/mint) : `npm i -g mint`
2. Depuis le dossier contenant `docs.json`, lancez : `mint dev`
3. Ouvrez `http://localhost:3000` pour voir vos modifications en direct.

## Ajouter du contenu

- Les pages se trouvent au même niveau que `docs.json` (par exemple `index.mdx`, `quickstart.mdx`, `development.mdx`).
- Mettez à jour la navigation et le branding dans `docs.json` pour refléter votre produit.
- Ajoutez ou supprimez des fichiers MDX selon vos besoins ; gardez `navigation.tabs` synchronisé.

## Déploiement

Poussez vos changements sur la branche par défaut et déployez avec votre solution d’hébergement. Si vous utilisez l’app GitHub Mintlify, les déploiements suivent votre workflow Git automatiquement.
