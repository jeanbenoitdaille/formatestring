# formatestring
Formater une chaine de caractères 
Il est possible de réussir cet exercice sans utiliser la fonction format, en concaténant des chaînes de caractère avec le symbole +.

Cependant, vous remarquerez que la méthode format est souvent plus facile à utiliser et procure un résultat plus facile à décoder.

La méthode format s'applique directement sur une chaîne de caractère et fonctionne avec les accolades. On peut indiquer des indices à l'intérieur des accolades :

    "Bonjour je m'appelle {0} {1}".format(prenom, nom)

Mais aussi utiliser directement, comme dans le cas de cet exercice, des 'tags' qui vont nous permettre de remplir les espaces occupés par les accolades avec des variables :

    "Bonjour je m'appelle {prenom} {nom}".format(prenom="Pierre", nom="Dupont")
