# Passation vers une session locale (Claude Desktop / Claude Code avec Chrome)

> Généré le 05/10/2026 depuis la session cloud. À coller en entier dans la nouvelle session, ou à lire dans le dépôt : `nassuka/ecom`, branche `claude/confident-rubin-fpb7cf` (fichier `docs/passation-session-locale.md`).
> Aucun identifiant, jeton ou mot de passe dans ce document. L'adresse du serveur TrendTrack (`https://api.trendtrack.io/v1/mcp`) est publique.
> Règle de lecture : **fait sourcé (vu dans un outil ou une capture)** ≠ **estimation**. Ce qui est « non vérifié » n'a pas été vu.

## 1. Contexte du projet
- Porteur : débutant en e-commerce, en France, micro-entreprise existante (activité Decoscale, menée en parallèle). Le compte bancaire pro de la micro sert aussi à la boutique (un sous-compte dédié est conseillé, pas obligatoire).
- Objectif : boutique Shopify pour le Q4 2026 (Black Friday 27/11/2026, Cyber Monday 30/11, dernières commandes de Noël vers le 15-18/12), marché francophone au lancement : France, Belgique, Luxembourg, Monaco (Suisse et Andorre plus tard).
- Modèle : **dropshipping pur**. Aucun stock acheté : le client commande sur la boutique, la commande est transmise au fournisseur, qui expédie directement au client. « Stock UE » = stock du fournisseur dans un entrepôt européen (livraison ≤ 3 j idéal, 9 j max). Le coût à comparer = ce que le fournisseur facture par commande (produit + livraison vers le client).
- Budget de départ : 1 000 € (environ 650 € de pub Meta de test, le reste en outils, échantillons, médiateur de la consommation, domaine). Meta Ads en priorité, Google Ads (Shopping) en test.
- Outils : SEMrush (abonnement actif), TrendTrack (forfait Professional pris le 05/10/2026, connecteur MCP branché), AutoDS pas encore, IA pour les créas (Higgsfield, Seedance, Nano Banana), Claude.
- Contraintes produit : petit colis, effet waou, résout un problème ou fort côté cadeau/émotion, aucune allégation santé / minceur / repousse, conformité CE / GPSR / UN38.3 (batteries) / DEEE.
- Conventions : tout en français ; chiffres du web sourcés ; fiscal et juridique toujours « à vérifier » avec la source officielle.
- Décisions prises : pas de 2e micro-entreprise (on ajoute l'activité « vente à distance » à la micro) ; cotisations micro d'environ 12,3 % du chiffre d'affaires (à vérifier sur autoentrepreneur.urssaf.fr) ; pub et marchandises non déductibles en micro.

## 2. Calendrier (au 05/10/2026)
- Objectif révisé : **produit choisi avant le 08-09/10**, page du 1er produit en ligne vers le **16/10**, **1er test Meta vers le 20-23/10**.
- À faire par le porteur (reporté, « avec la tête reposée ») : ajouter l'activité de vente à distance à la micro-entreprise ; créer le Meta Business Manager et le compte publicitaire ; acheter le nom de domaine ; commander des échantillons une fois le produit choisi.
- Noms de boutique étudiés (domaines .fr/.com/.eu vérifiés libres au 02/10 par DNS seulement, à confirmer à l'achat ; INPI et EUIPO à vérifier) : **Nidette** (recommandé, cocooning / cadeau), Douce Pause, Rubanie, Cocon Malin, Jolie Pioche ; réserve animaux : Pattelune. Détail : `docs/nom-boutique.md`.

## 3. Ce qui a été décidé le 05/10
- Le porteur a demandé d'**oublier tous les produits cherchés avant** (short-list de 10, niches 40+, masque chauffant yeux, lampe chauffe-bougie, châle chauffant) et de repartir d'une **recherche produit automatisée avec TrendTrack + AliExpress**. Ces fichiers sont gardés comme historique (marqués archivés), pas comme candidats.
- Nouveau protocole (section 8), avec TrendTrack à la place de Minea.
- Réponses de calibration (Étape 0) à utiliser, **à confirmer par le porteur** : niche = « peu importe » (défaut : bien-être, maison et confort, animaux, beauté) ; marché = France ; niveau = débutant ; budget pub = environ 650 € pour les tests, entre 500 et 1 500 € par mois ; source = TrendTrack (connecté) + AliExpress, Alibaba facultatif.
- Point de tension à signaler au porteur : son protocole demande un coût fournisseur ≤ 15 € et une marge ×4, mais le projet exige un fournisseur avec stock UE. Constaté le 02/10 sur AliExpress (filtre « Expédié depuis l'Union européenne ») : les prix UE sont souvent 1,5 à 2 fois ceux de la Chine (masseur yeux ~31 €, lampe ~31 €, masques USB simples 14 €). À arbitrer : ≤ 9 jours depuis la Chine en express, ou relever la limite de coût.

## 4. Enseignements conservés des sessions précédentes
**Formules de marge** (frais de paiement 3 %, cotisations 12,3 %, TVA non facturée en franchise ; à vérifier) :
- marge avant pub = prix − coût − 3 % du prix − 12,3 % du prix ; **ROAS d'équilibre = prix ÷ marge avant pub**.
- Coût maximum par commande pour un ROAS d'équilibre de 2,5 : prix 59,95 € → 26,8 € ; 54,90 € → 24,5 € ; 49,90 € → 22,3 € ; 44,90 € → 20 € (ROAS 2,0 : 20,8 / 19,1 / 17,3 €).
- Le coût d'acquisition d'un achat sur Meta en France tourne autour de 15 à 30 € (affirmation de formations).

**Méthode retenue (synthèse des 39 vidéos de formation)** : voir `formation/synthese.md`. Points clés :
- ordre d'importance : produit, offre, créas, page produit, réglages pub ; la créa fait 56 à 80 % du résultat ;
- test Meta : 1 campagne Ventes, 1 ensemble de pubs par angle à 10-15 €/j (ABO), 3 créas par ensemble, ne rien toucher 48-72 h ; stop-loss d'environ 150-200 € par produit ; augmenter de 15-20 % par jour un gagnant sur 3 jours glissants ;
- toujours un angle « cadeau » pour le Q4 ; offres en packs 1/2/3 à tester ; flux e-mail (panier abandonné en 3 mails, post-achat) avant la 1re pub ;
- à ne pas reproduire (illicite en France, à vérifier) : faux avis, faux témoignages générés par IA, prix barrés fictifs (référence légale : prix le plus bas des 30 derniers jours), cases payantes pré-cochées, fausse rareté, fausses urgences (« on ferme à cause des droits de douane »), vidéos de concurrents réutilisées sans droits.

**Astuces d'outils**
- Bibliothèque publicitaire Meta : elle cherche seulement dans le **texte des pubs** (pas dans les images) ; mettre l'expression entre guillemets pour la phrase exacte ; chaque pub affiche la date de début, parfois « Temps actif total » et « Impressions : <100 » (Transparence UE).
- SEMrush : « Keyword Overview » (menu SEO) accepte jusqu'à 100 mots-clés ; choisir la base de données (US ou FR) avant de lancer ; « Update metrics » pour charger difficulté et CPC ; les Français emploient parfois d'autres mots (« masque chauffant yeux » 1 600 recherches/mois contre « masseur yeux chauffant » sans volume).
- AliExpress : filtre « Shipping from : European Union » (« Shipped locally, no extra duties »). CJ Dropshipping : filtre « Ship From » (Allemagne, « More » pour d'autres pays) ou « post a sourcing request ».
- Messages types pour les fournisseurs (dropshipping, en anglais) : `fournisseurs/stock-ue-top5.md`, section finale.

## 5. Connecteur TrendTrack (état)
- Connecté via claude.ai (connecteur personnalisé), forfait Professional (période du 05/10 au 05/11/2026), 10 000 crédits au départ, **9 059 restants** à la fin de la session cloud.
- Outils disponibles : `search_shops`, `search_ads`, `search_advertisers`, `search_tiktok_library`, `search_google_ads_library`, `find_winning_products`, `find_similar_shops`, `scan_ad`, `lookup`, `lookup_filter_ids`, `daily_radar`, `analyze_shop_emails`, `search_emails`, `creative_inspiration_pack`, boards, brandtracker, `check_credits`.
- Pièges rencontrés : `search_shops` n'accepte pas de filtre de croissance de trafic ; `search_ads` n'a pas de filtre de prix de best-seller ; `max_ads_per_brand` doit valoir 1 (ou être omis) ; les grosses réponses sont enregistrées dans un fichier local (à lire avec python) ; pour les pubs ciblant seulement les États-Unis, la portée et les dépenses ne sont pas disponibles (transparence UE seulement) : juger sur la durée de diffusion, le nombre de pubs et de variantes ; `find_winning_products` renvoie surtout de grandes marques ; les chiffres de ventes de `search_shops` sont des estimations (certains incohérents avec la portée).
- Méthode qui a marché : `lookup_filter_ids` (catégories, ex. Home & Interior Decor 789, Household Supplies 820, Pets & Animals 1031, Home Improvement 804, Gadgets 420, Kitchen & Dining 824, Fitness 260) → `search_shops` (niche_id, min_active_ads 8, max_products_count 40, main_market_countries US, min_monthly_sales 15000, creation_date_from 2025-06-01, tri estMonthlySales, limit 30) → filtre local sur le prix des best-sellers (29 à 85 $) et exclusion des compléments, vêtements, livres numériques → `search_ads` par domaine (tri longestRunning, limit 2 à 3).

## 6. Résultats de la recherche TrendTrack du 05/10 (sans Chrome)
**Aucun produit validé** : coût fournisseur, Google Trends, TikTok et concurrence française complète non vérifiés.

Les 6 pistes (détail aussi dans `recherche-produit/trendtrack-2026-10-05.md`) :
| Piste | Boutique | Prix | Pubs vues | Ventes estimées | Remarque |
|---|---|---|---|---|---|
| Diffuseur de parfum automatique à brume | olfiastudio.com | 69,90 $ (cire parfumée 39,90 $) | 157 pubs ; les plus longues 79-82 j ; 41 à 67 variantes ; portée 30 j 487 000 ; ciblage dont FR | 677 k$/mois, créée 06/2026 | produit courant, recharges en vente additionnelle |
| Harnais chien sans traction, une boucle | dogshood.com | 39,99 $ | 819 pubs ; les plus longues 110-122 j ; US/CA | 2,1 M$/mois, créée 08/2025 | tailles/retours, marché FR probablement encombré |
| Appareil de renforcement avant-bras | irond.shop | 34,99 à 44,99 $ | 47 pubs ; les plus longues 5 j ; AU/CA/GB/US | 484 k$/mois, créée 04/2026, trafic +34 513 % (anomalie probable) | aucune pub FR trouvée ; produit viral |
| Pomme de douche haute pression | riviage.com | 69,99 $ | 49 pubs ; les plus longues 80 j | 244 k$/mois, créée 07/2026 | portée faible (46 000 en 30 j) |
| Panier-griffoir pour chat | stimulicat.com | 79,95 $ (50 % de réduction) ; harnais 37,95 $ | 462 pubs ; les plus longues 264-276 j ; ciblage dont FR, BE, LU | 2,7 M$/mois | preuve très forte mais encombrant, > 69 $, fausse urgence dans les pubs |
| Sacs à pain en cire d'abeille | lorineofficial.com, loafguard.shop, hearthfold.store, doughdissolve.com | 30 à 54 $ | pubs non confirmées par domaine | Lorine 1,0 M$/mois, LoafGuard 536 k$ | aucune pub FR trouvée ; effet waou faible |

Autres boutiques repérées (petit catalogue, au moins 8 pubs, marché US ; ventes = estimations TrendTrack) : geniecloth.com (chiffon de nettoyage, 29,99 $ les 5, 75 000 unités/mois) ; truecleanhome.com (cartes anti-acariens 29,99 $, 31 550 unités) ; xteink.com (liseuse de poche 69 $, 3,7 M visites, 263 pubs) ; memo-mind.com (clip lunettes de soleil 69 $) ; halosphere.store (cube 34,99-49,99 $, 41 pubs) ; trydrinksmoked.com, shopellisellis.com, mizuroglass.com (verres rotatifs fumés 39,99-60 $, **fragiles**) ; oakandsmokeco.com (gobelet bois personnalisé 49,95 $, 3,2 M$/mois) ; pawira.com (filtres de fontaine pour animaux 39,99 $, 1,77 M$/mois) ; doggyspout.com (fontaine sans fil 74,95 $) ; pawras.com (harnais chat 49,90 $) ; whisko.co (LitterGuard Pro 39,99 $) ; dawnbands.com (bracelet réveil 39,99 $) ; steadystepp.com (équilibre 69 $) ; shayla.co (draps rafraîchissants 69 $) ; trykami.com (abat-jour Kami 55 $, 10 pubs) ; boxofjoy.shop (**calendrier de l'Avent squishy « dumpling » 2026**, 218 pubs, portée 7 j +257 000) ; xbotgo.com (caméra 4K IA pour sport d'équipe).
Écartés : compléments, soins, vêtements (tailles), dispositifs santé (anti-étouffement, ronflement, prothèse dentaire, lumière rouge), kits de survie, produits encombrants ou fragiles, produits à promesses de santé (bouteilles/baguettes de cuivre), couteaux, grandes marques.

## 7. Autres éléments utiles
- Fichiers du dépôt (historique) : `docs/journal.md`, `docs/roadmap.md`, `docs/budget.md`, `docs/entreprise-juridique.md`, `formation/synthese.md` et `formation/resumes/`, `recherche-produit/` (relevés SEMrush et bibliothèque Meta du 02/10, archivés), `fournisseurs/`.
- Constat du 02/10 sur des produits archivés, utile comme repère de prix : masseur yeux Renpho 54,99-99,99 € sur Amazon.fr / Google ; lampe chauffe-bougie Warmora 44,90-52,90 € contre 19,99 € sur Amazon.fr ; châle chauffant Middo 59,95 €, Aloueta 69,99 $.
- Chrome : dans Claude Desktop, le connecteur `claude-in-chrome` est activé (capture du porteur). Pour limiter les risques : fermer les onglets sensibles (banque, administration Shopify, Meta Business Manager) pendant une recherche autonome ; ne jamais coller un jeton dans une conversation.

## 8. Protocole à suivre (donné par le porteur, avec TrendTrack à la place de Minea)
> À suivre à la lettre par l'assistant, dans une session où **Chrome est piloté** (extension Claude in Chrome) et où le connecteur **TrendTrack** est actif. Adaptation décidée : la branche « Minea » est remplacée par **TrendTrack** (connecteur MCP déjà branché, forfait Professional, 10 000 crédits au 05/10/2026).

**Mode : autonome.** Aucune validation entre les étapes ; le livrable final seulement. Seules attentes de réponse : la vérification du connecteur si un problème est détecté, et les questions de l'Étape 0.

## Règles absolues
1. Ne jamais inventer une donnée : chaque prix, note, nombre d'avis, nombre de pubs doit avoir été vu sur une page réellement ouverte. Sinon : « non vérifié ».
2. Ne jamais donner un lien non ouvert.
3. Mieux vaut 5 produits solides et vérifiés que 12 approximatifs.
4. Expliquer en une ligne à chaque changement d'étape.
5. Si un site bloque ou demande une connexion absente : le signaler en une ligne et continuer avec les autres sources.

## Pré-requis : vérifier Chrome
- Chrome détecté : « Connecteur OK, on peut démarrer. » puis Étape 0.
- Sinon guider : ouvrir Chrome, installer l'extension **Claude in Chrome** (Chrome Web Store), activer la connexion (Cowork), répondre « c'est bon ». Ne pas continuer avant.

## Étape 0 : calibration (5 questions en un seul message, puis attendre)
1. Passion, centre d'intérêt ou niche ? (défaut « peu importe » : santé et bien-être, maison et confort, animaux, beauté)
2. Marché visé ? (défaut : France)
3. Niveau en e-commerce ? (défaut : débutant)
4. Budget publicitaire mensuel ? (défaut : 500 à 1 500 €)
5. Source : A. AliExpress, B. Alibaba, C. outil de pubs (TrendTrack ici, à la place de Minea), ou plusieurs.

## Étape 1 : 8 à 10 produits candidats
- **A. AliExpress** (fr.aliexpress.com) : chercher par problèmes, bénéfices recherchés, caractéristiques ; Bestsellers, Tendances, Recommandés. Relever prix, commandes, note fournisseur, avis. Écarter < 4,5 étoiles ou < 50 avis.
- **B. Alibaba** : mêmes angles ; relever aussi MOQ et prix au 1er palier ; privilégier Verified / Gold Supplier ; signaler les MOQ élevés.
- **C. TrendTrack** (à la place de Minea) : marché prioritaire États-Unis, pubs actives, boutiques en forte croissance (Top scaling), produits gagnants ; vérifier la richesse créative disponible.

## Étape 2 : validation de la demande (par produit)
1. Facebook Ads Library : nom en anglais et français, pubs actives, nombre d'annonceurs.
2. TikTok Ads Library.
3. Recherche organique TikTok (volume de vidéos et de vues).
4. Google Trends (12 mois et 5 ans) : evergreen ou saisonnalité.
**Juste milieu** : zéro concurrent actif = écarté ; quelques concurrents actifs = gardé ; des dizaines saturés = écarté.

## Étape 3 : filtres éliminatoires (raison en une ligne si écarté)
1. Coût fournisseur ≤ 15 €.
2. Prix de vente réaliste de 39 à 69 € (prix unitaire, jamais le prix d'un pack).
3. Marge ×4 minimum (×5 ou ×6 idéal) : le coût par achat en pub tourne autour de 15 à 30 € en France.
4. Compact et léger.
5. Compréhensible en moins de 3 secondes sans le son.
6. Au moins 2 critères sur 4 : effet waou, problème douloureux, avant-après, innovation.
7. Déjà prouvé sur un marché (idéalement US), pubs actives confirmées.
8. Potentiel d'upsell.
**Exclusions** : produits dangereux, médicaux ou à promesses de santé, contrefaçons / marques / licences, fragiles, encombrants ou lourds, trop nichés.

## Étape 4 : notation sur 10 (un point par critère)
Audience large · compréhensible en 3 s · fort potentiel visuel · concurrence dans le juste milieu avec pubs actives · marge ×4 · fournisseur fiable · evergreen · upsell · haute valeur perçue · coût < 15 €.
**VALIDÉ** : note ≥ 8/10 ET pubs actives confirmées ET coût < 15 €. Dans le livrable : note finale et point faible seulement.

## Étape 5 : livrable (dans la conversation)
Format par produit : numéro, emoji, nom ; 2-3 phrases ; coût fournisseur ; prix de vente conseillé ; marge ×X ; fournisseur (note, avis) ; potentiel marketing (waou, démonstration, viralité en étoiles) ; concurrence (annonceurs actifs, pubs en cours) ; tendance Google ; upsell ; score X/10 ; point faible ; lien fournisseur ouvert.
Puis **Top 3** (pourquoi, principal risque) et la question exacte : **« Avec quel produit souhaites-tu qu'on aille plus loin ? »**

## Contraintes du projet à garder (CLAUDE.md), sauf avis contraire du porteur
Dropshipping pur ; fournisseur avec stock UE (≤ 3 j idéal, 9 j max) ; pas d'allégation santé ; Q4 2026 (Black Friday 27/11) ; le coût fournisseur = ce qui est facturé par commande, livraison comprise. Point de vigilance : un coût ≤ 15 € avec stock UE est difficile (les entrepôts UE coûtent souvent 1,5 à 2 fois plus que la Chine, constaté sur AliExpress le 02/10).

## 9. Prochaines actions pour la session locale
1. Vérifier Chrome et TrendTrack (`/chrome` et `/mcp` en Claude Code ; connecteurs dans Claude Desktop).
2. Poser les 5 questions de calibration (ou confirmer les réponses de la section 3), puis lancer le protocole **sans autre interruption**.
3. Valider d'abord les 3 pistes de la section 6 (diffuseur, harnais, appareil avant-bras) : coût rendu en France sur AliExpress et Alibaba (stock UE), bibliothèque Meta France, TikTok (bibliothèque et organique), Google Trends 12 mois et 5 ans.
4. Élargir avec TrendTrack, AliExpress (Bestsellers, Tendances) et si possible le calendrier de l'Avent / idées cadeaux de Noël (fenêtre courte : vendre avant le 25/11).
5. Présenter le livrable au format de l'Étape 5, puis **coller le résultat dans la session cloud** (ou dans le dépôt) pour mise à jour de `docs/journal.md`, `docs/roadmap.md` et du dossier `recherche-produit/`.
