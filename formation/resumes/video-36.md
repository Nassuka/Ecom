# Vidéo 36 — Pubs images IA en volume : Claude + recherche approfondie ChatGPT (« Breakthrough Advertising ») + Higgsfield / Nano Banana Pro

- **Auteur / intervenant** : e-commerçant anglophone (US), non nommé dans la transcription ; se réclame de « Mark Builds Brands » et d'Alex Hormozi.
- **Langue** : anglais. **Longueur** : ~28 000 caractères.
- **Thème principal** : processus en deux outils (Claude + Higgsfield) pour produire **des dizaines de pubs statiques par jour** à partir d'une recherche marché approfondie.

## En bref
L'auteur dit avoir généré **820 000 $ en 4 mois** (depuis avril) avec cette méthode, dont une campagne de pubs statiques IA à **55 000 $ dépensés pour 73 000 $ de CA (ROAS 1,3, rentable grâce à de fortes marges)**. Processus :
1. **Documents de base** (marché, produit, avatar) ;
2. **recherche approfondie** dans ChatGPT guidée par un document-cadre tiré de *Breakthrough Advertising* (Eugene Schwartz) : désirs, niveau de conscience du marché, sophistication du marché, mécanismes ;
3. Claude transforme cette recherche, avec deux prompts maîtres (« structure » et « moteur émotionnel »), en **30 prompts d'images** pour **Nano Banana Pro dans Higgsfield** (4:5, 4K) ;
4. contrôle qualité et itérations.

Démo sur des **pastilles dentifrice** (« No BS toothpaste tablets »).

