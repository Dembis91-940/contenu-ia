# 🎬 Créer et monétiser du contenu avec l'IA — Business « Créateur IA »

Business complet pour solopreneur : formation « Créer et monétiser du contenu avec l'IA » (film, vidéo, storytelling), vendue en 3 formules.

## 📁 Contenu du dossier

| Fichier | Rôle |
|---|---|
| `index.html` | Page d'accueil immersive 3D (Three.js : particules, parallaxe souris, profondeur au scroll) — hero, preuve, 12 leçons, 3 offres, formulaire de commande, garantie 14 jours |
| `chatbot.js` | Widget chatbot autonome (réponses préprogrammées + capture de leads via EmailJS) |
| `chatbot-config.js` | Config du chatbot « Créateur IA » : welcome, FAQs (prix, délai, prérequis, garantie…), EmailJS |
| `formation-contenu-ia.md` | LA formation complète niveau expert : promesse mesurable, 12 leçons (méthode + exemple réel + exercice), checklist finale, tarifs |
| `workbook.md` | Workbook élève : 12 fiches pratiques à remplir, template de scénario, template de prompt vidéo, grille de cohérence, kit de publication, plan de monétisation |
| `README.md` | Ce fichier |

## 🛠️ Stack (100 % réelle, zéro simulateur)

- **3D** : Three.js (CDN unpkg) — particules cyan/violet, icosaèdre wireframe, anneaux, parallaxe souris.
- **Formulaire de commande** : EmailJS réel — `serviceId: service_cy1ytdb`, `templateId: template_xpo58cv`, `publicKey: 8Pui4ZEqxW2jRVF7h`. Envoie `{site, name, email, question}` (« Commande : <offre> ») à chaque commande.
- **Chatbot** : `chatbot.js` + `chatbot-config.js` — questions fréquentes répondues, sinon capture de coordonnées (EmailJS + localStorage).
- **Design** : fond `#070b14`, accents cyan (`#22d3ee`/`#06b6d4`) et violet (`#8b5cf6`/`#a78bfa`), Inter, sombre haut de gamme, responsive.

## 💰 Offres

- **97 €** — La Formation (12 leçons PDF)
- **197 €** — Pack Pro + Studio (formation + prompts, templates, grille de cohérence, presets, kit de publication)
- **297 €** — Accompagnement (Pack Pro + 4 semaines : revue scénario, revue vidéo, coaching)

Paiement : virement ou message privé (indiqué au client dans l'email de confirmation). Livraison par email dès réception. Garantie satisfait ou remboursé 14 jours.

## 🚀 Déploiement

Site 100 % statique — hébergement gratuit :
1. Poussez le dossier sur un dépôt GitHub (ou tout hébergeur statique : Cloudflare Pages, Netlify, Vercel).
2. Activez GitHub Pages (branch `main`, dossier racine).
3. Testez le formulaire : remplissez une commande → l'email de confirmation arrive dans la boîte reliée au template EmailJS.

> ⚠️ Ne pas publier avant validation du paiement réel (passerelle Stripe/Lemon Squeezy) si vous souhaitez encaisser en ligne — le formulaire EmailJS prend les commandes et envoie les confirmations, il ne prélève pas d'argent.
