# Vidéo 32 — Cloner une boutique US qui « scale » avec Claude + TrendTrack + Higgsfield : produit, branding, page produit, photos et pub UGC IA

- **Auteur / intervenant** : formateur du programme d'accompagnement **« E-com Masters »** (non nommé dans la transcription).
- **Langue** : français. **Longueur** : ~90 000 caractères.
- **Thème principal** : chaîne complète, pilotée par l'IA, pour répliquer en France une boutique qui marche aux US, de la recherche produit à la première pub vidéo.

## En bref
Tutoriel très concret et **directement aligné avec notre stack** :
- **Claude** connecté en MCP à **TrendTrack** (recherche de boutiques US en forte croissance) et à **Higgsfield** (images via Nano Banana, vidéos, audio) ;
- **Shopify** + **AutoDS** pour le sourcing ;
- **ChatGPT Image** pour le logo et quelques visuels.

Exemple suivi de bout en bout : un **legging 3D « anticellulite »** inspiré de la boutique US « Silx » (~3,4 M visites/mois estimées), relancé en France sous la marque « Galbé ». Étapes : branding (nom, logo, kit de marque), page produit codée section par section en HTML/CSS (blocs « Liquid personnalisé » du thème gratuit Horizon), 10 photos produit IA, puis une pub UGC de ~27 s montée à partir de plans IA de 3-5 s, avec voix off refaite en *speech-to-speech*. Fin : appel de vente pour E-com Masters.

## Points clés (affirmations de l'auteur)

### 1. Trouver la boutique à cloner (Claude + MCP TrendTrack)
- Dans Claude : Paramètres → **Connecteurs** → « Ajouter un connecteur personnalisé » : **TrendTrack** (URL `…api…/v1/mcp`) et **Higgsfield** (« Xfield » dans la transcription, `mcp.higgsfield…/mcp`). Mettre les autorisations sur « toujours autoriser ». Compte TrendTrack requis (lien affilié −20 % pendant 3 mois).
- **Prompt 1** (« agent de recherche produit e-commerce expert ») :
  - onglet **Top scaling** de TrendTrack, croissance sur le dernier mois ;
  - **≥ 1 M de visites/mois** (seuil abaissable) ;
  - **catégories resserrées** (ex. mode femme, accessoires de sport), pas de catégories larges ;
  - marché **États-Unis** ; **≥ 5 pubs actives sur les 7 derniers jours** ;
  - profil cible décrit précisément ; livrables (shortlist + top 3).
- Claude écarte les grandes marques (Skims, Alo Yoga, Steve Madden, Spanx) et recommande **Silx** : legging de compression 3D anticellulite, 99 $ (2e à 49 $), ~290 pubs actives, activité réelle depuis ~7-8 mois, site « format dropshipping ».
- Logique : un produit banal (legging) **repositionné sur un problème** (cellulite) cartonne sur un marché US très concurrentiel, donc il y a de la place pour un équivalent en France.