## Points clés (affirmations de l'auteur)
1. **Documents de base** (méthode de Mark Builds Brands) : stocker tout le contexte (étude de marché, produit, avatar…) dans des documents fournis à chaque nouvelle conversation IA, pour que les angles et les pubs soient pertinents.
2. **Recherche approfondie (ChatGPT, mode Deep Research, 10-20 min)**, jugée meilleure que celle de Claude par l'auteur. Entrées : informations produit (issues de Claude) + **document-cadre « BTA »** qui apprend à l'IA ce qu'il faut chercher selon les principes de Schwartz. Sorties :
   - **3 désirs principaux** du marché ;
   - **niveau de conscience** (ce que l'audience sait du produit et de sa capacité à satisfaire ses désirs) ;
   - **sophistication du marché** (nombre de concurrents et de promesses → scepticisme → ce qu'on peut affirmer de façon crédible) ;
   - identité et croyances du client ;
   - **mécanismes** du produit (« comment il délivre le résultat » : ex. l'hydroxyapatite, « le minéral dont ton émail est déjà fait ») pour rendre la promesse crédible au lieu d'une affirmation creuse.
3. **Principe** : « les gens se moquent de ta marque, ils ne s'intéressent qu'à eux » ; voir le produit avec les yeux du client.
4. **Génération des prompts (Claude)** : recherche + **prompt « structure »** (comment rédiger les prompts d'images, leur longueur, le contexte produit et marque) + **prompt « moteur émotionnel »** (le sujet émotionnel de chaque pub) + **URL du site** (logo, couleurs, style) + **5-7 photos de référence du produit**. Demande : « **30 prompts de pubs images complètement différents** pour Nano Banana Pro ».
   - Chaque prompt = **bloc 1 fixe** (« ancre » : référence aux photos, apparence exacte du produit) + **bloc 2 variable** (contenu émotionnel de la pub).
5. **Higgsfield** :
   - Nano Banana Pro, **format 4:5** (ou 1:1), **qualité 4K**, lot de 1, **~4 crédits par image** ;
   - charger les **5-7 meilleures photos produit** en référence (au-delà, trop d'informations dégradent le résultat) ;
   - copier-coller les prompts un par un ;
   - échec « NSFW » = relancer, sans coût en crédits.
6. **Contrôle qualité** : écarter ou corriger les pubs sans contexte (ex. un homme qui met les pastilles dans son sac de sport sans qu'on sache ce que c'est) → capture d'écran à Claude « plus de contexte » → nouveau prompt (« Entraînement à 6 h, rendez-vous client à 9 h »). Si le produit est souvent mal rendu, corriger le prompt Claude (une révision suffit en général).
7. **Angle vs format** :
   - **angle** = la raison émotionnelle d'acheter (praticité, tube qui coule, voyage et contrôle de sécurité…) ;
   - **format** = l'exécution visuelle (avant/après côte à côte, photo « native » qui ne ressemble pas à une pub, capture de SMS entre proches, fausse recherche Google, grand titre + sous-titre + photo lifestyle, encadré informatif) ;
   - varier les deux ; ensuite, **approfondir** : lots de 30 sur un format gagnant ou sur un angle gagnant.
8. **Volume** : « 100 à 150 pubs par jour à deux personnes ». Les statiques ont souvent un ROAS plus faible que les vidéos (vidéos IA dans une prochaine vidéo).

## Outils et apps cités
- **Claude** : recherche produit initiale, analyse, rédaction des 30 prompts, corrections.
- **ChatGPT Deep Research** : recherche marché selon le cadre *Breakthrough Advertising*.
- **Higgsfield + Nano Banana Pro** : génération d'images (4 crédits/image en 4K ; Artlist cité comme alternative).
- Google Drive : prompts « structure » et « moteur émotionnel », document-cadre BTA (gratuits en description).
- Livre : *Breakthrough Advertising*, Eugene Schwartz (1966).

## Exemples de produits / boutiques cités
- **Pastilles dentifrice « No BS »** (bocal, hydroxyapatite, pratique en voyage et à la salle de sport, pas de tube qui coule).
- Produits de l'auteur non dévoilés (floutés).

## Ce qu'on retient pour notre projet
- **Processus le plus directement applicable du lot à nos créas statiques Meta**, avec nos outils (Claude + Higgsfield/Nano Banana). À intégrer à `formation/` sous forme de procédure :
  1. dossier « documents de base » par produit dans `recherche-produit/` (marché FR, produit, avatar, objections) ;
  2. recherche approfondie (désirs, niveau de conscience, sophistication du marché FR, mécanismes) ;
  3. Claude → 20-30 prompts en deux blocs (ancre produit + angle émotionnel) ;
  4. Nano Banana Pro en 4:5, 5-7 photos de référence **réelles** du produit ;
  5. contrôle qualité, puis tests.
- **Grille angle × format** : idéale pour le Q4 (angles « cadeau parfait pour… », « dernière minute », « Secret Santa », « livré avant Noël » × formats « avant/après », « SMS entre proches », « photo native au pied du sapin », « recherche Google »).
- **Budget** : à ~4 crédits par image, 30 visuels coûtent peu. Les tests restent limités par le budget pub (1 000 €), pas par la production. Avec notre budget, viser **10-15 statiques + 3-5 vidéos** par produit plutôt que 150/jour.
- **Mécanisme** : chercher pour chaque produit le « comment ça marche » qui rend la promesse crédible face à un marché français déjà sollicité (sophistication).
- Les textes sur les images doivent être **en français** et relus (accents, fautes : Nano Banana se trompe parfois).

## Points de vigilance
- **Résultats invérifiables** (820 000 $ en 4 mois) ; ROAS 1,3 « rentable » seulement avec de très fortes marges, inatteignable pour un débutant en dropshipping.
- **Formats « natifs » trompeurs** (faux SMS, fausse recherche Google, photos qui « ne ressemblent pas à une pub ») : en France, toute publicité doit être identifiable comme telle (loi pour la confiance dans l'économie numérique — à vérifier) ; risque de **pratique commerciale trompeuse** si l'on simule un témoignage ou une conversation réelle (DGCCRF).
- **Allégations santé / dentaire** (hydroxyapatite, blancheur) : encadrées pour les cosmétiques (règlement (UE) 655/2013) ; un produit bucco-dentaire relève du règlement cosmétique — à vérifier.
- **Mention IA** : Meta étiquette ou demande d'indiquer certains contenus générés par IA ; l'AI Act européen prévoit des obligations de transparence — à suivre.
- 100-150 pubs par jour suppose des budgets importants pour obtenir des données par pub ; avec 20-50 €/jour, trop de pubs diluent l'apprentissage (vidéo 26 : 3-5 pubs par ensemble).
- L'auteur préfère ChatGPT pour la recherche approfondie : à comparer avec la recherche web de Claude (vidéo 29).
