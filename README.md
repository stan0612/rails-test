# RAILS Test Hoggo

## Énoncé

Vous devez développer une application avec un formulaire qui permet de gérer des **assurances Multirisque** (c'est-à-dire des assurances permettant de protéger des locaux professionnels.). C'est un produit d'assurance classique. Néanmoins, la particularité de ce produit est que bien que ce soit un  produit commun à tous les types de société, les informations demandées  aux entreprises varient énormément en fonction du type d'entreprise. Pour ce même produit d'assurance, on ne va poser exactement les mêmes  questions à un agriculteur, qu'à un agent immobilier ou à un restaurant (en effet, les risques ne sont pas les mêmes.).

L'Exercice est simple. Comment faire en sorte de gérer ces **demandes de devis** (formulaire de demande) qui comprennent **beaucoup de champs en commu**n (comme l'email du demandeur, la raison sociale de l'entreprise, son siret,  siren, code naf, le prix max, le revenu annuel, le téléphone, la  description, le status de traitement etc.) et les **éléments propres à chaque métier**. Pour l'exercice, on va prendre **3 types d'assurances Multirisques** :

- **Assurance Immobilier**, les champs spécifiques à ce type d'assurance sont :
  - hauteur_du_bâtiment => Integer
  - Nombre_d'étages => Integer
- **Assurance Agricole**, les champs spécifiques à ce type d'assurance sont :
  - type_de_culture => Enum
  - zone_de_sècheresse => Bool
- **Assurance automobile**, les champs spécifiques à ce type d'assurance sont :
  - nombre_de_points_sur_le_permis => Integer
  - modèle_de_voiture => String
  - numéro_d'immatriculation => String