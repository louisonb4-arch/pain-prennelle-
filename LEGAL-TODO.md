# LEGAL-TODO — Pain'Prenelle, boulangerie artisanale

> **Ne pas mettre en ligne avant d'avoir traité la section 1.**
> État au 17 juillet 2026. Aucune donnée n'a été inventée : tout ce qui n'a pas pu être
> vérifié à une source est marqué `[à fournir]` ou `[à confirmer]` et apparaît **en
> surbrillance rose sur le site lui-même**, exprès — pour qu'un trou se voie au lieu de se
> combler avec une supposition.

---

## 1. Bloquant avant la mise en ligne

### 1.1 🔴 QUI ÉDITE CE SITE ? — le point le plus important de ce document

**Nous ne savons pas avec certitude quelle société édite ce site, et nous n'avons pas
tranché.** Désigner la mauvaise personne comme éditeur dans des mentions légales est
précisément la faute à éviter : c'est elle qui engage sa responsabilité pénale au titre de
l'article 6 LCEN.

Voici ce que le registre national des entreprises dit exactement, au 17 juillet 2026 :

| | Société A | Société B |
|---|---|---|
| **Nom** | **PAIN'PRENELLE** | **ORACLE** |
| Forme | SARL | SAS |
| SIREN | 803 493 600 | 914 299 557 |
| Adresse | **171** route de Sainte-Luce | **149** route de Sainte-Luce |
| APE | — | 10.71C — Cuisson de produits de boulangerie |
| État | 🔴 **CESSÉE** — établissements fermés | 🟢 **ACTIVE** |
| Enseigne déclarée | — | 🔴 **aucune** |

**Le problème, en trois lignes :**

1. La société qui **porte le nom** « Pain'Prenelle » est **cessée**, et elle était au **171**,
   pas au 149. Ce n'est pas l'éditeur. Ses numéros ne doivent surtout pas être repris.
2. La seule société **active** à l'adresse de la boulangerie (**149** route de Sainte-Luce)
   s'appelle **ORACLE**, et son activité déclarée est bien la cuisson de produits de
   boulangerie.
3. Mais **ORACLE n'a déclaré aucune enseigne**. Le lien ORACLE ↔ « Pain'Prenelle » est déduit
   de **la seule adresse**. Ce n'est pas une preuve.

**Ce qui va dans le sens d'ORACLE** (des indices, pas des preuves) :

- ORACLE est immatriculée le **7 juin 2022**, et le site écrit « Reprise fin 2022 par Clément
  et Aurore ». Les dates concordent.
- La **directrice générale d'ORACLE est Aurore Gachot** — le prénom du site.
- L'**APE 10.71C** est exactement l'activité d'une boulangerie.
- C'est la **seule** société active à l'adresse.

**Ce qui reste sans réponse :**

- « Clément » n'apparaît **dans aucun registre** au titre d'ORACLE.
- ORACLE est **présidée par une autre société, MCLA** (personne morale). Qui est derrière ?
- Aucune enseigne, aucun nom commercial « Pain'Prenelle » n'est rattaché à ORACLE.

**➜ Question à poser au client, telle quelle :**

> « Est-ce bien la SAS ORACLE (SIREN 914 299 557) qui exploite la boulangerie Pain'Prenelle
> et qui édite ce site ? Si oui, il faut déclarer l'enseigne « Pain'Prenelle » au registre —
> aujourd'hui elle n'y figure pas. Si non, quelle société ? »

Tant que ce point n'est pas tranché, **les mentions légales ne sont pas valables** : c'est
tout le bloc « Éditeur du site » qui en dépend, plus le directeur de la publication, plus le
responsable de traitement dans `confidentialite.html`.

### 1.2 Le reste de l'identité de l'éditeur (`mentions-legales.html`)

