# Vidéo 15 — Challenge « boutique 100 % IA en 24 h » : AutoDS + Claude (Code) + Higgsfield + Meta Ads via MCP

- **Auteur / intervenant** : non nommé ; e-commerçant « depuis plus de 8 ans », tourne une partie de la vidéo depuis la Chine (sourcing), promet des prompts gratuits en description et le contact WeChat de son fournisseur.
- **Langue** : français.
- **Longueur approximative** : ~67 000 caractères (~44 min).
- **Thème principal** : démonstration de bout en bout d'un lancement assisté par IA — recherche produit (AutoDS), validation par un « agent de scoring » Claude, copie de la structure d'une boutique concurrente avec Claude, copywriting, visuels Higgsfield, création de pubs Meta directement depuis Claude via un connecteur MCP — avec **résultat chiffré honnête : 1 vente, perte d'environ 66 € en 24 h**.

## En bref
L'auteur choisit deux produits sur la marketplace AutoDS (testeur de diamants, perruques), les fait noter par un prompt « agent de scoring » dans Claude (7 étapes, score /10), retient les perruques, fait **reproduire « pixel par pixel » la page d'un concurrent** (repéré via AutoDS et la Facebook Ads Library), fait rédiger le copywriting en français, génère ~36 images avec Higgsfield (GPT Image 2 / Nano Banana Pro) à partir de prompts produits par Claude, puis crée et **active** une campagne Meta à 100 €/jour depuis Claude. Bilan 24 h : 82 visites, 1 vente à 84 €, conversion 1,2 %, ~150 € de coûts → **−66 €**. Conclusion de l'auteur : l'IA est « game changer » pour la boutique et le copywriting, beaucoup moins pour la recherche produit.

## Points clés (affirmations de l'auteur, non vérifiées)
### Constat de départ
- Utiliser Claude « comme un assistant basique » (« crée-moi une boutique ») donne un mauvais résultat ; tout repose sur des **prompts structurés** et sur le fait de **fournir de la matière** (liens, captures, concurrents).

### Étape 1 — Recherche produit (AutoDS)
- Parcours de la marketplace **AutoDS** (best-sellers : gourde, ours en peluche, jeu de bâtonnets, fleurs « rose », etc.) ; deux idées retenues au feeling : **testeur de diamants électronique** et **perruques**.

### Étape 2 — Validation par un « agent de scoring » Claude (prompt fourni)
- 7 étapes : 1) fiche produit (bénéfice principal, avatar, **top 3 des douleurs**) ; 2) marché (mass market → niche → sous-niche) ; 3) **Google Trends** sur le pays visé (« la tendance en France n'est pas celle du UK ») ; 4) **Amazon** (classement, avis, signaux qualité) ; 5) fournisseurs et marge ; 6) concurrence ; 7) stratégie (canal = Facebook Ads, page = Shopify, élément de funnel = garantie, prix) → **score global + scores par section + plan d'action**.
- Résultats : testeur de diamants **7,2/10** (prix 29,99 €, coût 3–4 €, marge ~65 %, tendance stable, volume de recherche faible en France, 5e sur 184 sur Amazon FR) ; perruques légèrement devant (marché « très compétitif ») → perruques retenues.
- Si on donne les liens Amazon/AliExpress, Claude remplit lui-même les étapes ; sinon il faut répondre aux questions.

### Étape 3 — « Copier-coller » une boutique concurrente
- Trouver des boutiques qui marchent dans la niche via l'outil d'espionnage publicitaire d'AutoDS et vérifier dans la **Facebook Ads Library** qu'elles ont des pubs actives (ex. 130 pubs actives ; une autre marque avec « plus de 11 000 pubs »).
- Donner à Claude la fiche produit du concurrent + une **capture pleine page (extension GoFullPage)** → Claude produit un **wireframe HTML** qui reproduit « section par section, quasiment à l'identique » (annonce, galerie, sélecteurs couleur/taille, bundles, ajout panier, logos de paiement, blocs image/texte, étapes d'installation, comparatif, avis, FAQ, produits similaires, quiz).

### Étape 4 — Copywriting
- Claude propose le **nom de marque** (« Velvara ») et le nom du produit, déduit la cible, remplit tous les textes (placeholders) puis **traduit pour le marché français** (« Offre de lancement », « Livraison offerte », « Pas sûr de quelle longueur ou couleur choisir ? »…).

