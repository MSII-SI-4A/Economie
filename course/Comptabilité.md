# Comptabilité

## Définitions

Comptabilité : Sert à enregistrer (dans des journaux: vente, achat, banque, caisse...) toutes les opérations (achats, ventes, emprunts, salaires) réalisés par une entreprise sur une année (exercice comptable).

	- Les opérations (mouvements) sont identifiés par des numéros de comptes (issues du plan comptable).
	- La balance est un document synthétique (total) de tous les mouvements de tous les comptes. C'est ce document qui est utilisé pour créer le compte de résultat et le bilan.

## Compte de résultat

Le compte de résultat permet de calculer le résultat H.T. (produits - charges).

````
if resultat > 0
	Bénéfice
else if resultat < 0
	Perte
else
	Résultat null
````

Produits : 
	Chiffre d'affaire
	Subventions
	Revenues de placements
Charges :
	Achats
	Charges d'exploitation
	Salaires
	Interêts d'emprunts

## Le bilan

Le bilan présente une image du patrimoine (l'actif et le passif) de l'entreprise au moment de la cloture.

L'actif : ce qui est possédé (immobilisé + circulant)
	Immobilisé : Enssemble des investissements (durability.years > 1 && value.euros > 500)
		- Incorporel : Softs, licences, brevet, marque...
		- Corporels : Bâtiments, voiture, mobilier, matériel...
		- Financier : Participation dans une autre entreprise (filiale...)
	Circulant : Enssemble des élements mobiles
		- Stocks
		- Créances
		- Trésorerie

Le passif : ce qui est due (capitaux + dettes);
	Capitaux propres : Fonts appartenents à la société
		- Capital social : Apport des associés
		- Résultat : Distribué (dividendes) ou laissé dans l'entreprise (réserves)
		- Réserves
	Dettes
		- Emprunts : Valeurs brute sans interêts
		- Dettes fournisseurs
		- Fiscale et sociale : Salaires, Impots ...

````
if actif == passif
	Good
else
	You made an error !! Try again.
````
