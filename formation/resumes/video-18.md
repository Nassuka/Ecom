# Vidéo 18 — Cloner la boutique d'un concurrent (homepage + page produit) avec Claude Design, Claude Cowork et Photoroom

- **Auteur / intervenant** : même youtubeur anglophone que les vidéos 16-17 (Winning Hunter, USA Drop, « 500 likes ») ; non nommé. Partenariat Photoroom.
- **Langue** : anglais
- **Longueur approximative** : ~36 000 caractères
- **Thème principal** : construire une boutique Shopify « niveau marque » en s'inspirant de 3 pages concurrentes, conversion HTML → Shopify Liquid par Claude, création des visuels/animations produit avec Photoroom.

## En bref
Partant d'une boutique concurrente (sac à dos tech de voyage) qui ferait 390 k$/mois depuis février 2026, l'auteur choisit 3 références (meilleure homepage, meilleure page produit, meilleure section « hero »), fait rédiger par ChatGPT des prompts pour Claude Design qui produit deux maquettes HTML, puis Claude Cowork + connecteur Shopify fusionne et convertit le tout en thème Liquid éditable (25-40 min). Pendant ce temps, il génère logo, photos produit/lifestyle et animations 3D dans Photoroom, à partir des meilleures pubs image du marché.

## Points clés (affirmations de l'auteur, non vérifiées)
**Choix des références**
- Inspiration via « Landers » (Winning Hunter : pages + revenu estimé de la boutique) ou « Pages by Landing Deck » (gratuit, sans revenu).
- Ne pas copier une seule boutique : décomposer en **3 éléments** pris chez des sites différents : (1) homepage, (2) page produit, (3) **hero section** (premier écran de la page produit, « la partie la plus importante »).
- Exemple de hero choisi : **bundle avec cadeau offert**, jugé très convertissant.
- Toujours vérifier le rendu **mobile** (inspecteur du navigateur) : « plus important que le desktop ».
- Les références n'ont pas besoin d'être de la même niche.

**Construction**
1. ChatGPT (mode « work », raisonnement élevé) + prompt de l'auteur avec les URLs de référence → prompt pour Claude Design.
2. Claude Design génère homepage et page produit **dans deux projets séparés** (les deux ensemble « corrompent le fichier ») ; export « standalone HTML ».
3. **Importer le produit dans Shopify avant** (via l'app du fournisseur, recherche par image possible) — sinon Claude « bloque ».
4. Claude Cowork : connecteur Shopify en « always allow », upload des 2 HTML + méga-prompt (rédigé par ChatGPT) demandant de fusionner et d'utiliser le connecteur Shopify ; 25-35 min ; installation de l'app « Shopify Claude Connector ». Claude duplique le thème (Horizon) et construit les sections.
5. Finitions manuelles : images dans chaque section, titre et description produit (via ChatGPT), variantes, logo.
- Les images de la maquette sont celles du concurrent (placeholders) : **à remplacer obligatoirement**.

**Visuels (Photoroom)**
- Stats citées par Photoroom : 63 % des acheteurs disent que des images incohérentes réduisent leur confiance ; 59 % des petits vendeurs disent perdre des ventes à cause d'images médiocres (chiffres de l'éditeur, non vérifiés).
- Une page qui convertit = un **système visuel** : hero, angles différents, matériaux, lifestyle, infographies — pas une seule belle image.
- Workflow : connecter Shopify → générer logo (style aléatoire, carré, description fournie par ChatGPT) → « product staging » (qualité avancée, 1:1) à partir de prompts rédigés par ChatGPT d'après les **meilleures pubs image du secteur** (tri « highest reach and spend » sur le mot-clé « backpack ») et la liste des emplacements d'images des maquettes HTML → images lifestyle (aéroport, bureau) → « video generator » (templates ou prompt libre, première frame puis vidéo) pour les animations 3D.
- Autres fonctions : embellisseur produit, ghost mannequin, flat lay, packaging, édition par lot.

## Outils et apps cités
| Outil | Usage | Prix |
|---|---|---|
| Winning Hunter « Landers » | pages de référence + revenu estimé | non donné |
| Pages by Landing Deck | galerie de landing pages | gratuit |
| ChatGPT (mode work, effort élevé) | rédaction des prompts design, images, titres | non donné |
| Claude Design | maquette HTML | non donné |
| Claude Cowork + connecteur Shopify | conversion HTML → Liquid, construction du thème | non donné |
| Shopify (thème Horizon) | boutique | non donné |
| USA Drop | import produit (recherche par image), sourcing, agent privé dès 5 commandes/jour ; plan gratuit ou pro | gratuit au départ |
| Photoroom | logo, staging, lifestyle, vidéos/animations, batch, audit | non donné |

## Exemples de produits / boutiques cités
- Sac à dos tech de voyage (boutique concurrente annoncée à 390 k$/mois, lancée en février 2026).

## Ce qu'on retient pour notre projet
- Méthode « 3 références » (homepage / page produit / hero) : simple et applicable pour notre boutique Q4 ; privilégier une hero avec **offre bundle + cadeau** (cohérent avec Black Friday / Noël).
- Penser **mobile d'abord** (trafic Meta ≈ mobile).
- Ordre des opérations : produit importé dans Shopify → maquettes → conversion → images → textes.
- Les visuels de page se génèrent avec nos outils IA (Nano Banana pour staging/lifestyle) en s'inspirant des meilleures pubs image du secteur ; prévoir hero, angles, détails matière, lifestyle, infographie.
- Prévoir 1 journée pour la boutique, mais **vérifier chaque texte en français** (titres, mentions légales, CGV) : l'IA ne gère pas le juridique FR.

## Points de vigilance
- « Cloner » une boutique : ne jamais garder images, textes ou logo du concurrent (droit d'auteur, concurrence déloyale).
- Revenus de boutiques concurrentes = estimations d'outils spy, souvent surévaluées.
- Vidéo sponsorisée (Photoroom) et liens affiliés ; stats Photoroom = données de l'éditeur.
- USA Drop expédie depuis la Chine : hors contrainte stock UE.
- Donner un accès « always allow » à une IA sur la boutique : faire une copie du thème et contrôler les modifications.
- Une boutique française doit afficher mentions légales, CGV, droit de rétractation de 14 jours, médiateur de la consommation : à vérifier (service-public.fr, economie.gouv.fr).
