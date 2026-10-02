# Grille de notation des produits

But : comparer les produits **objectivement** et n'en tester que 2 ou 3, car le budget de pub (~650 €) ne permet pas de se tromper souvent.
La grille se remplit dans [`grille-de-notation.csv`](grille-de-notation.csv) (ouvrable dans Excel ou Google Sheets, séparateur `;`).

---

## Étape 1 — Critères éliminatoires (un seul « non » = produit écarté)

| # | Critère | Comment vérifier |
|---|---|---|
| E1 | **Stock UE disponible**, livraison ≤ 9 jours (idéal ≤ 3 jours) | CJ Dropshipping / AutoDS / BigBuy : filtre entrepôt UE |
| E2 | **Petit colis léger** (< 1 kg, non fragile, pas encombrant) | Fiche fournisseur |
| E3 | **Prix de vente ≥ 3 × coût rendu** (produit + livraison) | Calcul de rentabilité ci-dessous |
| E4 | **Pas de marque déposée ni de contrefaçon**, pas de licence (Disney, Pokémon…) | Bon sens + recherche INPI/EUIPO en cas de doute |
| E5 | **Pas dangereux ni lourdement réglementé** (médicament, arme, cosmétique à risque, jouet pour moins de 3 ans, produit alimentaire) | Bon sens |
| E6 | **Conformité UE faisable** : marquage CE si nécessaire, opérateur responsable UE (GPSR) | Demander au fournisseur ; voir `docs/entreprise-juridique.md` |

---

## Étape 2 — Critères notés de 1 à 5 (total sur 100)

| # | Critère | Poids | 1 = faible | 3 = moyen | 5 = excellent | Outil |
|---|---|---|---|---|---|---|
| C1 | **Effet waouh / démontrable en vidéo** | ×4 (20 pts) | Il faut l'expliquer longuement | Intéressant en vidéo | On comprend et on veut en 3 secondes, sans le son | Vidéos TikTok / pubs concurrentes |
| C2 | **Problème résolu** | ×3 (15 pts) | Gadget « sympa » | Petit agacement résolu | Douleur fréquente et frustrante (douleur, temps perdu, sécurité, sommeil, froid…) | Commentaires TikTok, avis Amazon |
| C3 | **Émotion / potentiel cadeau Q4** | ×3 (15 pts) | Aucun lien avec les fêtes | Peut s'offrir | Cadeau évident (« pour papa / maman / mon couple »), personnalisable, émotionnel | Bon sens, recherches « idée cadeau » |
| C4 | **Marge et prix** | ×3 (15 pts) | Prix de vente < 3 × coût | 3-4 × coût, prix de vente 25-35 € | ≥ 4 × coût, prix de vente 35-70 €, lots possibles (×2, ×3) | Calcul ci-dessous |
| C5 | **Preuve que ça marche aux US** | ×3 (15 pts) | Aucune preuve | Quelques boutiques et pubs | Plusieurs boutiques qui montent, pubs actives depuis 2-4 semaines ou plus, volume de recherche en hausse | TrendTrack, SEMrush (US), TikTok Shop, Amazon US |
| C6 | **Écart US / FR (peu saturé en France)** | ×2 (10 pts) | Déjà partout en FR (Amazon.fr, nombreuses pubs FR) | Quelques vendeurs FR | Quasi absent en FR, ou présent avec des pubs faibles | Bibliothèque publicitaire Meta (pays : France), SEMrush (FR), Amazon.fr |
| C7 | **Fiabilité fournisseur et livraison** | ×1 (5 pts) | Délai 7-9 jours, fournisseur inconnu | Délai 4-6 jours | Délai ≤ 3 jours, bon historique, échantillon possible | CJ / AutoDS / BigBuy |
| C8 | **Faible risque SAV et retours** | ×1 (5 pts) | Taille, compatibilité, batterie, fragile | Quelques risques | Taille unique, simple, robuste | Fiche produit, avis clients |

**Score = C1×4 + C2×3 + C3×3 + C4×3 + C5×3 + C6×2 + C7 + C8** (sur 100)

### Décision
- **≥ 75** → produit à tester en priorité
- **60-74** → produit de réserve
- **< 60** → écarté

> Astuce : C1 et C5 pèsent le plus. Un produit sans preuve de traction aux US et sans effet visuel fort ne doit pas passer, même s'il « nous plaît ».

---

## Étape 3 — Calcul de rentabilité (à faire pour chaque produit noté ≥ 60)

| Ligne | Formule | Exemple |
|---|---|---|
| Prix de vente TTC (P) | — | 39,90 € |
| Coût rendu (C) : produit + livraison | fournisseur | 10,00 € |
| Frais de paiement | ≈ 2 % × P + 0,25 € | 1,05 € |
| Cotisations micro + versement libératoire | ≈ 13,3 % × P | 5,31 € |
| **Marge avant pub (M)** | P − C − frais − cotisations | **23,54 €** |
| **CPA maximum** (coût pub max par commande) | = M | 23,54 € |
| **ROAS de rentabilité** | P ÷ M | **1,70** |

- Si la pub coûte plus que le **CPA maximum** par commande, on perd de l'argent.
- Visons un ROAS ≥ 2,5 pour avoir une vraie marge (remboursements et SAV compris).
- Les **lots** (« 2e à −50 % ») et les **upsells** augmentent le panier moyen sans augmenter le coût de pub : à prévoir dès le départ.

---

## Étape 4 — Validation finale (pour les 2-3 produits retenus)
- [ ] Échantillon reçu : la qualité correspond à la promesse de la pub
- [ ] Délai de livraison réel mesuré
- [ ] Au moins 5 idées de créas (angles différents : problème, cadeau, démonstration, avant/après, réaction)
- [ ] Offre de lots / upsell définie
- [ ] Concurrents FR analysés : prix, promesse, points faibles à exploiter
