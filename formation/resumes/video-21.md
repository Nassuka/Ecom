# Vidéo 21 — Tutoriel Facebook (Meta) Ads complet : configuration du compte, tracking, première campagne Ventes, lecture des données, IA

- **Auteur / intervenant** : media buyer / fondateur anglophone (probablement Davey Fogarty, Daily Mentor — « Davey's columns », exemple de la marque « The Oodie » qu'il cite comme sa marque ; affirme avoir dépensé plus de 200 M$ en Facebook Ads sur ses propres marques). Lien vers sa formation « Daily Mentor » à la fin.
- **Langue** : anglais
- **Longueur approximative** : ~40 000 caractères
- **Thème principal** : mettre en place Meta Ads proprement (Business Manager, page, Instagram, compte pub, paiement, 2FA, pixel/dataset via Shopify), construire une campagne Ventes simple en ciblage large, créer les annonces, publier sans risque, lire les métriques après 24-72 h, piloter au ROAS cible, outils IA.

## En bref
Tutoriel sérieux et sobre, orienté « compte réel ». Message central : la configuration et le tracking d'abord, puis **une campagne Ventes manuelle, budget au niveau campagne (Advantage campaign budget), ciblage large (pays seulement), placements automatiques**, 3-5 créas d'angles réellement différents, améliorations automatiques Meta désactivées. Après lancement : ne pas toucher trop tôt, lire l'entonnoir (impressions → clics → vues de page → ajouts panier → achats), piloter chaque matin au ROAS des 3 derniers jours vs ROAS cible, monter/baisser de 10-20 %, et surtout **ajouter de nouvelles créas** en continu. Contredit la méthode « 5 intérêts » de la vidéo 20.

## Points clés (affirmations de l'auteur, non vérifiées)

