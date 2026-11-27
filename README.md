# 🎄 Qui gâte qui ? — Secret Santa simple, sans inscription et sans pub

> **Le tirage au sort de cadeaux de Noël (ou d'anniversaire / Secret Santa) ultra-rapide, 100 % secret, sans création de compte, sans publicité et pensé pour être limpide pour tout le monde.**

🔗 **Démo en ligne :** [https://quigatequi.thomaslamart.fr/](https://quigatequi.thomaslamart.fr/)

---

## ✨ Pourquoi « Qui gâte qui ? » est une excellente alternative à DrawNames et TiroKado ?

Les plateformes connues comme **DrawNames** ou **TiroKado** sont pratiques pour certains besoins avancés, mais elles imposent souvent des compromis (comptes, écrans supplémentaires, publicités, parcours plus denses ou moins directs pour des utilisateurs peu familiers avec le web). **Qui gâte qui ?** prend le parti de la **simplicité radicale** : un seul fichier léger, aucune base de données, aucune inscription et une expérience fluide dès la première seconde.

### Comparatif rapide

| Critère | Qui gâte qui ? | DrawNames / TiroKado |
| :--- | :---: | :---: |
| **Inscription / création de compte** | ❌ Aucune | ⚠️ Souvent requise ou mise en avant |
| **Publicités & relances** | ❌ Zéro pub | ⚠️ Présentes selon formules / écrans |
| **Prise en main (« Boomer friendly »)** | ✅ Immédiate, lisible, sans jargon | ➖ Parfois plus chargée ou multi-étapes |
| **Tirage en boucle unique (cycle complet)** | ✅ Oui (algorithme de *backtracking*) | ➖ Variable selon les tirages |
| **Exclusions (couples, etc.)** | ✅ Oui (simples ou mutuelles) | ✅ Oui |
| **Partage rapide (WhatsApp + copie groupée)** | ✅ Oui + sauvegarde admin en un clic | ✅ Oui (souvent via mail/lien) |
| **Révélation ludique & masquage d'écran** | ✅ Cadeau animé + floutage du prénom | ➖ Souvent affichage direct |
| **Architecture** | 1 fichier HTML autonome (`index.html`) | Plateforme web tierce |

### Les vrais plus au quotidien
* **Zéro friction pour les participants** : chacun reçoit un lien direct vers sa page de révélation, clique sur le paquet cadeau animé et découvre qui il gâte — sans avoir à créer un mot de passe ni valider d'e-mail.
* **Accessible à toutes les générations** : typographie soignée, consignes claires, bouton pour **masquer/flouter le prénom** si quelqu'un regarde par-dessus l'épaule ou si vous partagez un écran.
* **Tirage fiable en une seule grande boucle** : grâce à la résolution par *backtracking*, le tirage forme un cycle unique passant par tous les participants tout en respectant les exclusions (fini les petits groupes fermés à deux).
* **Confort de l'organisateur** : possibilité de renseigner le **budget conseillé** et la **date de l'échange**, d'envoyer facilement via **WhatsApp** et de copier d'un clic **tous les liens (`Prénom : lien`)** pour garder une sauvegarde au cas où quelqu'un égarerait le sien.
* **Respect de la vie privée** : le tirage s'exécute côté client dans le navigateur, sans compte utilisateur ni tracking publicitaire invasif.

---

## 🚀 Fonctionnalités principales

* **Ajout & gestion des participants** (dès 3 personnes).
* **Règles d'exclusion** : excluez deux personnes dans un sens ou de façon **mutuelle** (idéal pour les couples).
* **Infos pratiques optionnelles** : budget conseillé et date de l'échange affichés lors de la révélation.
* **Liens secrets individuels** : encodage des données de révélation dans l'URL (`#reveal=...`) pour un partage simple.
* **Animations & confettis** : ouverture du paquet cadeau en SVG et confettis à la découverte.

---

## 🛠️ Stack technique & installation

Le projet tient dans un unique fichier `index.html` (accompagné de ses assets visuels comme `giftbox.png` et `og-qui-gate-qui.png`) :

* **HTML5 / CSS3** & **Tailwind CSS** (via CDN)
* **Polices Google Fonts** : *Playfair Display* et *Plus Jakarta Sans*
* **Canvas Confetti** (via CDN)
* **JavaScript vanilla** (sans framework ni build obligatoire)

---

## 🔒 Note sur la confidentialité des liens

Les informations de révélation sont encodées dans le fragment d'URL (`#reveal=...`) et non chiffrées cryptographiquement : elles ne sont pas lisibles d'un simple coup d'œil, mais restent décodables si quelqu'un inspecte le lien. Envoyez donc bien **chaque lien uniquement à la personne concernée**.

---

## 👤 Auteur

Créé par **Thomas Lamart** (*Themas*) — © 2026 Tous droits réservés.

---
---

# 🎄 Qui gâte qui? — Simple, Ad-Free Secret Santa Without Sign-Up

> **A fast, 100% secret gift exchange / Secret Santa draw with no account required, no ads, and a clean experience designed for everyone.**

🔗 **Live Demo:** [https://quigatequi.thomaslamart.fr/](https://quigatequi.thomaslamart.fr/)

---

## ✨ Why "Qui gâte qui?" Is a Great Alternative to DrawNames and TiroKado

Popular tools like **DrawNames** or **TiroKado** offer plenty of features, but they often come with trade-offs—such as account prompts, ads, extra steps, or interfaces that can feel overwhelming for less tech-savvy family members. **Qui gâte qui?** focuses on **effortless simplicity**: a single standalone HTML file, no sign-up walls, no ads, and an intuitive flow from start to finish.

### Quick Comparison

| Feature | Qui gâte qui? | DrawNames / TiroKado |
| :--- | :---: | :---: |
| **Sign-up / account required** | ❌ None | ⚠️ Often required or prompted |
| **Ads & promotional clutter** | ❌ Zero ads | ⚠️ Present depending on plan/screens |
| **Ease of use (all ages / non-tech)** | ✅ Clean, direct, low friction | ➖ Sometimes busier or multi-step |
| **Single full-circle draw** | ✅ Yes (*backtracking* cycle) | ➖ Varies by draw |
| **Exclusions (couples, etc.)** | ✅ Yes (one-way or mutual) | ✅ Yes |
| **Quick sharing (WhatsApp + copy all)** | ✅ Yes + 1-click organizer backup | ✅ Yes (often email/link based) |
| **Gift reveal & name privacy toggle** | ✅ Animated box + blur/hide name | ➖ Often shown directly |
| **Architecture** | Single standalone HTML (`index.html`) | Third-party hosted platform |

### Everyday Advantages
* **Zero friction for guests**: each participant gets a personal link, taps the animated gift box, and sees who they are gifting—no passwords, no sign-ups, no friction.
* **Built for everyone**: clear layout, readable typography, and a **hide/blur name button** in case someone is peeking or you're showing your screen.
* **Single-loop draw guarantee**: a backtracking solver generates a single Hamiltonian cycle across all participants while honoring exclusions (preventing isolated mini-loops).
* **Organizer convenience**: optionally add a **suggested budget** and **exchange date**, share via **WhatsApp**, and copy **all links (`Name : link`)** in one click as a backup if someone loses theirs.
* **Privacy-friendly**: runs client-side in the browser with no user accounts or ad tracking.

---

## 🚀 Key Features

* **Participant management** (for 3 or more people).
* **Exclusion rules**: block specific pairings one-way or **mutually** (great for couples).
* **Optional event details**: suggested budget and gift exchange date shown upon reveal.
* **Personal secret links**: reveal payload encoded in the URL hash (`#reveal=...`) for easy sharing.
* **Interactive reveal**: animated SVG gift box and confetti celebration.

---

## 🛠️ Tech Stack & Local Setup

Everything lives in a single `index.html` file (alongside assets such as `giftbox.png` and `og-qui-gate-qui.png`):

* **HTML5 / CSS3** & **Tailwind CSS** (via CDN)
* **Google Fonts**: *Playfair Display* and *Plus Jakarta Sans*
* **Canvas Confetti** (via CDN)
* **Vanilla JavaScript** (no framework or build step required)

---

## 🔒 Privacy Note on Links

Reveal data is encoded in the URL hash (`#reveal=...`) rather than cryptographically encrypted—it isn't plain text at a glance, though it can still be decoded if inspected. Always send **each link only to its intended recipient**.

---

## 👤 Author

Created by **Thomas Lamart** (*Themas*) — © 2026 All rights reserved.