| Donnée | État |
|---|---|
| Capital social | **manquant** — obligatoire pour une SAS, ne figure dans aucun registre public |
| RCS | **à confirmer** — « RCS Nantes 914 299 557 » est la forme attendue, non vérifiée à une source |
| Directeur de la publication | **manquant** — voir 1.3, c'est plus compliqué qu'ailleurs |
| E-mail | **manquant** — apparaît dans les mentions légales, la confidentialité et le bloc accessibilité |
| Dépôt de marque « Pain'Prenelle » | **non vérifié** — aucune recherche INPI n'a été faite |

Le téléphone (**02 40 68 88 81**) est repris du site : il est déjà renseigné partout.

### 1.3 Directeur de la publication — cas particulier

Pour une société, le directeur de la publication est le **représentant légal**
(art. 93-2 de la loi du 29 juillet 1982). Ici la SAS est **présidée par une personne morale
(MCLA)**, pas par une personne physique. Une société ne peut pas être directrice de la
publication : c'est **la personne physique qui représente légalement MCLA** qui l'est, sauf
désignation expresse d'un autre.

**Il faut donc un nom de personne physique**, et ce nom ne se déduit pas du registre. À
demander au client. (Aurore Gachot est *directrice générale*, pas présidente — la désigner
d'office serait une supposition.)

### 1.4 Hébergeur (article 6 III-1 LCEN — obligatoire)

Nom, adresse, téléphone et site de l'hébergeur. Les quatre champs sont vides dans
`mentions-legales.html`, et la durée de conservation des journaux de connexion est vide dans
`confidentialite.html`.

> Le dossier contient un fichier `.vercel/project.json` (projet `painprenelle-site`), ce qui
> **suggère** un déploiement sur Vercel. Ce n'est pas une confirmation, et l'hébergeur n'a
> donc **pas** été écrit sur la page : il doit être arrêté puis renseigné par l'éditeur, avec
> sa raison sociale exacte, son adresse et son téléphone.

Une fois l'hébergeur retenu, vérifier s'il implique un **transfert hors UE** (section
correspondante de `confidentialite.html`).

### 1.5 Photographies — aucun crédit, et des fichiers de dépannage

**Aucun auteur n'est identifié pour les photographies du site.** C'est un `[à fournir]` sur
la page.

Les images actuellement en place sont des **vues réelles de la boulangerie, récupérées en
basse définition depuis le compte Instagram de la maison** (recadrages 800 × 800 typiques
d'une grille Instagram ; `devanture.jpg` ne fait que 511 × 391 px). Elles dépannent, elles ne
tiennent pas en production :

- **techniquement** : trop petites pour les blocs où elles sont affichées (le hero, le
  portrait, la bande Instagram) — elles seront visiblement molles sur écran Retina ;
- **juridiquement** : une photographie appartient à **celui qui l'a prise**, même publiée sur
  le compte de la boulangerie. Si un photographe est intervenu, l'étendue des droits cédés
  (support, durée, territoire) doit être documentée.

**À réclamer :** les fichiers d'origine en haute définition, le nom de l'auteur, et
l'autorisation au titre du droit à l'image des personnes reconnaissables — au premier chef le
portrait `clement-aurore.jpg` en section « La Maison ».

### 1.6 L'avis Google affiché en page d'accueil

Le hero affiche : **« 4,6 / 5 — plus de 290 avis Google »**. C'est une allégation
commerciale chiffrée, et elle n'a **pas** été vérifiée à la source lors de cette rédaction.
Une note obsolète ou fausse relève de la pratique commerciale trompeuse
(art. L121-2 du code de la consommation).

**À faire :** vérifier la note et le nombre d'avis sur la fiche Google Business le jour de la
mise en ligne, puis prévoir de les rafraîchir — ou retirer le chiffre précis au profit d'une
formulation stable.

### 1.7 Vérifier avant publication

```bash
grep -rn "à fournir\|à confirmer" *.html    # ne doit plus rien renvoyer
```

---

## 2. Ce qui a été vérifié (et n'est donc pas à redemander)

Relevé le **17 juillet 2026** au registre national des entreprises via l'API publique
`recherche-entreprises.api.gouv.fr` :

**Société ORACLE — active, 149 route de Sainte-Luce (rattachement à Pain'Prenelle à confirmer,
voir § 1.1) :**

- Dénomination : **ORACLE** · aucun sigle, **aucune enseigne déclarée**
- Forme : **SAS** (code INSEE 5710 — société par actions simplifiée)
- Siège : **149 route de Sainte-Luce, 44300 Nantes**
- SIREN : **914 299 557** · SIRET siège : **914 299 557 00019**
- TVA : **FR01914299557**
- APE : **10.71C — Cuisson de produits de boulangerie**
- Immatriculation : **7 juin 2022**
- Présidente : **MCLA** (personne morale)
- Directrice générale : **Aurore Gachot**
- Coordonnées GPS du siège : **47.2362499798249, -1.51850211855043**
- État administratif : **actif**

**Société PAIN'PRENELLE — l'homonyme cessé, à ne pas confondre :**

- Dénomination : **PAIN'PRENELLE** · Forme : **SARL** · SIREN : **803 493 600**
- Adresse : **171** route de Sainte-Luce (≠ l'adresse du site)
- État administratif : **cessé (C)** — établissements fermés

Le siège d'ORACLE **est** l'adresse de l'établissement : il n'y a donc qu'une seule adresse à
mentionner, pas deux.

> Les coordonnées GPS ne sont pas dans un JSON-LD : `index.html` n'en contient aucun. À
> ajouter si l'on veut une fiche `Bakery` structurée (champs `geo`, `openingHours`).

---

## 3. Pages légales : ce qui a été créé, et ce qui ne l'a pas été

### Créées

| Page | Pourquoi |
|---|---|
| `mentions-legales.html` | Obligatoire (art. 6 III LCEN) pour tout site édité par une société. |
| `confidentialite.html` | Transparence RGPD sur les journaux de l'hébergeur et les liens sortants, même sans collecte. Contient la section cookies (ancre `#cookies`). |

Rubrique maison : **« La liste des ingrédients »** — sur un site de boulangerie, les pages
légales sont la composition, écrite en toutes lettres.

### Volontairement non créées

| Page | Pourquoi pas |
|---|---|
| **CGV** | Ce site ne vend rien : aucune commande, aucun paiement, aucun panier. Les ventes se font au comptoir. Une CGV serait un document sans objet. |
| **CGU** | Aucun compte, aucun contenu déposé par l'utilisateur, aucun service interactif. Sans objet. |
| **Droit de rétractation** | Pas de vente à distance depuis ce site. |
| **Section « Vente d'alcool »** | Boulangerie : sans objet. |
| **Bannière de consentement cookies** | Voir § 4. |
| **`sitemap.xml`** | **Impossible sans inventer le domaine** — voir ci-dessous. |

### 🟠 `sitemap.xml` — non créé, exprès

Le site **n'a ni `sitemap.xml`, ni `robots.txt`, ni balise `canonical`, ni `og:url`** : **aucun
domaine n'est écrit nulle part** dans le projet. Un sitemap exige des URL absolues. En écrire
un aurait voulu dire choisir un domaine à la place du client.

**À faire une fois le domaine arrêté** — créer `sitemap.xml` avec les trois pages :

```xml
<url><loc>https://LE-DOMAINE/</loc><lastmod>2026-07-17</lastmod><priority>1.0</priority></url>
<url><loc>https://LE-DOMAINE/mentions-legales.html</loc><lastmod>2026-07-17</lastmod><priority>0.2</priority></url>
<url><loc>https://LE-DOMAINE/confidentialite.html</loc><lastmod>2026-07-17</lastmod><priority>0.2</priority></url>
```

…et ajouter les `canonical` correspondants dans les trois `<head>`.

---

## 4. Cookies, traceurs, données

### Ce que le site fait réellement — après les corrections du 17 juillet 2026

| | |
|---|---|
| Cookies déposés | **aucun** |
| Stockage local | **aucun** — `main.js` n'utilise ni `localStorage` ni `sessionStorage` |
| Mesure d'audience | **aucune** |
| Requêtes vers des tiers | **aucune** — vérifié : plus une seule URL externe dans les `src`/`href` de ressources |
| Formulaires | **aucun** |
| Comptes utilisateurs | **aucun** |
| Newsletter | **aucune** |
| Paiement | **aucun** |

### Ce qui a dû être corrigé pour pouvoir écrire ça

Avant le 17 juillet 2026, la phrase « aucun cookie » aurait été **fausse**. Deux fuites :

**1. La carte Google Maps en `<iframe>` (section « Nous trouver ») — supprimée.**
L'iframe `google.com/maps?…&output=embed` chargeait Google **dès l'ouverture de la page**,
lui transmettait l'adresse IP du visiteur et y déposait ses cookies, sans consentement. À
elle seule, elle imposait une bannière.
Elle est remplacée par un **cartouche vert avec l'adresse, l'accès en tram et un bouton
« Ouvrir le plan »** qui part en lien sortant vers Google Maps. Même service rendu, zéro
requête tierce à l'ouverture. Le filtre CSS vert de l'iframe est retiré avec elle.

**2. Fraunces, Karla et Caveat chargées depuis `fonts.googleapis.com` / `fonts.gstatic.com`
— rapatriées.** Chaque visite transmettait l'adresse IP du visiteur à Google, sans
consentement : le point précis sur lequel la CNIL et plusieurs autorités européennes ont
sanctionné des éditeurs.
Les trois familles sont désormais **auto-hébergées** dans `assets/font/` (licence SIL OFL
1.1, sous-ensembles latin + latin-ext uniquement, **460 Ko** au total, `font-display: swap`).
Les `<link>` et `<preconnect>` vers Google ont été retirés d'`index.html`, les `@font-face`
ajoutés en tête de `styles.css`, et deux `preload` posés sur les polices principales.

> Fraunces (opsz 9–144, wght 100–900), Karla romain (wght 200–800) et Caveat (wght 400–700)
> sont **variables** : un fichier par style et par sous-ensemble suffit. L'italique de Karla
> est **statique** (400 seulement) — c'est le seul poids que le site lui demande.

### Pourquoi il n'y a pas de bannière

L'article 82 de la loi Informatique et Libertés impose le consentement **avant tout dépôt de
cookie non strictement nécessaire**. Aucun cookie n'étant déposé, il n'y a rien à consentir.
Une bannière serait une gêne sans objet. C'est un choix argumenté, pas un oubli.

**Ce qui déclencherait l'obligation d'en poser une :**

- ajouter Google Analytics, Matomo (en mode non exempté), un pixel Meta ou tout traceur ;
- **remettre une carte Google Maps en `<iframe>`** — c'est exactement ce qui vient d'être
  retiré ;
- intégrer un widget Instagram, une vidéo, un module de commande en ligne ;
- **recharger les polices depuis Google Fonts.**

Dans ces cas : dispositif Refuser / Accepter / Personnaliser, refus aussi simple que
l'acceptation, aucun dépôt avant consentement, lien permanent de modification du choix dans
le pied de page.

---

## 5. À vérifier après la mise en ligne

- [ ] **L'identité de l'éditeur est tranchée** (§ 1.1) — rien d'autre ne compte tant que non
- [ ] `grep -rn "à fournir\|à confirmer" *.html` ne renvoie plus rien
- [ ] Les photos HD d'origine sont en place et créditées (§ 1.5)
- [ ] La note Google affichée est à jour (§ 1.6)
- [ ] `sitemap.xml`, `robots.txt` et les `canonical` pointent le vrai domaine (§ 3)
- [ ] Le site est déclaré dans Google Search Console
- [ ] La fiche Google Business est cohérente avec les horaires du site
- [ ] Aucune requête tierce dans l'onglet Réseau du navigateur
- [ ] `document.cookie` est vide
- [ ] `confidentialite.html#cookies` atterrit bien sur la section Cookies (le reset de scroll
      de `main.js` est désormais neutralisé sur les pages légales)
- [ ] Si une carte des produits avec prix est ajoutée un jour : affichage des prix
      (arrêté du 3 décembre 1987) et information sur les **allergènes**
      (règlement UE n° 1169/2011) deviennent obligatoires.
