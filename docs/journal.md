# Journal de bord

> Entrées les plus récentes en haut.

---

## 2026-10-02 — Session 2 : résumé des 39 vidéos de formation

**Fait**
- Les transcriptions envoyées en un seul message (~4,6 M caractères) avaient fait planter la session. Je les ai récupérées, découpées vidéo par vidéo et sauvegardées dans `formation/transcriptions/`.
  - 39 vidéos uniques.
  - Écartées : les doublons 22 = 21, 30 = 29 et 34 = 33, et la vidéo 23, qui n'était qu'un lien.
- 39 résumés en français dans `formation/resumes/`, avec un index noté par intérêt dans `formation/README.md`.
- Synthèse et méthode retenue : `formation/synthese.md`.
  - Consensus entre les vidéos, méthode étape par étape et structure Meta pour un petit budget.
  - Pratiques illicites à ne pas reproduire, points fiscaux à vérifier, tableau des désaccords.
- Roadmap et `docs/budget.md` mis à jour avec la méthode retenue.

**Décidé**
- **Calendrier avancé** : 1er test Meta vers le **16-20/10** au lieu du 23/10. Pour tenir cette date :
  - 3 produits choisis au plus tard le **07-08/10** ;
  - page du 1er produit en ligne vers le **14-15/10**.
- **Structure Meta de test** :
  - 1 campagne Ventes, 1 ensemble de pubs par angle à 10-15 €/j, 3 créas par ensemble ;
  - ne rien toucher pendant 48-72 h ;
  - stop-loss d'environ 150-200 € par produit, soit 2 à 3 tests possibles avec le budget.
- **ROAS d'équilibre** = 1 ÷ taux de marge brute, calculé avant chaque lancement.
- Toujours un **angle « cadeau »** pour le Q4. Offre en packs 1/2/3 à tester, sans l'imposer.
- **On s'inspire des concurrents sans jamais copier leurs médias.**
  - Pas de faux avis, pas de faux témoignages IA, pas de prix barrés fictifs.
  - Au Black Friday, le prix de référence est le plus bas des 30 derniers jours (à vérifier).
- Google Ads seulement après validation sur Meta : campagne Shopping en CPC manuel à 20-30 €/j.

**Points à vérifier (fiscal et juridique)**
- Facturation électronique : réception obligatoire depuis le 01/09/2026 ?
- Droit de douane UE de 3 € par article depuis le 01/07/2026 ?

Sources dans `formation/synthese.md` §5.

**Prochaines étapes (urgentes vu le nouveau calendrier)**
- **Porteur de projet** :
  - données SEMrush US/FR, avec le score de niche prix ÷ CPC ;
  - Google Trends sur 5 ans ;
  - bibliothèque publicitaire Meta FR pour les 10 candidats ;
  - délai : **avant le 07/10**.
- **Porteur de projet** : formalités à lancer tout de suite (activité ajoutée à la micro, Meta Business Manager, compte bancaire).
- **Claude** : recherche des fournisseurs à stock UE (prix, délais, conformité) pour les 5 premiers candidats.
- **Claude** : propositions de noms de boutique et de domaines.
- Pour les prochaines vidéos : 5 à 10 par message au maximum.

---

## 2026-10-02 — Session 1 : lancement du projet

**Infos du porteur de projet**
- Budget de départ : **1 000 €**
- Outils : SEMrush (abonné) ; TrendTrack et AutoDS pas encore
- Réside en France, **micro-entreprise existante** (Decoscale, projet mené en parallèle)
- Disponibilité : temps plein possible, partagé avec Decoscale

**Fait**
- Plan global et calendrier jusqu'à Noël (`docs/roadmap.md`)
- Structure du dépôt, qui sert de mémoire entre les sessions
- Grille de notation des produits (`recherche-produit/grille-de-notation.md` + `.csv`)
- Budget détaillé (`docs/budget.md`) et point juridique/fiscal (`docs/entreprise-juridique.md`)
- Recherche des produits gagnants des Q4 précédents et des tendances US 2026 (`recherche-produit/produits-q4-historiques.md`)

**Décidé**
- **Pas de 2e micro-entreprise** (impossible : une seule par personne) → ajouter l'activité « vente à distance » à la micro existante.
- Zone de livraison au lancement : France, Belgique, Luxembourg, Monaco. La Suisse et Andorre (hors UE, douane) viendront plus tard.
- Fournisseurs avec stock UE uniquement.

**Recherche produit (résultat)**
- 65 produits analysés → short-list de 10 dans `recherche-produit/produits-q4-historiques.md`.
- Top pré-notes : masseur yeux chauffant (82), anneau fascia (81), collier LED chien (77), anneau lumineux sapin (76), appareil photo Y2K (75).

**Vidéos de formation**
- Le réseau de l'environnement cloud bloque YouTube : il faut autoriser `youtube.com` dans les réglages réseau de l'environnement (à faire par le porteur), sinon coller les transcriptions.
- 1re vidéo reçue : « La plus grosse formation dropshipping » de Jonathan Ecom (~39 h, partie 1, sans transcription visible). Chapitres utiles repérés : recherche produits, fournisseurs, offre, neuro-marketing, Meta Ads, créatives, SAV, e-mail, IA créatives.

**Prochaines étapes**
- Le porteur vérifie les 10 candidats dans SEMrush (US vs FR) et dans la bibliothèque publicitaire Meta FR (mots-clés fournis)
- Le porteur envoie la liste des vidéos et leurs transcriptions → résumés dans `formation/`
- Ajouter l'activité à la micro-entreprise, créer le Meta Business Manager, ouvrir un compte bancaire dédié
- Passer les candidats au crible : SEMrush (volumes US vs FR), bibliothèque publicitaire Meta FR, CJ Dropshipping (stock UE)
- Décider de prendre TrendTrack (1 mois) pour confirmer la traction US
