# Vidéo 40 — Construire en 10 minutes une page produit Shopify qui convertit : TrendTrack + Claude + Atlas + Rapid Bundles

- **Auteur / intervenant** : **Perry Sha** (orthographe incertaine), 21 ans, revendique « plusieurs millions » en e-commerce (une marque à 3 M$ ; boutiques à 197 k$ en 50 jours et 143 k$ en 30 jours) ; Discord gratuit.
- **Langue** : anglais. **Longueur** : ~27 000 caractères.
- **Thème principal** : fabriquer rapidement la boutique d'un produit à tester en s'inspirant de la page produit du plus gros concurrent.

## En bref
Procédure en 5 étapes :
1. trouver le produit et la **boutique de référence** (le plus gros vendeur) dans TrendTrack, connecté à Claude ;
2. **capturer** la page produit concurrente (GoFullPage) et la faire analyser par Claude (prompt maître : rôle de chaque section dans la conversion) ;
3. générer la boutique avec l'**app Shopify Atlas**, alimentée par un PDF d'étude de marché produit par 6 prompts Claude (~1 min, « 60-70 % terminée ») ;
4. recréer l'**offre de bundles** à partir d'une capture d'écran avec l'**app Rapid Bundles** ;
5. recréer chaque section manquante en **code Liquid personnalisé** généré par Claude à partir de captures, puis corriger l'affichage mobile.

Exemple : un oreiller « nuage » contre les douleurs cervicales (marque de référence « Melo »).

## Points clés (affirmations de l'auteur)
1. **Recherche** : TrendTrack (onglet Ads, filtre « native ads » ; onglet Shops → recherche par produit pour voir **toutes les grosses boutiques** qui vendent le même produit) ; choisir comme référence la page dont le style nous convient (souvent la plus grosse).
2. **Connexion TrendTrack ↔ Claude** : pop-up dans TrendTrack, 3 étapes.
3. **Capture et analyse** : GoFullPage (gratuit) → PNG de toute la page produit → **nouveau projet Claude** par boutique → capture + **prompt maître** (gratuit sur son Discord) + URL du concurrent. Claude analyse chaque section et son rôle dans la conversion, ce qui prépare la recréation. Modèle conseillé : le plus puissant (« Opus 5 » ; un modèle inférieur est possible).
4. **Atlas (app Shopify)** :
   - « Create new → full store », projet, **produit principal** (déjà créé dans Shopify), modèle « Atlas default » (modèles par niche, ex. compléments alimentaires) ;
   - **étude de marché** = 6 prompts Claude enchaînés (nom du produit + URL fournisseur AliExpress/Alibaba/1688 ou page concurrente) → **un PDF maître** chargé dans Atlas. Sans ce PDF, les textes du site sont plus vagues et convertissent moins ;
   - site complet en ~1 min, publié sur la boutique. Penser à **autoriser les permissions** que Claude demande pendant les actions.
5. **Images** : ne **jamais** reprendre les images du concurrent à l'identique ; les faire **recréer** par Gemini / Nano Banana Pro ou GPT Image 2 (« similaires mais pas identiques »).
6. **Offre (élément le plus important)** : l'app **Rapid Bundles** (alternative à Kaching Bundles) crée un bundle à partir d'une **capture d'écran** de l'offre concurrente en ~30 s : paliers, **cadeau offert débloqué selon la quantité** (exemple « Kitty Subs »). Ajouter un **bouton d'ajout au panier fixe** (« sticky add to cart »).
7. **Sections en Liquid personnalisé** :
   - capture d'une section concurrente → Claude « recrée cette section » → éditeur de thème → « Ajouter une section » → **Custom Liquid** → coller le code ;
   - en cas d'erreur, renvoyer le message d'erreur à Claude ;
   - ajouter ses images en les fournissant à Claude ;
   - travailler en parallèle (Claude code la section suivante pendant qu'on colle la précédente) ;
   - corriger par instructions précises (taille du texte, couleurs, interlignes).
8. **Priorités de conversion** :
   - « **90 % des visiteurs ne scrollent pas au-delà de l'offre** » : soigner avant tout le haut de page (images nettes, puces de bénéfices) et le **bundle** ;
   - la page d'accueil compte peu en phase de test ;
   - logo centré, barre d'annonce (offre saisonnière), avis colorés ;
   - **toujours vérifier la version mobile** (le code de Claude peut casser sur mobile).

## Outils et apps cités
| Outil | Usage | Prix |
|---|---|---|
| **TrendTrack** (+ intégration Claude) | produits, pubs « natives », boutiques concurrentes | −20 % avec son lien ; prix non donné |
| **Claude** (projets) | analyse de page, étude de marché (6 prompts), code Liquid | abonnement (modèle haut de gamme conseillé) |
| GoFullPage | capture pleine page | gratuit |
| **Atlas** (app Shopify) | génération du site / de la page produit par IA | non précisé |
| **Rapid Bundles** (app Shopify) | bundles et cadeaux débloqués, création depuis une capture | non précisé |
| Kaching Bundles | alternative citée | — |
| Nano Banana Pro / Gemini, GPT Image 2 | recréer les visuels produit | — |

## Exemples de produits / boutiques cités
- **Oreiller « nuage » ergonomique** (douleurs cervicales) — référence : « Melo ».
- « Kitty Subs » (exemple d'offre avec cadeau débloqué).
- Sa marque à 3 M$ (non détaillée).

## Ce qu'on retient pour notre projet
- **Priorité de construction** pour notre boutique de test du Q4 :
  - **haut de page** (photos nettes, titre-bénéfice, puces, preuve, prix) ;
  - **bundle** (1 / 2 / 3 avec cadeau débloqué — idéal pour Noël : « 2 achetés = emballage cadeau offert ») ;
  - **bouton d'ajout au panier fixe** ;
  - **mobile** d'abord.
  - La page d'accueil peut rester simple pendant le test.
- **Même méthode que la vidéo 32** (capture d'une section → Claude → Custom Liquid) : deux sources concordantes, à retenir comme méthode par défaut sur un thème Shopify gratuit (Horizon/Dawn).
- **Étude de marché en amont des textes** : Atlas et Claude écrivent de meilleurs textes s'ils reçoivent l'étude (cf. vidéos 29 et 36). Garder ce PDF ou document dans le projet Claude du produit.
- **Apps à évaluer** (prix à vérifier, impact sur le budget) : une app de bundles (Rapid Bundles ou Kaching) est probablement la plus rentable ; Atlas est optionnelle si Claude code les sections.
- **Visuels** : recréer à partir de nos propres photos produit avec Nano Banana Pro ou GPT Image 2, pas à partir des visuels concurrents.

## Points de vigilance
- **Reproduire « à 99 % » la page et l'offre d'un concurrent** : risque de **concurrence déloyale / parasitisme** et de droit d'auteur (textes, mise en page distinctive, photos). Il faut adapter (structure oui, contenu et visuels non).
- **« 90 % ne scrollent pas »** : chiffre non sourcé, mais l'idée (prioriser le haut de page) est raisonnable.
- **Apps tierces** : coûts mensuels, scripts qui ralentissent la page, compatibilité avec le Pixel/CAPI (tester les événements après installation, cf. vidéo 26).
- **Oreiller « anti-douleurs cervicales »** : allégation santé → prudence (DGCCRF, règles Meta). Un oreiller est aussi un **colis volumineux**, contraire à notre contrainte « petit colis ».
- Résultats annoncés (197 k$ en 50 jours) invérifiables ; contexte US.