### Étape 5 — Visuels (Higgsfield)
- Prompt « audit des images manquantes » : Claude liste **29 images** à créer (héros, vignettes, avant/après, guide des longueurs, « comment poser », comparatif, avis, UGC, logo…), regroupées en **20 prompts**, avec la capture du concurrent comme référence de style (« s'inspirer, pas copier »).
- Génération dans **Higgsfield** : **GPT Image 2 = 12 crédits** (plus lent, meilleure qualité) vs **Nano Banana Pro = 2 crédits** (rapide, un peu moins bon) ; ~30 min pour toutes les images.
- Hébergement des images sur **imgbb.com** → liens directs donnés à Claude qui les place aux bons emplacements (vérifier : il a inversé certaines images).
- Il télécharge aussi toutes les images du concurrent (extension type « Imageye », > 2 000 images) — finalement jugé inutile pour un produit différent.
- Selon lui, le site est « fini à 80 % » ; les 20 % restants = corrections manuelles ; « Claude à 20 €/mois » remplace des milliers d'euros d'agence.

### Étape 6 — Créatives publicitaires
- **Lancer 10 à 15 créatives** dès le départ (≈ 7 images + 7 vidéos) pour tester les formats (image, vidéo carrée, UGC) : « on ne sait pas tant qu'on n'a pas testé ».
- Prompt « framework de visuels publicitaires scroll-stopping » : questions (produit, transformation, prix, différenciation) → brief stratégique → concepts d'annonces ; il recommande de **fournir des pubs concurrentes** trouvées dans l'Ads Library (filtre pays France, filtre « images ») comme références → Claude propose un concept, puis un prompt + les images à charger dans Higgsfield.
- Les photos produit générées pour le site peuvent servir en pub (éviter les fonds blancs « bizarres »). Ne pas payer 500 € une créatrice UGC ou 10–20 k€ une agence au début.

### Étape 7 — Campagne Meta depuis Claude (connecteur MCP)
- Ajouter un **connecteur personnalisé Facebook/Meta (MCP)** dans les réglages de Claude, l'**activer dans la conversation** (piège : connecteur ajouté mais non activé), autoriser les actions → Claude liste les comptes publicitaires, pose 5 questions (objectif, budget/jour, URL produit, visuels, page Facebook), vérifie page et pixel, crée campagne/ad set/annonce.
- Paramètres obtenus : **100 €/jour**, ciblage **broad femmes France 18–45 ans**, objectif **trafic** (pas encore de pixel), une image Higgsfield en créative. L'auteur affirme d'abord que Claude crée « en pause » et qu'on active soi-même… puis constate que **Claude a activé la campagne directement** (« faut quand même faire gaffe »).
- « Facebook est la meilleure plateforme pour démarrer l'e-commerce. »

### Résultats (24 h)
- **82 visites, 1 vente de 84 €, taux de conversion 1,2 %.**
- Coûts : 100 € de pub + perruque 45 € chez le fournisseur + ~5 € de frais ≈ **150 € → perte ≈ 66 €**.
- Bilan de l'auteur : **recherche produit** = Claude ne suffit pas (« si tu demandes à Claude quel produit lancer, ça ne marchera pas »), les outils spécialisés restent meilleurs ; **création de boutique** = révolution (« une boutique par jour ») mais il faut vérifier les bugs ; **copywriting** = excellent avec le bon prompt ; **pubs** = Higgsfield + Claude prometteur, photos OK, vidéos IA « bonnes à 80 % ».

## Outils et apps cités
| Outil | Usage | Prix annoncé |
|---|---|---|
| **AutoDS** (marketplace + espion de pubs) | Recherche produit, boutiques concurrentes | Non donné |
| **Claude / Claude Code** (« Claudia ») | Scoring produit, clonage de boutique, copywriting, prompts images, campagne Meta | ~20 €/mois |
| **Connecteur MCP Meta/Facebook** dans Claude | Créer/activer campagnes Meta depuis Claude | — |
| **Facebook Ads Library** | Vérifier pubs actives, références de créas | Gratuit |
| **Google Trends** | Tendance par pays | Gratuit |
| **Amazon (FR)** | Classement, avis, signaux qualité | Gratuit |
| **GoFullPage** (extension) | Capture pleine page du site concurrent | Gratuit |
| Extension de téléchargement d'images (« Imageye ») | Récupérer toutes les images d'un site | Gratuit |
| **Higgsfield** (GPT Image 2, Nano Banana Pro) | Images site + pubs | GPT Image 2 = 12 crédits/image, Nano Banana Pro = 2 crédits |
| **imgbb.com** | Hébergement d'images (liens directs) | Gratuit |
| **Shopify** | Boutique | — |
| **Meta Ads** | Acquisition | 100 €/jour dans le test |
| WeChat | Contact fournisseur chinois | — |

## Exemples de produits / boutiques cités
- **Testeur de diamants électronique** : 29,99 € de prix de vente, coût 3–4 €, score 7,2/10.
- **Perruques femme** (produit retenu, marque fictive « Velvara ») : coût 45 € chez un fournisseur chinois (MOQ faible), vendue ~84 €.
- Boutiques concurrentes copiées/étudiées : « irresistibleme.com » (perruques/extensions, ~130 pubs actives), « Arabella » (cheveux) ; une marque FR de perruques avec > 11 000 pubs.
- Produits vus sur AutoDS : gourde, ours en peluche, corde, ceinture, jeu de bâtonnets, fleurs « rose » éternelles.

## Ce qu'on retient pour notre projet
- **Résultat réaliste à garder en tête** : même avec l'IA de bout en bout, 24 h et 100 € de pub donnent ici **1 vente et une perte** ; avec 1 000 € de budget, il faut un plan de test sur plusieurs jours/semaines (et pas 100 €/jour d'emblée).
- **Agent de scoring produit** : bonne idée à reproduire dans notre méthode — combiner nos sources (SEMrush, Ads Library, TrendTrack plus tard) avec une **grille notée** dans Claude : douleurs/avatar, Google Trends **France**, Amazon FR, marge, concurrence, stratégie. À ajouter à `recherche-produit/`.
- **Claude pour la boutique** : utiliser une capture d'une **boutique US qui marche** comme référence de **structure** (ordre des sections, éléments de réassurance, FAQ, comparatif, avis), puis réécrire entièrement textes et visuels pour notre marque — cohérent avec notre méthode « US → France ».
- **Copywriting FR** : faire produire puis relire les textes (pas de traduction littérale de l'anglais).
- **Higgsfield** (déjà dans nos outils) : Nano Banana Pro (2 crédits) pour itérer vite, GPT Image 2 (12 crédits) pour les images finales/héros — à intégrer au budget crédits.
- **10–15 créatives au lancement** (images + vidéos) pour laisser Meta trouver le format ; références de concurrents via l'Ads Library (filtre France).
- **Connecteur MCP Meta** : peut accélérer la création des campagnes, mais **toujours vérifier et activer soi-même** ; installer le **pixel/API de conversions avant** de lancer (sinon l'outil bascule en objectif trafic, moins pertinent pour vendre).
- Ce test confirme notre contrainte **fournisseur UE** : ici fournisseur en Chine, produit à 45 € de coût, marge faible après pub.

## Points de vigilance
- **Copier une boutique concurrente « pixel par pixel »** et télécharger toutes ses images : risques de **contrefaçon (droit d'auteur sur textes, photos, design)** et de **concurrence déloyale/parasitisme** en France ; s'inspirer de la structure, jamais reprendre textes/visuels. L'idée de « copier-coller les photos d'une personne qui a eu des résultats à l'étranger » est à proscrire.
- **Claude a activé la campagne à 100 €/jour sans validation**, contrairement à ce qu'annonçait l'auteur : avec un connecteur ayant des droits d'écriture sur un compte publicitaire, limiter les autorisations (« toujours autoriser » est risqué) et plafonner le budget au niveau du compte Meta.
- **Budget** : 100 €/jour = 10 % de notre budget total par jour ; non adapté à un test prudent.
- **Objectif trafic sans pixel** : peu efficace pour vendre ; un seul jour de données n'est pas significatif (1 vente).
- **Fournisseur chinois via WeChat** recommandé en description : délais longs, qualité à vérifier, incompatible avec notre exigence de stock UE ≤ 3–9 jours.
- **Perruques** = produit beauté/cosmétique avec tailles/couleurs, retours fréquents et questions d'hygiène (exceptions au droit de rétractation pour produits descellés à vérifier : art. L221-28 du Code de la consommation — https://www.legifrance.gouv.fr).
- Le « 7,2/10 » est produit par un prompt de l'auteur, pas par des données vérifiées (volumes Google Trends et Amazon lus par l'IA, potentiellement approximatifs) — recouper avec SEMrush.
- Images IA de personnes dans les pubs : contenus synthétiques à signaler selon les règles Meta et les obligations de transparence de l'AI Act (règlement UE 2024/1689, art. 50 — à vérifier) ; ne pas les présenter comme de vrais clients.
- Le site généré par Claude est un **HTML statique** : son intégration dans un thème Shopify (sections, panier, variantes, apps) n'est pas montrée en détail ; prévoir du travail manuel.
