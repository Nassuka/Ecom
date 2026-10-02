# Vidéo 01 — Créer une boutique Shopify 100 % avec l'IA (Claude Code) en copiant la structure d'une marque qui cartonne

- **Auteur / intervenant** : « Jonathan » (Jonathan Ecom / « Joecom », code promo cité), e-commerçant français, dit avoir 8 ans d'e-commerce et vendre un accompagnement.
- **Langue** : français
- **Longueur approximative** : ~92 000 caractères (transcription brute)
- **Thème principal** : construire une landing page / fiche produit Shopify sans thème payant ni application, en faisant analyser une boutique concurrente par Claude Code, puis copywriting + visuels IA (Higgsfield) + intégration en section Liquide. Bonus : paramétrage Shopify, obligations légales, emailing Omnisend.

## En bref
L'auteur repère via AutoDS (module « Adspy ») une marque anglophone de sabots/sandales, **confortco.com** (930 publicités actives dans la bibliothèque publicitaire Meta, >100 000 abonnés Facebook), puis fait reconstruire par Claude Code la structure exacte de sa fiche produit (sections, FAQ, avis, variantes) en HTML/Liquide, traduite en français. Il génère ensuite le copywriting adapté, une vingtaine de prompts d'images exécutés dans Higgsfield, héberge les images, et colle le tout dans une section « Liquide personnalisé » du thème gratuit Dawn. Il insiste sur les mentions légales, l'entreprise déclarée et l'email marketing (paniers abandonnés). Beaucoup de prompts « en description » (non fournis dans la transcription) et de liens d'affiliation.

