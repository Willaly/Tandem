# Finances de couple — site

Site statique : page d'atterrissage + application de démo.

## Contenu
- `index.html` — page d'atterrissage (liste d'attente, formulaire branché sur Formspree).
- `app/index.html` — l'outil de gestion (démo, données locales dans le navigateur).

## Déploiement Vercel
1. Pousser ce dossier sur un dépôt GitHub (voir README à la racine du projet).
2. Sur https://vercel.com → **Add New… → Project** → importer le dépôt GitHub.
3. Framework preset : **Other** / static. Root directory : `./`. Rien d'autre à configurer.
4. **Deploy**. L'URL sert `index.html` à la racine, et l'app sur `/app`.

## Formulaire (liste d'attente)
Branché sur Formspree (form `xbdbpydw`) → e-mails vers **aly.william@gmail.com**.
L'envoi ne fonctionne qu'une fois le site **en ligne** (pas en ouverture locale du fichier).
Sur Formspree : confirmer le destinataire et valider la 1re inscription (e-mail d'activation).

> Nom « Tandem » = provisoire, à remplacer (déjà pris dans la finance).
