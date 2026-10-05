# Recherche TrendTrack du 05/10/2026 (sans Chrome)

> Protocole : `docs/protocole-recherche-produit.md`. Source : connecteur TrendTrack (forfait Professional). Environ 940 crédits utilisés sur 10 000 ; 9 059 restants à la fin.
> **Aucun produit n'est VALIDÉ** : le coût fournisseur (AliExpress, Alibaba), Google Trends, la recherche TikTok organique et la concurrence française complète n'ont pas pu être vérifiés (pas de Chrome dans cette session). Les estimations de ventes et de dépenses de TrendTrack sont des estimations.
> Rappel : pour les pubs ciblant uniquement les États-Unis, TrendTrack n'a pas de données de portée (transparence UE seulement) ; les critères fiables sont la durée de diffusion, le nombre de pubs et le nombre de variantes.

## Méthode qui a marché
- `search_shops` (filtre catégorie, boutiques de 40 produits maximum, au moins 8 pubs actives, marché principal US, ventes estimées ≥ 15 000 $/mois, créées depuis juin 2025), tri par ventes estimées, puis filtre local sur le prix des best-sellers (29 à 85 $) et exclusion des compléments, vêtements, livres numériques.
- `search_ads` avec le domaine de la boutique (tri par durée de diffusion) pour la durée des pubs, les variantes, le texte, les pays ciblés.
- Peu utile : `find_winning_products` (renvoie surtout de grandes marques) et `search_ads` sans catégorie (compléments, beauté).

## Pistes retenues (données vues dans TrendTrack)
| Piste | Boutique | Prix | Pubs (vues) | Ventes estimées | À noter |
|---|---|---|---|---|---|
| Diffuseur de parfum automatique à brume (diffuseur « générique ») | olfiastudio.com | 69,90 $ (cire parfumée 39,90 $) | page 157 pubs ; pubs les plus longues 79 à 82 jours ; 41 à 67 variantes ; portée 30 j : 487 000 ; ciblage dont **FR** | 677 k$/mois (est.), créée 06/2026, trafic +459 % | Produit courant en France ; recharges de parfum = vente additionnelle ; prix en haut de la fourchette |
| Harnais chien sans traction, une boucle | dogshood.com | 39,99 $ | page 819 pubs ; pubs les plus longues 110 à 122 jours ; ciblage US/CA | 2,1 M$/mois (est.), créée 08/2025 | Tailles et retours ; vieux concurrents en France probables ; ne pas reprendre les promesses vétérinaires |
| Appareil de renforcement avant-bras | irond.shop | 34,99 à 44,99 $ | 47 pubs ; **les plus longues : 5 jours** ; ciblage AU/CA/GB/US | 484 k$/mois (est.), créée 04/2026, trafic +34 513 % (anomalie probable) | Aucune pub FR trouvée (recherche « avant-bras musculation grip », FR) ; produit « viral » donc durée de vie incertaine ; textes culpabilisants |
| Pomme de douche haute pression | riviage.com | 69,99 $ | page 49 pubs ; pubs les plus longues 80 jours | 244 k$/mois (est.), créée 07/2026 | Portée faible (46 000 sur 30 j) : estimation de ventes peu crédible |
| Panier-griffoir pour chat (cordage naturel) | stimulicat.com | 79,95 $ (50 % de réduction) ; harnais 37,95 $ | page 462 pubs ; pubs les plus longues 264 à 276 jours ; ciblage dont FR, BE, LU | 2,7 M$/mois (est.) | Preuve très forte (9 mois), mais encombrant et au-dessus de 69 $ ; pub « on ferme à cause des droits de douane » (fausse urgence : à ne pas reproduire) |
| Sacs à pain en cire d'abeille | lorineofficial.com, loafguard.shop, hearthfold.store, doughdissolve.com | 30 à 54 $ | pubs non confirmées par domaine ; aucune pub FR trouvée (« sac à pain cire d'abeille ») | Lorine 1,0 M$/mois (est.), LoafGuard 536 k$ | Plusieurs boutiques : marché validé aux US ; produit simple, léger ; effet waou faible |

## Écartés (raison)
- Compléments, soins, vêtements (tailles), dispositifs santé (anti-étouffement, ronflement, prothèse dentaire), kits de survie, livres numériques.
- Produits encombrants ou fragiles (verres à whisky rotatifs avec fumée, paniers).
- Bouteilles en cuivre et « baguettes » à eau : promesses de santé.
- Grandes marques (Decathlon, Liquid I.V., ESN, etc.).

## Reste à faire pour valider (à lancer dans une session avec Chrome)
1. Coût fournisseur rendu en France sur AliExpress et Alibaba (≤ 15 €, marge ×4) ; stock UE.
2. Google Trends 12 mois et 5 ans (France).
3. Bibliothèque Meta France et TikTok : nombre d'annonceurs sur chaque produit.
4. Recherche TikTok organique (matière créative).
5. Concurrence française réelle via SEMrush et bibliothèque Meta.
