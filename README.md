# Portfolio – Lionel Ndoizine

Site CV / portfolio personnel, construit avec [Astro](https://astro.build).

🔗 **En ligne :** https://lioneldj24.github.io/CV-Lionel/

Étudiant en 5e année d'école d'ingénieurs à l'ESAIP (Angers), spécialisé en cybersécurité et réseaux, actuellement en Erasmus à l'Universidad Politécnica de Madrid.

## Stack

- **Astro 7** — site 100 % statique, zéro framework JS côté client
- **CSS vanilla** — styles scopés par composant
- **`astro:assets`** — images optimisées (WebP, responsive) au build
- **GitHub Actions** — build et déploiement automatiques sur GitHub Pages à chaque push sur `main`

## Développement

| Commande          | Action                                        |
| :---------------- | :-------------------------------------------- |
| `npm install`     | Installe les dépendances                      |
| `npm run dev`     | Serveur de développement sur `localhost:4321` |
| `npm run build`   | Build de production dans `./dist/`            |
| `npm run preview` | Prévisualisation locale du build              |

## Déploiement

Chaque push sur `main` déclenche le workflow [`.github/workflows/deploy.yml`](.github/workflows/deploy.yml), qui builde le site et le publie sur GitHub Pages. Aucune étape manuelle.

## Mesure d'audience

Google Analytics n'est chargé qu'après consentement explicite du visiteur (bannière conforme RGPD / recommandations CNIL).
