# trente30

Website for the Trente30 app: Instagram bio link, App Store required URLs (privacy policy, support) and legal notice.

Site statique publié avec GitHub Pages (workflow `.github/workflows/pages.yml`, à chaque push sur `main`). Seuls les fichiers `*.html` et `assets/` sont publiés. La source de vérité est le dossier `site/` du dépôt (privé) de l'app : modifier là-bas, puis recopier ici.

| Page | Rôle | URL à déclarer |
| --- | --- | --- |
| `index.html` | Lien en bio Instagram : stores, « gratuit avec achats intégrés », prix | — |
| `confidentialite.html` | Politique de confidentialité (App Store, Google Play, RGPD, accord API Strava) | App Store Connect → *Privacy Policy URL* ; Strava → paramètres de l'app API |
| `support.html` | Contact + FAQ (restaurer les achats, déconnecter Strava…) | App Store Connect → *Support URL* |
| `conditions.html` | Renvoi vers l'EULA standard d'Apple + règles des achats | Optionnel (pas d'abonnement) |
| `mentions-legales.html` | Mentions légales (LCEN, site édité en France) | — |

Les polices sont auto-hébergées (`assets/fonts`, licences OFL incluses) : le site ne charge aucune ressource externe et ne dépose aucun cookie, ce que dit la politique de confidentialité.

## À compléter avant publication

Chaque champ est marqué `[À compléter]` (fond orange) dans les pages.

- [ ] Nom définitif de l'app (le site dit « Trente30 », nom de code).
- [ ] Prix du pack premium (`index.html`).
- [ ] Éditeur : nom ou raison sociale, adresse, SIREN/RCS si société, directeur de publication (`mentions-legales.html`, `confidentialite.html`, pied de page de `index.html`).
- [ ] Adresse e-mail de contact et de support (`confidentialite.html`, `support.html`, `mentions-legales.html`).
- [ ] Dates de mise à jour (`confidentialite.html`, `conditions.html`).
- [ ] Lien App Store + badge officiel Apple ; lien Google Play + badge officiel quand l'app Android existera (`index.html`).
- [ ] Logo officiel « Compatible with Strava » (règles de marque Strava) à la place du texte du pied de page.
- [ ] Smart App Banner (`apple-itunes-app`) une fois l'identifiant App Store connu.

## À garder à jour

La politique de confidentialité décrit le fonctionnement réel de l'app. Toute évolution qui touche aux données (nouveau prestataire, analytics, crash reporting, Apple Santé, compte utilisateur…) doit être reportée ici **avant** sa mise en ligne, ainsi que dans la fiche « Confidentialité » d'App Store Connect.

Ces textes sont une base rédigée à partir du code ; ils ne remplacent pas un avis juridique.
