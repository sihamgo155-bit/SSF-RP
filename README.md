# SSF Morocco RP — Nouveau portail

Une refonte distincte du portail SSF : direction éditoriale claire, fond ivoire, vert profond, accent corail et citron vert, navigation latérale, mini-QCM et formulaire de candidature.

## Ouvrir en local
Ouvrez `index.html` dans un navigateur moderne. Une connexion Internet est utile pour charger les polices Google; le site reste utilisable avec les polices de secours sans connexion.

## Déployer gratuitement sur GitHub Pages
1. Créez un nouveau dépôt public, par exemple `ssf-morocco-portal`.
2. Importez le contenu de ce dossier (index.html, style.css, app.js et assets/).
3. Ouvrez **Settings → Pages**.
4. Choisissez **Deploy from a branch**, branche `main`, dossier `/(root)`, puis **Save**.
5. Attendez la fin du déploiement et ouvrez l’URL affichée dans GitHub Pages.

## Fonctions incluses
- Mise en page responsive, navigation par ancres et repérage de la section active.
- Français / English / العربية (avec direction RTL en arabe).
- QCM interactif de démonstration, score sur 100 et correction visuelle.
- Formulaire de candidature avec validation HTML, aperçu, copie et sauvegarde locale.
- Accordéons de charte, métadonnées SEO/Open Graph et favicon SVG.

## Limites à connaître
Il s'agit d'un projet statique. Les candidatures enregistrées sont conservées uniquement dans le navigateur et sur cet appareil; elles ne sont pas envoyées à une équipe et ne sont pas visibles par un administrateur à distance. Le QCM est un outil d'entraînement, non un examen officiel sécurisé. Pour des candidatures partagées, une connexion administrateur sécurisée ou un tableau de bord en ligne, il faut un backend et des règles d'accès adaptées. Les rôles et textes sont fictifs et ne représentent aucune institution gouvernementale réelle.

## Personnalisation
- Contenu et questions : modifier les objets de traduction et le tableau `quiz` dans `app.js`.
- Couleurs et mise en page : modifier les variables CSS en haut de `style.css`.
- Logo du navigateur : remplacer `assets/favicon.svg`.
