# Vidéo 39 — Claude + Higgsfield pour une marque de vêtements : étude de marché, textes et visuels publicitaires 100 % IA

- **Auteur / intervenant** : **Malik**, 21 ans, propriétaire d'une marque de streetwear (« sept chiffres », 35 000 commandes, entrepôt propre) ; mentorat individuel et agence de pub.
- **Langue** : anglais. **Longueur** : ~15 600 caractères.
- **Thème principal** : utiliser **Claude** (étude de marché, textes, calculs) et **Higgsfield** (visuels pub via MCP) pour une marque de vêtements en direct au consommateur.

## En bref
La vidéo vise une **marque de vêtements** (hors de notre modèle produit), mais le **processus est transposable** :
- étude de marché dans Claude à partir d'un **profil de marque** sauvegardé (5 concurrents : prix, livraison offerte, offres) ;
- inscription chez les concurrents pour **recevoir leurs e-mails et SMS** ;
- Claude comme rédacteur (e-mails, textes de pub, fiches) et comme « comptable » (marge, ROAS d'équilibre) ;
- surtout, **Higgsfield connecté à Claude en MCP** pour générer des visuels pub réalistes en **formats feed et story simultanés**.

Trois règles d'image : bonne image de référence, prompt détaillé, bon modèle (**Nano Banana Pro** pour la scène et le produit, **GPT Image 2** pour les textes nets et l'insertion du produit dans une image existante). Astuce : une **bibliothèque d'« éléments »** (photos produit renommées par produit et par angle) que Claude propose à chaque génération.

## Points clés (affirmations de l'auteur)
1. **Ne jamais deviner** : quelqu'un a déjà fait ce que tu essaies de faire ; l'étude de marché sert à voir les prix, les produits qui se vendent et les stratégies marketing des concurrents.
2. **Prompts riches** : « trash prompt = trash response ». Créer d'abord un **profil de marque** (fondamentaux, audience, contexte concurrentiel) et le stocker dans les fichiers du projet Claude.
   - Prompt : « En te basant sur le profil de ma marque, trouve mes 5 principaux concurrents avec des prix et des angles similaires, adaptés à mon client idéal. Tu es un analyste expert en étude de marché pour marques DTC… »
   - Résultat en ~1 min : fiche par concurrent (prix, livraison offerte, lien) + synthèse.
3. **Espionner les concurrents** : s'inscrire à leur pop-up (e-mail + téléphone) pour recevoir leurs e-mails et SMS ; noter l'offre (ex. −10 %), la structure de la page produit, l'absence ou la présence d'un BOGO.
4. **Claude rédacteur** : 5 e-mails avec 5 angles différents en 30 s (objet, texte d'aperçu, corps). Exemple d'angle « calcul du bundle » : « 1 casquette 60 $, 2 casquettes 90 $ — tu n'allais pas t'arrêter à une ».
   - Aussi : fiches produit, textes de pub, légendes Instagram ; **suivi des dépenses, coût des marchandises, marge, ROAS d'équilibre**.
5. **Visuels pub IA** : remplacent les séances studio, les mannequins et les créateurs UGC, ce qui **divise le budget contenu par deux** (selon lui). On teste beaucoup d'angles et on scale les gagnants. Claude génère simultanément les **formats feed (4:5 ou 1:1) et story (9:16)** ; les visuels sont téléversés dans Meta Ads. Les visuels sans texte servent de pubs de découverte.
6. **Coûts Higgsfield** : forfait d'entrée « ~50 $/mois » ; lui paie **~2 000 $/an pour ~6 500 crédits/mois** (rarement tous consommés).
7. **3 règles d'image** :
   - **image de référence** de qualité ;
   - **prompt détaillé** (écrit par Claude) ;
   - **bon modèle** : Nano Banana Pro (produit, décor, scène réaliste) vs **GPT Image 2** (textes sans faute, insertion du produit dans une image existante).
8. **Connexion MCP** : dans Higgsfield → « MCP & CLI » → copier le lien ; dans Claude → Personnaliser → Connecteurs → Ajouter un connecteur personnalisé → coller l'URL du MCP distant.
   - Démo : une image de référence (jean sur la banquette arrière d'une voiture, ambiance sombre) → Claude écrit le prompt → 2 images en ~40 s (Nano Banana Pro, texture réaliste).
9. **Astuce « éléments »** : renommer toutes les photos produit en « nom_produit + angle » (face, profil, dessous), les charger comme **éléments de référence** dans Higgsfield, puis demander à Claude de **proposer à chaque génération la liste des éléments** à choisir (il recommande le plus adapté).

## Outils et apps cités
| Outil | Usage | Prix cité |
|---|---|---|
| **Claude** (projets/fichiers, connecteurs) | étude de marché, rédaction, calculs, prompts d'images | — |
| **Higgsfield** (MCP) | génération d'images ; hub de modèles | ~50 $/mois en entrée ; ~2 000 $/an pour ~6 500 crédits/mois |
| **Nano Banana Pro** | photos produit, scènes réalistes | via crédits Higgsfield |
| **GPT Image 2** | images avec textes nets, insertion du produit | via Higgsfield |
| Meta Ads | diffusion des visuels feed et story | — |

## Exemples de produits / boutiques cités
- Sa marque de streetwear (casquettes, jeans, modèle « City of Angels ») ; concurrents streetwear non nommés.

## Ce qu'on retient pour notre projet
- **Hors sujet par la niche (vêtements), très pertinent par l'outillage** : c'est notre stack (Claude + Higgsfield / Nano Banana) avec une procédure précise.
- **À mettre en place** :
  1. un **projet Claude** par produit avec le profil marque/produit/avatar en fichiers (rejoint les documents de base de la vidéo 36) ;
  2. le **connecteur MCP Higgsfield** dans Claude ;
  3. la **bibliothèque d'éléments** de photos produit renommées (photos réelles de l'échantillon) ;
  4. la génération **feed + story** en un seul lot ;
  5. le choix du modèle : **Nano Banana Pro** pour la scène, **GPT Image 2** pour les visuels avec texte en français (accents, orthographe).
- **Budget** : forfait Higgsfield d'entrée (~50 $/mois cité) pendant octobre-décembre ; à inscrire dans `docs/budget.md` (prix à vérifier sur le site).
- **Espionnage des concurrents français** : s'inscrire aux newsletters des boutiques FR du même produit pour récupérer leurs offres BF/Noël et leurs séquences d'e-mails.
- **Angle e-mail « calcul du bundle »** (« 1 = 60 €, 2 = 90 € ») : directement réutilisable pour nos offres de packs du Q4 (cf. vidéo 31).
- Faire calculer par Claude la **marge et le ROAS d'équilibre** de chaque produit (cohérent avec les vidéos 26 et 31).

## Points de vigilance
- **Chiffres et statut** (sept chiffres, 35 000 commandes) invérifiables ; vidéo d'appel vers un mentorat et une agence.
- **Marque de vêtements avec stock propre** : modèle différent du nôtre (tailles, retours, stock).
- **Visuels 100 % IA présentés comme de vraies photos** : pour des produits physiques, l'image doit **refléter fidèlement le produit** (sinon retours, litiges, pratique trompeuse) ; partir de photos réelles du produit reçu.
- **Signalement IA** : Meta peut exiger ou ajouter une mention pour certains contenus IA ; transparence AI Act — à suivre.
- **Collecte de SMS et d'e-mails** pour nos propres clients : consentement obligatoire (RGPD, CNIL) — à vérifier sur cnil.fr.
