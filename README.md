# TRAMPOLINE — software & informatique

Site vitrine statique (HTML / CSS / JS, sans build) hébergé sur GitHub Pages,
domaine `trampolinesoftware.shop`.

> Généré depuis `C:\Users\souha\coaching-sites-factory` (fichier `sites/trampolinesoftware.mjs`).
> Pour une modification de contenu, éditez ce fichier puis relancez `node build.mjs trampolinesoftware` :
> une modification faite directement ici serait écrasée à la prochaine génération.

## À compléter avant de communiquer sur le site

| Priorité | Quoi | Où |
|---|---|---|
| 🔴 Bloquant | Mentions légales : identité de l’éditeur, SIREN, adresse, médiateur. Obligatoire en France. | `mentions-legales.html` |
| 🟠 Important | Adresse `contact@trampolinesoftware.shop` : créer une redirection e-mail chez Namecheap (*Domain List → Manage → Redirect Email*). | Namecheap |
| 🟠 Important | Formulaire : remplacer `VOTRE_ID_FORMSPREE` (sinon repli automatique en `mailto:`). | `contact.html` |
| 🟠 Important | Présentation de la personne qui coache (nom, parcours réel, photo). | `a-propos.html` |
| 🟡 Plus tard | Tarifs (Sur devis / Sur devis / Renvoyé €) et contenu des formules à ajuster à votre offre réelle. | `index.html` `#tarifs` |
| 🟡 Plus tard | Témoignages : n’en ajoutez que des vrais, avec l’accord des personnes. | — |

## Description de l’activité (Stripe, annuaires…)

```
We are Trampoline Software, an IT consultancy and software development company based near Gembloux, in the province of Namur. We advise on architecture and technical choices, build custom software, and manage and operate IT installations for businesses that have no internal team. Three things are written into every engagement because leaving them out is how clients get trapped. Who owns the code and the intellectual property, stated explicitly, since under Belgian law copyright stays with the developer unless it is assigned in writing. How backups are verified, by actually restoring them rather than trusting a green status light. And how personal data is handled, under a processing agreement within the meaning of Article 28 of the GDPR. We give no guarantee that any system is unbreachable, because no honest supplier can. Site: trampolinesoftware.shop
```

## Structure

```
index.html            Accueil : hero, programmes, méthode, tarifs, approche, FAQ
programmes.html       Détail des 4 programmes
a-propos.html         Notre approche et principes
contact.html          Formulaire de prise de contact
mentions-legales.html Mentions légales, confidentialité, CGV
404.html              Page d’erreur (chemins absolus)
assets/css/style.css  Couleurs de la marque en tête de fichier, puis styles communs
assets/js/main.js     Menu, thème, animations, formulaire
```

## DNS (Namecheap → Advanced DNS)

Supprimer les enregistrements de parking, puis :

| Type | Host | Value |
|---|---|---|
| A Record | `@` | `185.199.108.153` |
| A Record | `@` | `185.199.109.153` |
| A Record | `@` | `185.199.110.153` |
| A Record | `@` | `185.199.111.153` |
| CNAME Record | `www` | `hamzaniceguy99-glitch.github.io.` |
