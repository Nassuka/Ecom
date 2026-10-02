# Vidéo 17 — Recréer les pubs IA d'une boutique à « 1 M$/mois » (vidéo cartoon, réaliste, UGC + images) avec Claude Cowork, Zeely AI et Seedance 2.5

- **Auteur / intervenant** : même youtubeur anglophone que la vidéo 16 (mêmes partenaires : Winning Hunter, USA Drop ; « 500 likes pour le tableau Miro »). Non nommé.
- **Langue** : anglais
- **Longueur approximative** : ~27 600 caractères
- **Thème principal** : production de créas publicitaires 100 % IA en « ré-ingénierie » des pubs gagnantes d'un concurrent.

## En bref
Cas d'étude : la marque « One Compress » (genouillère en bambou, produit AliExpress en marque blanche) ferait 2-3 M$ sur 30 jours avec 579 pubs actives, majoritairement générées par IA (vidéos cartoon, vidéos « TV », UGC IA, images statiques). L'auteur montre comment : télécharger les meilleures pubs du concurrent + transcript, les faire analyser par Claude Cowork qui produit des prompts d'images (storyboard) et un prompt Seedance 2.5, générer images puis vidéo dans Zeely AI, et produire des pubs image à partir de templates.

## Points clés (affirmations de l'auteur, non vérifiées)
**Preuve / cas concurrent**
- One Compress : boutique lancée en décembre 2025, 5-9 M$ affichés par l'outil sur 30 jours (« plus réalistement 2-3 M$ »), 579 pubs actives, meilleures pubs = vidéos et images IA.
- Leçon : les **pubs image statiques** comptent aussi parmi les meilleures pubs ; « pour scaler, il faut des images ET des vidéos ».

**Trouver les concepts à recréer**
- Outil spy (Winning Hunter) : filtrer par « highest reach and spend », média vidéo ou image. Alternative gratuite : Meta Ad Library (mais « on devine ce qui marche ») + extension Chrome de téléchargement vidéo + outil de transcription gratuit.
- On peut recopier le concept d'un concurrent direct « avec un twist », ou prendre **n'importe quel concept gagnant d'une autre niche** et l'adapter à son produit.

**Méthode vidéo (3 formats démontrés)**
1. Ajouter le produit en « asset » dans Zeely (via l'URL de la page produit).
2. Donner à Claude Cowork la/les vidéos de référence + transcript + skill + prompt → il rend une « prompt sheet » : prompts d'images (personnages, scène, packshot produit) + prompt Seedance 2.5.
3. Générer les images (storyboard), puis les charger dans Seedance 2.5 **dans le bon ordre** (image 1 = frame de départ…) car le prompt les référence par numéro ; une erreur d'ordre ruine la vidéo.
4. Réglages Seedance utilisés : 9:16, 720p, 30 s, audio activé ; génération 5-10 min ; vérifier avant de lancer pour ne pas gaspiller de crédits.
5. Post-production : accélérer les passages lents (3 premières secondes, gestes), couper ce qui « fait faux » ; possibilité d'enchaîner deux clips de 30 s.
- **Cartoon ad** : le produit « parle » (« je suis ta genouillère, je reste sur ton genou toute la nuit »).
- **Pub réaliste type TV** : dame âgée dans l'escalier + fille ; dialogue sur l'ancienne attelle « trop chaude ».
- **UGC IA** : femme en voiture avec un café (« j'ai annulé mon opération du genou » chez le concurrent ; sa version : « j'ai failli arrêter mes marches », « 40 % de réduction »).

**Méthode image**
- Télécharger les meilleures pubs image du concurrent ; demander à Claude Cowork « 12 concepts » d'images virales + prompts (en lui donnant le lien de son site) ; générer en GPT Image 2, 9:16, 2K, image produit en référence ; lancer toutes les générations en file.
- Galerie de templates d'images de Zeely filtrable par secteur (santé, beauté, vêtements) → « recreate » avec son produit ; textes éditables directement.

**Fournisseur** : USA Drop (11 ans d'existence, livraison 5-15 jours, échantillons, agent privé dès 5 commandes/jour, connexion Shopify et TikTok Shop).

## Outils et apps cités
| Outil | Usage | Prix |
|---|---|---|
| Zeely AI | génération images/vidéos, templates de pubs, assets produit | non donné (affilié) |
| Claude Cowork + skill de l'auteur | rédaction des prompts storyboard/vidéo/image | non donné |
| Seedance 2.5 (dans Zeely) | vidéo 30 s, jusqu'à 50 images de référence | crédits |
| GPT Image 2 (dans Zeely) | images 9:16 2K | crédits |
| Winning Hunter | pubs triées par portée/dépense, transcripts, téléchargement | non donné |
| Meta Ad Library + extension « video downloader » + outil de transcription | alternative gratuite | gratuit |
| USA Drop | fournisseur (Chine), 5-15 jours | inscription gratuite |
| AliExpress | vérifier qu'un produit de marque est un produit dropshipping | — |

## Exemples de produits / boutiques cités
- **One Compress** — genouillère / manchon de compression en bambou (arthrose du genou, récupération, port la nuit).
- Divers exemples génériques : tondeuse (« clipper »), masque visage, clavier.

## Ce qu'on retient pour notre projet
- **Pipeline créa directement transposable à notre stack** (Claude + Higgsfield/Seedance/Nano Banana) : pub concurrente → analyse → storyboard d'images de référence → vidéo 30 s → montage léger. Prévoir 3 formats à tester : cartoon/objet qui parle, mini-scène réaliste, UGC.
- Ne pas négliger les **pubs image** : moins chères à produire, rapides à décliner (10-12 concepts par produit) — idéal avec 1 000 € de budget.
- S'inspirer de concepts gagnants d'autres niches quand le produit n'a pas de concurrent FR.
- Ad Library gratuite + transcription suffisent pour démarrer si on ne paie pas encore de spy tool.
- Pour le Q4 : décliner les concepts en version « cadeau de Noël » / « offre Black Friday ».
- Tout réécrire et doubler **en français** (voix, textes incrustés).

## Points de vigilance
- Promotion affiliée (Zeely, USA Drop, Winning Hunter) ; chiffres du concurrent issus d'un estimateur (l'auteur lui-même divise par ~3).
- **Allégations santé** : les pubs montrées parlent d'arthrose, d'« opération annulée », de circulation — en France/UE, allégations de santé non prouvées et faux témoignages = pratiques commerciales trompeuses ; un produit présenté comme ayant un effet médical peut relever des **dispositifs médicaux** (marquage CE). À éviter / à vérifier (DGCCRF, ANSM).
- Faux témoignages UGC générés par IA (« j'ai annulé mon opération ») : risque juridique et de rejet Meta ; préférer des formats démonstratifs honnêtes.
- Copier les pubs d'un concurrent à l'identique : risque de droit d'auteur ; recréer le concept, pas la créa.
- USA Drop : délais 5-15 jours depuis la Chine, hors de notre contrainte stock UE.
- Les visuels IA générés « paraissent faux » par endroits de l'aveu même de l'auteur : prévoir un tri sévère.
