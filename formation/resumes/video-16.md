# Vidéo 16 — Dropshipping de A à Z avec Claude (Opus 5.5) : produit, boutique, pubs IA en 1-2 jours

- **Auteur / intervenant** : youtubeur dropshipping anglophone non nommé (dit pratiquer depuis ~11 ans) ; vidéo tournée le 23/09/2026. Nombreux liens affiliés (Winning Hunter, Shopify, USA Drop, Omnisend, Photoroom).
- **Langue** : anglais
- **Longueur approximative** : ~40 000 caractères
- **Thème principal** : workflow complet « IA-first » : recherche produit via Claude connecté à un outil d'espionnage (Winning Hunter), recherche d'avatar, clonage de pages concurrentes en HTML puis Shopify Liquid, création de pubs UGC IA (Higgsfield + Seedance 2.5).

## En bref
L'auteur montre une boutique « gym » (sac/bouteille magnétique pour salle de sport) vendue 59 $ pour 5 $ d'achat, qui ferait 1 700-2 000 $/jour. Méthode : Claude (Opus 5.5) + connecteur MCP Winning Hunter + « skills » fournis par l'auteur pour trouver un produit prouvé, définir l'avatar client, générer homepage et page produit en HTML (Claude Design) puis les transposer dans Shopify via le connecteur Shopify, auditer la page (Photoroom), installer email/SMS (Omnisend), et produire 3-5 pubs vidéo UGC IA avec Seedance 2.5 nourri de 10-30 images de référence.

## Points clés (affirmations de l'auteur, non vérifiées)
**Critères d'un produit gagnant**
1. Résout un problème agaçant (ici : bouteille/affaires posées par terre à la salle).
2. Introuvable en magasin.
3. Bonne marge (exemple : achat 5 $, vente 59 $ ; concurrent à 69 $ avec logo).
4. Effet « wow » / compris immédiatement sans vidéo sophistiquée.
5. Petit et léger (colis).
6. **D'autres le vendent déjà et gagnent de l'argent** : un produit « saturé » l'est sur un marché donné ; il existe toujours un autre marché / un autre avatar.

