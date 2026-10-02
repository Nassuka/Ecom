# Synthèse des 39 vidéos de formation → méthode retenue

> Rédigée le 2026-10-02 à partir des résumés de `resumes/` (39 vidéos uniques, ~4,4 M caractères de transcriptions dans `transcriptions/`).
> Les chiffres cités (CA, ROAS, « X k€/jour ») sont des **affirmations des auteurs, non vérifiées**. Beaucoup de vidéos servent aussi à vendre un coaching ou des liens affiliés.
> Les points juridiques et fiscaux sont **à vérifier** auprès des sources officielles indiquées.

## 1. Ce sur quoi presque toutes les vidéos sont d'accord

1. **Ordre d'importance** : produit, puis offre, puis créas, puis page produit, puis réglages pub (Gabor, 03-09). La créa fait 56 à 80 % du résultat selon les vidéos 20, 21, 26 et 36.
2. **Pas de concurrent, pas de marché.** On cherche un produit qui se vend déjà quelque part (US, UK), puis on vérifie qu'il n'est pas saturé en France (vidéos 03-04, 16, 20, 32, 37). C'est **exactement notre méthode**.
3. **Le produit est rarement saturé, c'est l'angle qui l'est.** On teste plusieurs avatars et angles avant d'abandonner un produit. Pour Noël, il faut **toujours un avatar « acheteur de cadeau »** (vidéos 28, 31, 41).
4. **Marge** : prix de vente d'au moins **×2,5 à ×3** le coût produit + livraison (×4-5 idéal). Pour fixer le coût d'achat maximum, on prend le prix des concurrents divisé par 2,5 ou 3.
5. **L'IA rend les créas et la boutique presque gratuites** : Claude pour la recherche, les textes et les sections Shopify ; Nano Banana pour les images ; Higgsfield et Seedance pour les vidéos. On l'utilise à condition de **donner les vraies photos du produit** à l'IA (vidéos 10, 11, 15-18, 20, 32, 36, 39, 40).
6. **E-mails automatiques dès le lancement** : panier et paiement abandonnés, post-achat et demande d'avis, puis campagnes Black Friday et Noël (vidéos 07, 16, 20, 42).
7. **Le légal et le tracking sont prêts avant la 1re pub** : pixel et API de conversion testés, mentions légales, CGV, rétractation, cookies.

## 2. Méthode retenue pour notre projet

