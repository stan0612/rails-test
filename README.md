# RAILS Test Hoggo

## Énoncé

Vous devez développer une application avec des formulaires qui permettent de gérer des **demandes de devis d’assurances multirisques** (c'est-à-dire des assurances permettant de protéger des locaux professionnels). 

La particularité de cet application est que bien que les assurances multirisques soit des produits communs à tous les types de sociétés, les informations demandées aux entreprises dans nos formulaires varient énormément en **fonction du type d'entreprise**. Pour un même produit d'assurance, on ne va pas poser exactement les mêmes questions à un agriculteur, à un agent immobilier ou à un restaurant. Car les risques ne sont pas les mêmes.

L’exercice est le suivant. Comment faire en sorte de gérer ces demandes de devis (sous forme de formulaires) qui comprennent des **champs en commun** (comme l'email du demandeur, la raison sociale de l'entreprise, son siret, siren, code naf, le prix max, le revenu annuel, le téléphone, la description, le status de traitement etc.) et des **informations propres à chaque entreprise**.

Pour l'exercice, on va prendre 3 types d’assurances multirisques :

**Assurance Immobilier**, les champs spécifiques à ce type d'assurance sont :
    - hauteur_du_batiment => Integer
    - nombre_etages => Integer
**Assurance Agricole**, les champs spécifiques à ce type d'assurance sont :
    - type_de_culture => Enum
    - zone_de_secheresse => Boolean (true / false)
**Assurance automobile**, les champs spécifiques à ce type d'assurance sont :
    - nombre_de_points_du_permis => Integer
    - modele_de_voiture => String
    - numero_immatriculation => String
