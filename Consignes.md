# Consignes exercice

## exo 1

- Creez un fichier Product.php dans le dossier exo

- Créer une classe product avec comme propriété : title(string), price(float) , quantity(int), total(float)

- créer une méthode _(c’est le nom des fonctions à l'intérieur des classes)_ qui va calculer le total du produit en multipliant le prix du produit par la quantité.

- Instancier deux fois la classe dans deux variables différentes,

`par exemple $commode et $chaise,
attribuez lui des valeurs.`

- Puis afficher dans un écho les propriétés de l’objet ainsi que le total.

## exo 2

- Creer un fichier Product1.php

- Créer la classe Product1 avec les mêmes propriétés que product sauf total.

- Modifier la visibilité des propriétés et faites une encapsulation grâce à des getter et setter.

- Finissez par instancier deux fois la classe et utilisez les méthodes précédemment créées pour modifier les valeurs de l’objet.

## exo 3

- Creer un fichier Product2.php

- Créer la classe Product2 avec le même code que product1.

- Puis modifier votre classe Product2 en incluant une methode statique qui verifie que ni la quantité ni le prix est nulle avant de retourner le total.

- Rajouter egalement une constante € pour l’utiliser dans la méthode calculeTotal.

## exo 4

- Créez un Product3.php et sa classe (vous pouvez reprendre comme base le Product2)

- ajouter un \_\_construct pour définir des le depart les valeurs des propriétés

## exo 5

- Créez une classe Employe avec les propriétés suivantes : $nom, $poste, $salaire.

- Ajoutez un constructeur pour initialiser ces propriétés lors de la création d'un objet.

- Implémentez la méthode magique \_\_toString dans la classe Employe pour retourner une chaîne de caractères représentant les détails de l'employé.

- Typez toutes vos méthodes.

- Ajoutez la méthode magique \_\_clone à la classe Employe.

- Modifiez la méthode \_\_clone pour incrémenter le salaire de l'employé cloné de 10%.

**Instanciation:**

- Créez un objet $employe1 avec un nom, un poste et un salaire spécifiques.

- Clonez l'objet $employe1 pour créer un nouvel objet $employe2.

- Affichez les détails de $employe1 et $employe2 en utilisant la méthode dans un echo;

## exo 6

- Creer une classe abstract product4 qui reprends le contenue de de Product3 avec setter et getter et le construct

- Puis creer une classe Meuble qui prends une propriete et une methode supplementaire pour ajouter une couleur

- et creer une classe Vetement qui prends une propriete et une methode supplementaire pour ajouter une Taille

- Instanciez les deux derniere classe puis affichez les valeurs contenue dans l’objet.