## Points clés (affirmations de l'auteur, non vérifiées)
1. **Recherche de la marque modèle** : AutoDS > Adspy (filtre Facebook/Instagram/TikTok) ou « Trending products ». Critère : nombre de publicités actives dans la **bibliothèque publicitaire Meta** (« 930 pubs actives, impossible qu'il ne soit pas rentable »). Il écarte les produits à abonnement et les produits trop chers ; « plus c'est simple, mieux c'est ».
2. **Prompt 1 – structure** (dans Claude Code) : 3 variables = URL de la page produit concurrente, nom du produit, nom de marque + **capture pleine page PNG** (extension Chrome GoFullPage, pas en PDF). Nom de marque généré par l'IA (« 5 lettres, sans signification » → « Miron »). Extension « Right Click » si le site bloque le copier-coller.
3. Claude produit un fichier HTML/Liquide reprenant la structure (barre d'annonce, héros, valeurs, section impact, sélecteur de variantes/tailles, FAQ, avis) ; aperçu en HTML local.
4. **Intégration Shopify** : thème gratuit **Dawn** → Modifier le code → Sections → nouveau fichier `xxx.liquid` → coller le code → si erreur de schéma (ex. « invalid schema setting… color 5 »), coller l'erreur dans Claude qui corrige. Puis éditeur de thème → créer un modèle de page → Ajouter une section (ou bloc « Liquide personnalisé »).
5. **Prompt 2 – copywriting** : fournir nom, transformation avant/après, prix et variantes, 3-5 bénéfices, audience, douleur principale, preuves/témoignages, garantie, livraison. Exemple d'angle produit : « Vous payez pour le daim, pas pour nos pubs » / « Nike le fait pour 150 €, on le fait pour 39,99 € ». Cible déduite : femmes 30-55 ans. Si l'extraction du site/Amazon est bloquée, envoyer une **photo du produit**.
6. **Prompt 3 – visuels** : wireframe HTML + capture du concurrent (style visuel) + images fournisseur (AliExpress/Amazon) → Claude liste ~20 images (5 héros, 3 caractéristiques, valeurs, section impact, 6 avatars d'avis) avec un prompt par image, compatible ChatGPT / Nano Banana / Higgsfield. Astuce : demander un prompt **par avatar** sinon le générateur met 6 visages sur une image. Durée annoncée : ~30 min pour générer toutes les images.
7. **Hébergement des images** sur imgbb.com (gratuit) → liens directs .jpg/.png → donnés à Claude qui les mappe (ou upload direct sur le CDN Shopify) ; finalisation via un « brief Claude Design » qui regénère le HTML final avec images.
8. Claude Code en mode « computer use » peut écrire dans un thème **non publié** mais pas dans le thème live (selon la démo).
9. **Paramétrage Shopify** : coordonnées obligatoires (nom, email dédié, téléphone — numéro virtuel via **Onoff** pour ne pas donner le sien), paiements (Shopify Payments, Stripe, PayPal), vérifier la livraison (payante par défaut), taxes UE, langue FR, nom de domaine acheté, pixel Facebook via « Événements clients », bannière cookies et politiques (retour, confidentialité, CGV, mentions légales) générées par Claude à partir de ses infos.
10. **Légal** (selon l'auteur) : ne pas lancer de pub sans mentions légales (risque DGCCRF / contrôle fiscal), entreprise déclarée obligatoire, adresse visible par les clients → domiciliation conseillée (LegalPlace, adresse à Paris), compte pro séparé.
11. **Email marketing dès le départ** (Omnisend) : taux de conversion « moyen » 1 à 5 % ; séquence panier abandonné en 3 emails (T0, +11 h, +12 h avec code promo), idem abandon de checkout ; campagnes saisonnières (Black Friday, Noël) sur la base email.
12. Format mobile prioritaire : « la plupart des boutiques seront consultées sur téléphone ».

## Outils et apps cités
| Outil | Usage | Prix annoncé |
|---|---|---|
| Claude Code / Claude (« Claude Design ») | Structure de page, copywriting, prompts images, correction d'erreurs Liquide, pages légales | non précisé |
| AutoDS (module Adspy, Trending products) | Recherche de marques/produits, fournisseurs | non précisé (lien affilié) |
| Bibliothèque publicitaire Meta | Compter les pubs actives d'une marque | gratuit |
| GoFullPage (extension Chrome) | Capture pleine page PNG | gratuit |
| Right Click (extension) | Débloquer le clic droit/copie | gratuit |
| Shopify | Boutique ; offre via son lien : 3 jours gratuits puis 1 €/mois pendant 3 mois, ensuite ~36 €/mois (Basic). Il recommande de prendre le plan **Advanced (« 384 € »)** pendant la période à 1 € | voir vigilance |
| Thème Dawn | Thème gratuit de base | gratuit |
| Higgsfield (+ plugin Adobe Premiere Pro) | Génération d'images et de vidéos produit, changement de décor, suppression d'éléments | non précisé |
| Adobe Premiere Pro | Montage vidéo | essai gratuit |
| ChatGPT, Nano Banana | Alternatives pour générer les images | — |
| imgbb.com | Hébergement d'images gratuit pour obtenir des URL directes | gratuit |
| Onoff | Numéro de téléphone virtuel | « quelques euros par mois » |
| LegalPlace | Création micro-entreprise + domiciliation | pack standard 59 € HT, pack express 24 h ; ~100 € avec domiciliation et code promo « JOECOM » (-14 €) |
| Omnisend | Emails/SMS : automatisations (panier abandonné, checkout abandonné), campagnes | offre « start free » |

## Exemples de produits / boutiques cités
- **confortco.com** : sandales/sabots (hiver/été), « plus de 250 000 paires vendues » (affirmation du site), 930 pubs actives, avis clients, variantes couleurs (noir, sable, taupe, crème) et pointures 37-41.
- Marque fictive créée : **« Miron »** — sabots en daim, puis variante « baskets femme » trouvée sur Amazon (rose/blanc/noir), prix 39,99 €.
- Mentionnés en passant : produits « tendance TikTok », boutique ayant travaillé avec des athlètes (non nommée).

## Ce qu'on retient pour notre projet
- **Méthode « marque modèle »** directement compatible avec notre approche US → FR : trouver une boutique US/anglophone avec beaucoup de pubs actives (Meta Ad Library, TrendTrack), en reprendre la *structure* de page (pas le contenu) et la franciser. On peut le faire avec Claude Code sans acheter de thème premium → économie sur le budget de 1 000 €.
- **Workflow IA visuels** réutilisable avec nos outils (Higgsfield, Nano Banana) : un prompt par image, partir des photos fournisseur pour garder l'identité du produit, générer héros + bénéfices + lifestyle ; faisable pour la fiche produit Q4 (prévoir des visuels « cadeau / Noël »).
- **Thème Dawn gratuit + sections Liquide personnalisées** : piste peu coûteuse ; garder une copie de thème non publiée pour tester.
- **Avant la première pub Meta** : mentions légales, CGV, politique de retour (14 jours de rétractation), politique de confidentialité + bannière cookies, coordonnées de l'entreprise. Notre micro-entreprise existe déjà (activité Decoscale) → vérifier qu'elle couvre la vente en ligne de marchandises (voir `docs/entreprise-juridique.md`).
- **Email dès le lancement** (Omnisend ou équivalent, plan gratuit) : séquences panier/checkout abandonné, puis campagnes Black Friday (27/11/2026) et Noël — à préparer en octobre-novembre.
- Domiciliation : utile si on ne veut pas afficher l'adresse personnelle (coût à intégrer dans `docs/budget.md` si retenu).

## Points de vigilance
- **Copie de boutique** : l'auteur parle de « copier-coller » exactement un concurrent. Reprendre une mise en page est courant, mais copier textes, photos, avis ou marque expose à des risques de contrefaçon / concurrence déloyale / droit d'auteur — reprendre la structure, réécrire tout le contenu, ne pas réutiliser les photos du concurrent (à vérifier juridiquement).
- **Faux avis / avatars IA** : il génère 6 « avatars clients » par IA pour les avis. En France, les faux avis sont une **pratique commerciale trompeuse** (art. L121-2 et suivants Code de la consommation ; obligations sur les avis en ligne art. L111-7-2) — à ne pas reproduire. Source officielle à vérifier : legifrance.gouv.fr / economie.gouv.fr (DGCCRF).
- **Faux prix barrés** (« vente limitée jusqu'à 50 % off ») et comparaison avec Nike : l'annonce de réduction doit se référer au prix le plus bas des 30 derniers jours (art. L112-1-1 Code conso, à vérifier) ; utiliser des noms de marques tierces dans la pub = risque.
- **« 930 pubs actives = forcément rentable »** : raccourci ; le nombre de pubs indique un budget de test, pas une rentabilité prouvée.
- **Plan Shopify Advanced** pendant l'essai à 1 € : piège possible — vérifier le prix appliqué après la promo et les conditions (l'offre 1 €/mois peut ne concerner que certains plans ; tarifs Shopify à vérifier sur shopify.com/fr/tarifs). Pour nous, plan Basic suffisant.
- **Liens d'affiliation partout** (AutoDS, Shopify, LegalPlace, Omnisend) et vente d'accompagnement : biais commercial. Les prompts « en description » ne sont pas dans la transcription.
- « Réduction d'impôts jusqu'à 1 000 €/an » grâce à la domiciliation : affirmation non étayée, à ignorer sauf vérification.
- Taux de conversion « 1 à 5 % » : fourchette optimiste pour un débutant (souvent 1-3 %).
- Le délai d'expédition/fournisseur n'est pas traité ; sabots/chaussures = tailles → retours fréquents, peu adapté à notre critère « petit colis sans souci ».
- Laisser Claude Code piloter le navigateur sur l'admin Shopify : prudence (droits, thème live).