### 2. Sourcing (AutoDS) et fiche Shopify
- Shopify (lien affilié : 3 jours gratuits puis 1 €/mois pendant 3 mois). AutoDS (3 jours d'essai) : marketplace avec fournisseurs Chine/UE/US, import en un clic, commandes automatisées.
- Recherche « legging 3D anticellulite », **expédition depuis la France / livraison en 9 jours**. Import, suppression du titre, de la description et des photos fournisseur ; une seule couleur (noir) ; tailles ; **prix 29,90 €** ; vérifier que les variantes restent liées dans AutoDS.
- AutoDS sert à **démarrer et tester** ; une fois rentable et régulier, passer par un **agent de sourcing privé**.

### 3. Branding (Prompt 2, « directeur de création + stratège de marque »)
- En 3 étapes avec validation entre chaque : noms de marque → concepts de logo (prompts d'image) → **kit de marque** (mission, 3 valeurs, ton, palette, typographies, système de logo, « design guidance » à coller dans Higgsfield pour la cohérence visuelle).
- Logo généré dans **ChatGPT Image** à partir du prompt de Claude, recadré (iloveimg) et détouré (remove.bg, version gratuite).

### 4. Page produit (Prompt 3, « développeur front + expert CRO e-commerce »)
- Trois options :
  - sections natives du thème (lent) ;
  - Claude connecté à Shopify génère tout le thème (bugs, nombreuses retouches) ;
  - **méthode retenue** : Claude dessine la page complète en HTML/CSS (maquette validée), puis livre **le code section par section**, collé dans des blocs/sections **« Liquid personnalisé »** du thème gratuit **Horizon**.
- Bloc produit : garder les éléments natifs (variantes, quantité, ajout au panier ; retirer le paiement accéléré) et ajouter du code au-dessus du titre (accroche), sous le prix (bénéfices) et sous le bouton (livraison, badges de réassurance).
- Sections suivantes : « Pourquoi Galbé », bénéfices + image, **comparatif**, preuve sociale, FAQ, CTA final + réassurance, « Au sport / en ville / à la maison ».
- Mise en forme : couleurs du kit dans la palette du thème ; fond alterné d'une section à l'autre ; **barre d'annonce** (offre ou « livraison offerte dès 40 € ») ; logo centré.
- Images : les téléverser dans Contenu → Fichiers, copier l'URL et la coller dans le `src`, ou donner directement les URL à Claude.
- Astuce : faire une capture d'une section d'une autre marque (ex. un bloc d'avis) et demander à Claude de la recréer aux couleurs de notre marque.
- **Avis clients** : utiliser une app d'avis réels. L'auteur rappelle que **générer de faux avis est illégal** (« tout le monde le fait », mais il le déconseille).

### 5. Photos produit (Prompt 4, via Higgsfield → Nano Banana)
- Claude analyse les visuels concurrents (téléversés dans les médias Higgsfield pour qu'il y ait accès), écrit **10 prompts** (3 lifestyle, 3 gros plans, 2 infographies de bénéfices, 2 « influenceuse casual »), puis lance la génération dans Higgsfield (2 variantes par prompt). Préciser « **textes en français** » (oubli corrigé en relançant 4 infographies).
- Variante avec ChatGPT : partir d'un **visuel publicitaire concurrent** (via TrendTrack, filtre Meta → images) + photo de notre produit → « même composition, autre fond, autre visage, texte en français, format carré, notre logo ».
- Principe : **s'inspirer des concepts** qui marchent, **ne pas copier** les visuels à l'identique (risque juridique).

### 6. Pub vidéo UGC 100 % IA (Prompt 5, en 2 phases)
- Référence : une pub UGC concurrente (téléchargée depuis TrendTrack et **transcription récupérée** dans le détail de la pub), téléversée dans Higgsfield.
- **Phase 1** : Claude analyse la pub (problème, frein émotionnel « sans effort », objection), réécrit le script en français à l'identique, puis 2 à 5 **variantes d'angle**. Paramètres : marque, produit, cible « femmes 30+ », **Meta audience froide**, vertical 9:16, **≤ 27 s**, plans de **3-5 s**, alternance humain / schéma / B-roll / macro produit pour le dynamisme. Relire et corriger les scripts soi-même.
- **Phase 2** :
  - étape 0 : générer une **actrice de référence** (même visage sur tous les plans) ;
  - générer chaque plan séparément, 1-2 variantes par plan (les outils plafonnent à ~15 s ; des plans courts limitent les bugs et le coût, et on ne régénère que le plan raté) ;
  - livraison des plans.
- **Audio en français = point faible** : mots déformés (« sculate », « soir »), voix un peu robotique. Solutions :
  - générer l'audio seul (voix Higgsfield ou ElevenLabs) ;
  - **mieux** : enregistrer sa propre voix en lisant le script, puis la convertir en *speech-to-speech* (outil « Arcade » cité, voix « Manon ») et la caler au montage.
  - En anglais, beaucoup moins de bugs.
- **Montage** dans Premiere Pro ou **CapCut** (gratuit) ; ne pas laisser l'IA monter seule. Optimisation : plans plus courts (1-2 s).
- Script obtenu : « Si tu as de la cellulite et que tu as horreur de la salle de sport, ce truc va te parler » → « Je n'ai rien changé… j'ai juste mis ça » → « les jambes plus légères » → « au bout de quelques semaines, mes cuisses avaient l'air plus lisses » → « satisfait ou remboursé 30 jours ».
- « Certains verront que c'est de l'IA, ce n'est pas grave : c'est le message qui compte. »

## Outils et apps cités
| Outil | Usage | Prix / remarque |
|---|---|---|
| **Claude** (+ connecteurs MCP personnalisés) | agent de recherche, branding, code des sections, prompts, scripts | abonnement Claude (non précisé) |
| **TrendTrack** (MCP) | boutiques « top scaling », pubs, transcriptions, filtres niche | lien −20 % × 3 mois ; prix non donné |
| **Higgsfield** (MCP, « Xfield ») | génération d'images (**Nano Banana**), de plans vidéo, d'audio ; médias de référence | compte requis ; prix non donné |
| ChatGPT Image | logo, visuels inspirés de pubs concurrentes | — |
| Shopify (thème gratuit **Horizon**) | boutique ; sections « Liquid personnalisé » | 3 j gratuits puis 1 €/mois × 3 (lien) |
| AutoDS | sourcing et commandes automatisées | 3 j d'essai |
| iloveimg, remove.bg | recadrage, détourage | gratuit |
| ElevenLabs / voix Higgsfield, « Arcade » (speech-to-speech) | voix off FR | — |
| Premiere Pro / CapCut | montage | CapCut gratuit |
| App d'avis Shopify (non nommée) | vrais avis clients | — |

## Exemples de produits / boutiques cités
- **Silx** (US) : legging de compression 3D anticellulite, 99 $ / 2e à 49 $, ~3,4 M visites/mois estimées, ~290 pubs actives.
- Écartés car trop gros : Skims, Alo Yoga, Boden UK, Steve Madden, Spanx.
- Marque créée pour la démo : **« Galbé »** (legging à 29,90 €, crème/rouge, cible femmes 30+).

## Ce qu'on retient pour notre projet
- **C'est notre méthode « US → France » outillée de bout en bout**, avec les outils prévus (Higgsfield, Nano Banana) et Claude. Si l'on prend **TrendTrack** (« pas encore » dans CLAUDE.md), le **connecteur MCP** dans Claude évite le travail manuel. À évaluer au regard du budget de 1 000 €.
- **Prompt de recherche à adapter au Q4** :
  - « top scaling » US sur **septembre-novembre** ;
  - niches **cadeau / déco / gadgets maison** ;
  - **petit colis**, problème ou effet waouh ;
  - visites ≥ 100 000-300 000 (et non 1 M, pour sortir des grandes marques) ;
  - ≥ 5 pubs actives sur 7 jours ;
  - puis **vérifier l'absence en France** (Ads Library FR + SEMrush).
- **Fournisseur UE** : filtre « Ship from France/EU » dans AutoDS (9 jours = notre maximum ; viser ≤ 3-5 jours avant Noël).
- **Branding + page produit en sections codées par Claude** sur un thème gratuit : économise un thème payant ou un designer ; garder la checklist de sections (accroche, bénéfices, comparatif, preuve sociale réelle, FAQ, réassurance, CTA). Ajouter pour le Q4 : **date limite de commande pour Noël**, « idée cadeau », emballage.
- **Photos produit IA** (Higgsfield / Nano Banana, 10 visuels : lifestyle, gros plans, infographies FR) à partir d'**une photo réelle du produit** (commander un échantillon pour la fidélité du rendu).
- **Pubs vidéo IA** : la recette « actrice de référence → plans de 3-5 s → montage CapCut → voix FR humaine convertie en speech-to-speech » est la plus robuste pour le français. Produire **3-5 scripts / angles** par produit (cohérent avec les vidéos 26, 28 et 31).
- **Prompt de recréation de pub** : partir de la **transcription** d'une pub US gagnante, la faire adapter en français et en variantes d'angle, ne jamais réutiliser les médias d'origine.

## Points de vigilance
- **Contenu commercial** : liens affiliés (TrendTrack, Shopify, AutoDS) et appel de vente pour E-com Masters ; prompts « débloqués à 200 likes ».
- **« Cloner » une boutique** : ne copier ni la marque, ni les textes, ni les photos, ni les vidéos (droit d'auteur, droit des marques, concurrence déloyale) ; il faut une **marque propre** — l'auteur le dit aussi. Vérifier l'**INPI** avant de choisir un nom (ex. « Galbé »).
- **Allégations « anticellulite »** :
  - textile « cosmétotextile » ou promesse d'effet sur la peau = allégation santé/beauté encadrée (DGCCRF) ;
  - « cuisses plus lisses en quelques semaines » prononcé par une **fausse cliente IA** = risque de **pratique commerciale trompeuse** (Code de la consommation) ;
  - risque de refus par Meta (règles sur l'apparence corporelle et les avant/après).
- **Faux avis** : illégaux en France (Code de la consommation, obligations sur les avis en ligne) ; l'auteur le reconnaît. Utiliser uniquement des avis réels. Vérifier sur economie.gouv.fr (DGCCRF).
- **Pub « UGC » entièrement IA** présentée comme un vrai témoignage : zone grise. Meta et le règlement européen sur l'IA (obligations de transparence progressivement applicables) poussent à **signaler les contenus générés par IA** — à vérifier (Meta « AI info », texte AI Act). Prudence sur les avant/après et les promesses de résultat.
- **Coûts IA** non donnés (crédits Higgsfield, abonnement Claude) : à chiffrer dans `docs/budget.md`.
- **Prix de 29,90 €** pour un legging en dropshipping avec 9 jours de livraison : la marge est à calculer (le concurrent US vend 99 $).
- Le code collé dans le thème peut casser lors des mises à jour : garder une copie et tester sur mobile.