### 1. Configuration du compte (business.facebook.com)
- Utiliser son **vrai profil Facebook** (pas de faux profil : vérifications d'identité ultérieures).
- Créer un **portefeuille business** avec des infos propres et cohérentes avec la marque ; email réellement consulté (alertes, facturation, vérifications).
- Ajouter/créer la **page Facebook** (photo de profil, bannière : la page ne doit pas paraître vide), connecter **Instagram** (placements Instagram + abonnés).
- Créer le **compte publicitaire** avec un nom clair (« Marque – Pays ») ; **fuseau horaire et devise** à choisir avec soin (quasi impossibles à changer).
- **Moyen de paiement** autorisé pour l'entreprise ; ne pas multiplier les paiements échoués (risque de bannissement).
- Utilisateurs : droits minimaux nécessaires (pas d'admin pour qui consulte seulement) ; **2FA obligatoire** pour soi et les admins (un piratage = argent dépensé + compte banni).

### 2. Tracking (Events Manager)
- « Pixel » = désormais « dataset / source de données / web events ». Doit voir : ViewContent, AddToCart, InitiateCheckout, Purchase.
- Sur Shopify : passer par le **canal Facebook & Instagram** (même business, page, Instagram, compte pub, dataset) plutôt que coller du code.
- Vérifier avec l'outil **Test events** (visiter, voir produit, ajouter au panier) et l'extension Chrome gratuite **Meta Pixel Helper**. But : ne pas dépenser 3 jours de budget sans que les achats soient suivis.

### 3. Campagne (niveau campagne)
- Objectif **Ventes** (pas Trafic, Interaction ou Vues vidéo, même si c'est « moins cher »). Catégories spéciales (crédit, emploi, logement, politique) : non concerné.
- Nommage : « Sales – produit – pays – broad – mois ».
- Choisir la configuration **manuelle** plutôt qu'Advantage+ pour apprendre (Advantage+ « pas mauvais en soi »). Test A/B désactivé, **catalogue désactivé** (première campagne = campagne large avec créas normales).
- **Budget au niveau campagne (Advantage campaign budget / CBO)**, budget quotidien. Montant selon prix, marge et CPA admissible : 3 $/jour sur un produit à 100 $ = trop peu pour apprendre ; 500 $/jour avec créas non testées = brûler de l'argent. Exemple : produit à 100 $ → 20-50 $/jour ; « si vous ne savez pas, mettez 10 $ ».

### 4. Ad set (niveau ensemble de publicités)
- Lieu de conversion : **site web** ; dataset = celui vérifié ; événement : **Achat**. L'avertissement « pas assez d'activité » disparaît avec les premiers achats si les autres événements remontent.
- **Ciblage large** : uniquement le **pays/la zone** où l'on livre ; âge et genre ouverts sauf raison réelle (les gens achètent aussi des cadeaux). Plus d'empilement d'intérêts ni de lookalikes pour un débutant : « c'est la créa qui cible » (ex. mentionner Netflix dans la créa plutôt que cibler l'intérêt Netflix).
- Plus tard : **exclure les acheteurs** (audience personnalisée) de la prospection.
- **Placements Advantage+ (automatiques)** OK si les créas sont adaptées à tous les formats.

### 5. Annonce (niveau ad)
- Identité : bonne page FB + bon compte Instagram.
- Avant de publier : **3-5 angles créatifs vraiment différents** (problème/solution, fondateur qui explique, avis UGC, démonstration produit) ; idéalement vidéos + statiques ; certains lancent avec 10-30 créas.
- Inspiration : **Meta Ad Library**, marques que l'on aime, tri par impressions ; souvent un selfie vidéo + des visuels Canva suffisent.
- **Format** : tout produire en **9:16** avec une **zone de sécurité 4:5** au centre (textes et CTA dedans) ; si on n'a que du 4:5, flouter/colorer les bords pour faire un 9:16. Vérifier l'aperçu de chaque placement.
- **Désactiver toutes les « améliorations créatives » / Advantage creative** (recadrages, surimpressions) pour savoir ce qui marche vraiment.
- Texte principal court, collé à la créa : problème/désir → produit/offre → raison d'agir maintenant (ex. « 2 achetés = −10 % ») ; faire générer 5 variantes par une IA ; pas d'allusions à des attributs personnels sensibles, pas d'allégations trompeuses. Un seul texte par annonce (pas les 5 suggestions de Meta). Titre important, description secondaire, CTA + URL (tester le lien sur mobile, cohérence offre pub/page). UTM facultatifs.
- Dupliquer l'annonce **dans le même ad set** pour chaque nouvelle créa.

### 6. Publication sûre
- Publier puis **mettre la campagne en pause pendant la revue**, la réactiver quand on peut surveiller ; vérifier le budget (pas un zéro de trop).
- Annonce refusée : lire la raison, corriger (l'IA peut aider), faire appel si injuste ; **ne jamais contourner** (orthographe bizarre, nouveau compte) → problèmes durables.

### 7. Les 24-72 premières heures et le diagnostic
- Vérifier : approuvée, active, dépense, impressions, clics, bonne page, événements remontés. **Pas de dépense** = facturation, audience ou restriction, pas la créa.
- **Colonnes personnalisées** (à enregistrer) : diffusion, montant dépensé, impressions, couverture, CPM, clics sortants, CTR sortant, coût par clic sortant, vues de page de destination, ajouts au panier, achats, coût par achat, valeur de conversion, ROAS (+ taux de conversion, panier moyen).
- Diagnostic par l'entonnoir : impressions sans clics → créa/offre/angle ; clics sans vues de page → vitesse, qualité de clic, tracking ; vues sans ajouts panier → offre, prix, confiance, voire produit ; achats → rentable et scalable ?
- **Ne pas modifier trop tôt** (audience, créa, budget, objectif après 10 $) ; seule action admise : **ajouter des créas** (duplication).
- Exemple de règle : CPA cible 50 $ ; une annonce à 150 $ dépensés sans achat est « en difficulté », une à 15 $ manque juste de données. Souvent inutile de couper : Meta arrête de dépenser sur les perdantes et concentre ~80 % du budget sur la meilleure créa.

### 8. Pilotage au ROAS
- Construire un **calculateur de rentabilité** (ex. Google Sheets + Gemini) : prix, panier moyen, coût produit, fret, emballage, préparation, livraison, frais de paiement, remises → marge avant pub, **CPA et ROAS d'équilibre**, ROAS cible pour **20 % de marge nette**.
- Routine : chaque matin, regarder le **ROAS sur les 3 derniers jours** (compte neuf = forte variance journalière). Sous la cible → baisser la dépense ; au-dessus → **augmenter de 10-20 %** puis laisser se stabiliser. Pas de vente → revoir site, offre, créas (« 90 % du métier »). Le travail du media buyer = **injecter sans cesse de nouvelles créas** dans cette structure large.

### 9. IA pour les pubs
- ChatGPT : coller des captures pour débloquer un réglage (limité).
- **Triple Whale** (app Shopify, assistant « Moby ») et **Manus** : connectés au compte pub, analysent performances et créas gagnantes, proposent de nouvelles idées ; Manus peut aussi créer des landing pages.
- **Higgsfield** : générer une image, y remplacer un objet par son produit, l'animer en vidéo pour la pub.

## Outils et apps cités
| Outil | Usage | Prix |
|---|---|---|
| Meta Business (portefeuille), Ads Manager, Events Manager | configuration, campagnes, tracking | gratuit (pub payante) |
| Canal Facebook & Instagram de Shopify | pixel/dataset + API | gratuit |
| Meta Pixel Helper (Chrome) | vérifier les événements | gratuit |
| Meta Ad Library | inspiration créas | gratuit |
| Canva | statiques | — |
| ChatGPT / Claude | copy, aide aux réglages | — |
| Google Sheets + Gemini | calculateur de ROAS d'équilibre | — |
| Triple Whale (Moby) | analytics + IA connectée | non donné |
| Manus | agent IA connecté à Meta | non donné |
| Higgsfield | créas IA image/vidéo | non donné |
| Daily Mentor | formation de l'auteur | non donné |

## Exemples de produits / boutiques cités
- The Oodie (sweat-couverture à capuche) utilisé comme exemple fil rouge ; « Calming Blankets US » comme exemple de nom de compte.

## Ce qu'on retient pour notre projet
- **Check-list de configuration Meta à faire dès maintenant** (avant le Q4) : vrai profil, portefeuille business propre, page FB + Instagram remplis, compte pub en **EUR / fuseau Paris**, carte dédiée, 2FA, dataset via le canal Shopify, test des événements (Pixel Helper). Un compte neuf qui se fait restreindre en novembre serait catastrophique.
- **Structure de test simple et adaptée à 1 000 €** : 1 campagne Ventes CBO, ciblage large **France + Belgique + Suisse + Luxembourg/Monaco** (selon livraison), placements auto, 3-5 créas d'angles différents (problème/solution, démonstration, UGC IA, « cadeau de Noël »), budget de départ ~20-30 €/jour, améliorations Meta désactivées.
- **Format créa** : produire nos vidéos IA (Seedance/Higgsfield) et images (Nano Banana) en **9:16 avec zone utile 4:5**.
- Avant de lancer : construire notre **calculateur de ROAS d'équilibre** (prix, coût produit, livraison UE, frais Shopify Payments, TVA éventuelle, remise BF) — à mettre dans `docs/budget.md`.
- Pilotage : décision sur 3 jours glissants, +10-20 % si au-dessus du ROAS cible ; priorité absolue = **renouveler les créas** (l'IA rend cela peu coûteux).
- Mettre la campagne en pause pendant la revue ; ne jamais contourner un refus.

## Points de vigilance
- Désaccord avec la vidéo 20 (Jonathan) : lui recommande 5 ad sets d'intérêts à 10 €/jour (ABO) ; ici **CBO + ciblage large**. Les deux sont des pratiques courantes ; la seconde est plus simple et plus cohérente avec l'algorithme actuel selon l'auteur. À trancher par nous (on peut tester large d'abord).
- Le « 200 M$ dépensés » est invérifiable ; la fin de vidéo renvoie vers une formation payante.
- Les noms et menus de Meta changent souvent (Advantage+, dataset…) : suivre la logique plus que les écrans.
- Pubs en France : mentions sur les prix barrés/réductions (règles sur les annonces de réduction, prix de référence = prix le plus bas des 30 derniers jours, Code de la consommation L112-1-1 — à vérifier) et pas d'allégations trompeuses ; contenu IA réaliste : vérifier la politique Meta d'étiquetage IA.
- Les chiffres d'exemple sont en dollars et pour des produits à 100 $ ; à recalculer pour un panier de 30-50 €.