### 2.1 Recherche et validation produit (semaine 1-2)
- **Repérer.** On part de la short-list actuelle (10 produits, voir `recherche-produit/produits-q4-historiques.md`). On peut la compléter avec TrendTrack, qui donne la croissance de trafic et du nombre de pubs des boutiques US, et le prompt « agent 30/60/90 jours » de la vidéo 37.
- **Valider la demande.** Pour chaque produit :
  - **SEMrush** en base US et en base FR, en notant le **score de niche = prix moyen ÷ CPC** (au-dessus de 150, c'est bon signe ; vidéo 33) ;
  - **Google Trends sur 5 ans** en France : on cherche un pic au Q4, puis une demande stable ;
  - **bibliothèque publicitaire Meta FR** : nombre d'annonceurs, pubs actives depuis au moins 30 jours, nombre de variantes ;
  - un concurrent à **au moins 15-20 k visites/mois** en croissance (vidéos 16, 20) ;
  - les **avis Amazon** analysés par l'IA pour lister les défauts et les objections.
- **Critères éliminatoires** (vidéo 20, compatibles avec notre grille) : concurrent prouvé, avant/après visible en 2-3 s, vrai problème ou fort potentiel cadeau, produit qu'on comprend sans explication.
- **Garder 3 produits**, à tester l'un après l'autre (pas tous en même temps).

### 2.2 Offre (là où se fait la marge)
- L'offre doit se comprendre en 3 secondes et être **justifiée par un événement** (Black Friday, Noël).
- **Packs 1 / 2 / 3** avec une offre haute qui sert d'ancrage, ou un **cadeau débloqué** selon la quantité. Pour Noël, le pack « 1 pour moi, 1 à offrir ».
- **Upsell après achat** et seuil de livraison gratuite avec barre de progression.
- ⚠️ La vidéo 12 a vu la conversion **monter** en retirant les bundles. On les teste donc, on ne les impose pas.
- Panier visé : **40 à 80 €**.

### 2.3 Boutique Shopify
- **Une niche extensible** plutôt qu'un produit isolé : si le 1er produit échoue, on garde le site, les avis et les données publicitaires (vidéo 12).
- **Thème gratuit** (famille Horizon / Tinker). On s'inspire de la structure d'une boutique US qui marche, mais on **réécrit tous les textes et on refait tous les visuels**.
- On ne copie jamais les médias des concurrents : c'est un problème de droit d'auteur et de marques, et un risque de blocage par Meta.
- **Paramétrage France** : checklist complète dans `resumes/video-14.md` et `video-19.md`.
  - Shopify Payments avec SIRET ;
  - checkout sur une page, sans compte obligatoire ;
  - Apple Pay, Google Pay, PayPal ;
  - livraison en points relais ;
  - retours en libre-service.
- **Page produit**, d'après les vidéos 04-05, 31, 40 et 42 :
  - le haut de page et le choix du pack sont prioritaires (la plupart des visiteurs ne descendent pas) ;
  - un GIF en 2e image ;
  - la date de livraison estimée près du bouton ;
  - des puces dans l'ordre émotion, objection, projection, argument rationnel ;
  - le mécanisme du problème puis celui de la solution ;
  - un comparatif et une FAQ construite à partir des objections réelles ;
  - les avis près du bouton ;
  - **mobile d'abord**.
- **Page d'accueil minimale** : environ 5 % des visiteurs la voient.
- **Avantage stock UE** à mettre en avant : « livré en 2-4 jours », et **date limite de commande pour Noël** affichée.

### 2.4 Créas (le cœur du résultat)
- **3 à 4 angles vraiment différents** par produit : problème/solution, démo avant/après, UGC, cadeau.
- **3 à 5 créas par angle** au départ : vidéos et images statiques. On en ajoute ensuite chaque semaine.
- **Structure de script** : accroche (3 premières secondes), problème, mécanisme, preuve, objection, urgence, appel à l'action. **20 à 30 s, en 9:16, avec une zone utile en 4:5.**
- **Méthode IA** :
  - analyser une pub gagnante (US ou FR) ;
  - générer des images de référence (actrice, décor, produit réel) avec Nano Banana ;
  - générer des plans de 3 à 10 s avec Higgsfield ou Seedance ;
  - monter le tout dans CapCut.
  - L'audio IA en français bugue : il vaut mieux enregistrer **sa propre voix** et la convertir (vidéo 32).
  - Contrôler l'accent, les mains, un produit déformé.
- **Nos propres vidéos de l'échantillon** (filmées au téléphone) sont un plus : elles prouvent que le produit livré est celui de la pub.
- **Matière première** : les clients écrivent les meilleures pubs (commentaires, avis Amazon, Reddit). Chaque objection devient une accroche ou une question de FAQ.

### 2.5 Meta Ads : structure retenue pour un petit budget
Les vidéos ne sont pas d'accord entre elles. Les vidéos 21 et 06 recommandent une campagne à budget global (CBO) avec ciblage large ; la vidéo 26 recommande un budget par ensemble de pubs (ABO) avec des intérêts. **Notre choix, adapté à 1 000 € et à un compte neuf :**
- **Une campagne « Ventes »** optimisée sur l'achat.
  - Pixel et API de conversion installés via l'app Facebook & Instagram de Shopify, testés avec Pixel Helper et le gestionnaire d'événements.
  - Compte publicitaire en EUR, double authentification activée.
- **Budget par ensemble de pubs (ABO)** pendant le test : 1 ensemble par angle, **10-15 €/jour chacun**, 2-3 ensembles, 3 créas par ensemble. Cela contrôle exactement ce que chaque angle dépense.
- **Ciblage** : France (puis Belgique), large ou Advantage+, avec éventuellement un ensemble par intérêt en comparaison. Désactiver les « améliorations créatives » automatiques.
- **Lancement à minuit**, puis **on ne touche à rien pendant 48-72 h**.
- **Avant de lancer**, on calcule le **ROAS d'équilibre = 1 ÷ taux de marge brute**. Avec 40 % de marge, il est de 2,5. Le « ROAS 1 = équilibre » de la vidéo 26 est faux.
- **Couper une pub** : CTR < 1 %, hook rate < 25 %, ou dépense de 1 à 1,5 fois le CPA cible sans achat.
- **Couper un produit (stop-loss)** : environ **150-200 €** dépensés sans rentabilité, toutes créas et tous angles confondus.
- **Augmenter un gagnant** : +15-20 % par jour sur 3 jours glissants rentables. Ensuite 80 % du budget sur ce qui marche, 20 % en test.
- **Diagnostiquer avec l'entonnoir** :
  - CPC élevé : la créa est en cause ;
  - clics sans ajout au panier : la page ou le prix ;
  - ajouts au panier sans achat : le checkout ou la confiance.
- **Fréquence** : au maximum 3,5 par semaine en acquisition. Le retargeting ne s'ajoute que quand il y a du trafic.

### 2.6 Google Ads (test secondaire)
- Ça marche surtout pour une **demande qui existe déjà** (produits qu'on recherche sur Google).
- On l'active **une fois le produit validé sur Meta**, avec :
  - un flux Merchant Center propre ;
  - une **campagne Shopping standard en CPC manuel, 20-30 €/jour** (vidéo 33), ou Performance Max ;
  - des mots-clés négatifs.
- Le **Google Ads Transparency Center** montre les pubs Shopping des concurrents (vidéo 33).

### 2.7 E-mail (Klaviyo ou Omnisend, version gratuite au début)
- **Pop-up -10/-15 %** avec un code (pas une remise automatique), qui sert aussi à collecter les adresses pour le Black Friday.
- **Flux à mettre en place avant la 1re pub** :
  - bienvenue ;
  - panier et paiement abandonnés : 3 mails, le code de réduction au 3e seulement. Pas de cascade jusqu'à -50 %, qui détruit la marge (vidéo 07).
  - post-achat, puis demande d'avis à réception + 3 jours.
- **Black Friday** : constituer une **liste d'attente « early bird »** dès début novembre, puis 4 vagues : annonce, ouverture, relance, dernière chance (vidéo 42).

## 3. Calendrier : ce que les vidéos changent pour nous
- Le cas de Gabor (CosyNest, produit d'hiver) s'est lancé le **06/10/2024**.
  - Octobre a été **à l'équilibre**, avec l'apprentissage et les créas à trouver.
  - Les profits sont arrivés en **novembre-décembre**.
- La vidéo 11 annonce environ 20 jours avant le premier profit.
- **Conséquence** : il faut **avancer le 1er test Meta vers le 16-20/10** au lieu du 23/10. Pour cela :
  - produits choisis au plus tard le **07-08/10** ;
  - échantillons commandés en stock UE (3 jours) ;
  - boutique et page du 1er produit en ligne vers le **14-15/10**.
- **Il faut s'attendre à rater 1 ou 2 produits.** Le budget doit permettre 2 à 3 tests d'environ 200 €.

## 4. Pratiques vues dans les vidéos à NE PAS reproduire (illicites ou risquées en France, à vérifier)
- **Faux avis** : avis importés d'AliExpress, filtre qui ne publie que les 5 étoiles, faux articles de presse, mentions « élu produit de l'année ». Référence : Code de la consommation, pratiques commerciales trompeuses. Source : [DGCCRF](https://www.economie.gouv.fr/dgccrf).
- **Témoignages UGC générés par IA présentés comme de vrais clients**, avec des promesses de résultat. Références : AI Act art. 50 sur la transparence et pratiques trompeuses. On peut faire de l'UGC IA en **démonstration**, mais pas un faux témoignage de cliente.
- **Prix barrés fictifs** : au Black Friday, le prix de référence est **le plus bas des 30 derniers jours** (art. L112-1-1 du Code de la consommation, [Légifrance](https://www.legifrance.gouv.fr/)).
- **Fausse rareté** (« plus que 3 en stock », variante faussement en rupture) et faux comptes à rebours.
- **Réutiliser les vidéos ou images des concurrents** sans droits. Utiliser ® sans marque déposée. Concepts « Run-to » qui font croire à une vente chez une enseigne connue.
- **« Assurance livraison » payante** : le vendeur supporte déjà le risque de transport vers le consommateur.
- **Suivi de colis simulé** ou masqué.
- **Comptes publicitaires « agence » loués** via des intermédiaires (vidéo 06) et multicomptes.
- **Allégations santé, minceur ou repousse** : interdites (concerne nos candidats anneau fascia, peigne de massage, masseur yeux).

## 5. Points fiscaux et juridiques soulevés par les vidéos (à vérifier)
- **Facturation électronique** : d'après la vidéo 14, toutes les entreprises doivent pouvoir **recevoir** des factures électroniques depuis le **01/09/2026**. L'émission et l'e-reporting des ventes aux particuliers arriveraient plus tard pour les micro-entreprises. → À vérifier sur [impots.gouv.fr – facturation électronique](https://www.impots.gouv.fr/facturation-electronique-et-plateformes-agreees).
- **Droit de douane UE de 3 € par article** sur les petits colis venant de vendeurs hors UE, depuis le 01/07/2026 (vidéo 20). → À vérifier sur [douane.gouv.fr](https://www.douane.gouv.fr/). Notre stock UE évite ce sujet, mais il faut vérifier que le fournisseur expédie bien depuis l'UE.
- **Seuils micro-entreprise et TVA** : les vidéos 20 et 26 citent des chiffres confus. → À vérifier sur [autoentrepreneur.urssaf.fr](https://www.autoentrepreneur.urssaf.fr/) et [impots.gouv.fr](https://www.impots.gouv.fr/). Rappel : la micro Decoscale existe déjà, donc l'ACRE est sans objet.
- **Cookies et pixel Meta** : une bannière de consentement conforme est obligatoire. → [CNIL](https://www.cnil.fr/fr/cookies-et-autres-traceurs).
- **Marquage CE, GPSR, jouets (EN 71), batteries (UN38.3)** : à exiger du fournisseur.

## 6. Désaccords entre les vidéos et choix retenu

| Sujet | Position A | Position B | Notre choix |
|---|---|---|---|
| Structure Meta | Budget par campagne (CBO), ciblage large (vidéos 06, 21) | Budget par ensemble de pubs (ABO), intérêts (vidéo 26) | ABO pendant le test (contrôle du budget), ciblage large + 1 ensemble par intérêt en comparaison |
| Budget de test | 25-50 €/j (vidéos 03-bis, 20) | 100-200 €/j (vidéo 06) | 30-45 €/j par produit, environ 200 € par produit |
| Canal | Meta d'abord (la plupart des vidéos) | Google Shopping d'abord (vidéos 12, 24, 33) | Meta d'abord, Google en test sur le produit validé |
| Copier les concurrents | « Copier-coller » (vidéos 01, 15, 20) | S'inspirer sans copier (vidéos 03-bis, 12, 14, 21, 32, 40) | S'inspirer de la structure, tout refaire nous-mêmes |
| Bundles | Indispensables (vidéos 05, 14, 31) | Ont fait baisser la conversion (vidéo 12) | On les teste, on ne les impose pas |
| Payant ou organique | Organique IA (vidéos 35, 38, 41) | Les likes ne sont pas des ventes (vidéo 37) | Payant d'abord, organique en bonus avec les mêmes créas (Reels, TikTok) |
| Volume de créas | 3-5 par ensemble (vidéo 26) | 100-150 par jour (vidéo 36) | 9 à 15 au départ, puis 3 à 5 nouvelles par semaine |
| Délai de livraison | 8-15 j acceptés (Chine, vidéos 04, 08, 20) | Stock rapide = avantage décisif (vidéo 12) | Stock UE ≤ 3 j (9 j maximum) |

## 7. Outils cités les plus utiles pour nous

| Outil | Usage | Statut |
|---|---|---|
| SEMrush | Volumes US/FR, CPC, score de niche, trafic des concurrents | ✅ abonné |
| Bibliothèque publicitaire Meta | Pubs actives et ancienneté en France | gratuit |
| Google Trends | Saisonnalité sur 5 ans | gratuit |
| TrendTrack (+ connexion MCP à Claude) | Boutiques US en croissance, best-sellers | à décider (1 mois) |
| Claude | Recherche, textes, sections Liquid, prompts de créas | ✅ |
| Nano Banana (Pro) / GPT Image | Visuels, statiques, images de référence | ✅ |
| Higgsfield / Seedance | Vidéos IA | ✅ |
| CapCut | Montage | gratuit |
| Klaviyo ou Omnisend | E-mails automatiques | version gratuite |
| App Facebook & Instagram de Shopify | Pixel + API de conversion | gratuit |
| Pixel Helper | Test du pixel | gratuit |
| AutoDS / CJ / BigBuy | Fournisseur avec stock UE | à choisir |

## 8. Index des résumés
Voir [`README.md`](README.md).