**Recherche produit avec l'IA**
- Un LLM seul (« trouve-moi un produit gagnant ») donne de mauvais résultats : il faut lui donner des données (outil spy type Winning Hunter : nb d'annonces actives, date de lancement, phase de scaling, trafic, ventes estimées). La Meta Ad Library seule « ne dit presque rien ».
- Connexion de Winning Hunter à Claude en connecteur MCP personnalisé + skill « proven product hunt » + prompt fourni.
- Adapter le prompt : indiquer **la date du jour**, 5 niches d'intérêt, et la **saison** (ex. « on approche de Noël, ajoute des produits de Noël »).
- Claude rend 5-10 produits ; on vérifie soi-même : lien AliExpress (ici 4 000 commandes), boutique concurrente dans le « sales tracker » (380-650 k$ estimés), courbe de visiteurs mensuels en hausse, **249 annonces actives**, avis Trustpilot bons (= moins de risque de remboursements/chargebacks).
- Principe : ne jamais laisser l'IA travailler sans vérifier ; il faut savoir quoi vérifier.

**Avatar / recherche concurrentielle**
- Prompt fourni pour faire identifier par l'IA les avatars clients et l'angle non exploité (ex. « le minimaliste de la salle »). Utiliser **les mots des clients** dans les pubs et pages. Lire le rapport en entier, sinon on ne comprend pas les créas générées ensuite.

**Boutique**
- « Landers » (Winning Hunter) = bibliothèque des meilleures landing pages ; choisir une référence pour la homepage et une pour la page produit.
- Ne pas sur-animer la page (« on tue la conversion en en faisant trop »).
- ChatGPT (mode « work », réglé high/max) transforme la page de référence + le lien concurrent en prompt pour Claude Design → HTML ; vérifier copy, couleurs et **version mobile** ; viser 80-90 % de perfection avant export.
- Claude + connecteur Shopify + skill « clone my Shopify store » convertit le HTML en thème Liquid éditable (30-40 min). **Importer le produit dans Shopify avant** (via le fournisseur).
- Audit : Photoroom « product page grader » (score sur 35 ; la sienne 18/35) sur 7 critères (cohérence visuelle, composition, couverture des types d'images, conversion, distinctivité, SEO titre/description), puis correction des images dans Photoroom.
- Avant de dépenser en pub : flux email/SMS (panier abandonné, bienvenue, post-achat) via Omnisend (MCP disponible ; migration annoncée « jusqu'à 35 % moins cher »).

**Créas pub (vidéo UGC IA)**
1. Dans l'outil spy : pubs vidéo du concurrent triées par portée/dépense ; copier le **transcript avec timestamps** + télécharger la vidéo.
2. Claude + skill « ad teardown » : analyse pourquoi la pub gagne (sans encore générer).
3. Skill « hyperreal avatar » → prompt image ; génération dans Higgsfield avec un modèle image récent (format 9:16, qualité max ; Nano Banana Pro utilisé pour économiser des crédits).
4. Générer **10 à 30 images de référence** (avatar, décor, produit en situation).
5. Demander à Claude un prompt Seedance 2.5 de 30 s (Seedance limité à 30 s ; pour 60 s, deux prompts).
6. Seedance 2.5 « reference » : jusqu'à 50 images de référence, voix activée, 30 s, 9:16, 1080p, bitrate élevé. Sans images de référence, « les pubs sont nulles ».
7. Lancer avec **3 à 5 pubs vidéo** ; la structure Facebook Ads est renvoyée à une autre vidéo.
- Tout le workflow serait faisable « en 1 à 2 jours ».

## Outils et apps cités
| Outil | Usage | Prix |
|---|---|---|
| Claude (Opus 5.5, Cowork, Claude Design, connecteurs, skills) | recherche, avatar, pages HTML, construction Shopify, scripts pubs | non donné |
| Winning Hunter (+ MCP, « Landers », sales tracker) | espionnage pubs FB/Google/TikTok, ventes estimées, landing pages | non donné (lien affilié) |
| ChatGPT (mode work, high/max) | rédiger les prompts de design | non donné |
| Shopify + app « Claude Connector » | boutique | non donné |
| USA Drop | fournisseur/agent dropshipping (sourcing, agent privé dès 5 commandes/jour) | inscription gratuite |
| AliExpress | vérifier le produit / nb de commandes | — |
| Photoroom (product page grader) | audit et retouche des visuels | non donné |
| Omnisend | email + SMS, MCP | « jusqu'à 35 % moins cher » (affirmation commerciale) |
| Higgsfield (modèle image GPT Image 2.5, Nano Banana Pro) | avatars et images de référence | crédits |
| Seedance 2.5 | vidéo UGC 30 s à partir de références | crédits |
| Trustpilot | vérifier la qualité du produit concurrent | gratuit |

## Exemples de produits / boutiques cités
- Sac/bouteille magnétique de salle de sport (« no-backtrack magnetic gym sling ») : 59 $ vente, 5 $ achat ; concurrent à 69 $, 249 annonces actives, 380-650 k$ estimés ; 4 000 commandes AliExpress.

## Ce qu'on retient pour notre projet
- **Le workflow colle à notre stack** : SEMrush ne remplace pas un outil spy de pubs ; prévoir un mois d'abonnement à un spy tool (TrendTrack déjà envisagé, Winning Hunter en alternative) et, si possible, le connecter à Claude pour pré-trier les produits.
- Dans chaque prompt de recherche : **date (oct.-nov. 2026), saison (Black Friday/Noël), marché France** et niches.
- Critère « déjà vendu et rentable ailleurs » = cohérent avec notre méthode US → France : vérifier nombre d'annonces actives, ancienneté, courbe de trafic du concurrent US.
- Avatar : faire le travail d'avatar **en français** (avis clients FR, Amazon.fr, forums) pour trouver les mots du public francophone.
- Pages : partir d'une référence de page qui convertit, garder sobre, vérifier mobile ; tester un audit type Photoroom.
- Créas : la méthode « 10-30 images de référence → Seedance » est directement applicable avec Higgsfield/Nano Banana/Seedance ; démarrer avec 3-5 vidéos. Pour la France : voix-off **en français** (vérifier la qualité de la voix générée).
- Installer dès le départ les flux panier abandonné / bienvenue / post-achat.

## Points de vigilance
- Vidéo très promotionnelle : quasi chaque outil est un lien affilié ; les chiffres de CA (1 700-2 000 $/jour, « premier 50 000 $ ridiculement simple ») ne sont pas vérifiables.
- Les « skills » et prompts promis sont conditionnés à 500 likes : on ne les a pas.
- **USA Drop = expédition depuis la Chine** : incompatible avec notre contrainte stock UE ≤ 3-9 jours ; chercher l'équivalent avec entrepôt UE.
- Cloner la page d'un concurrent « 1 pour 1 » : risque de contrefaçon (textes, photos, marque). Recréer, ne pas copier ; ne pas reprendre logo/nom de marque.
- Pubs UGC IA présentées comme de vrais témoignages : en France, risque de **pratique commerciale trompeuse** (Code de la consommation) et règles Meta sur le contenu généré par IA ; à vérifier (source : economie.gouv.fr / DGCCRF, politique Meta sur l'IA).
- Email/SMS marketing en France : consentement préalable (RGPD, CNIL) — à vérifier sur cnil.fr.
- Les noms de modèles IA évoluent vite ; tester ce qui est disponible au moment du lancement.
