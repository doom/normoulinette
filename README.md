# normoulinette
(Encore) une moulinette de norme Epitech, mais codée en Python et dégoulinante de swag.
Et plutôt rapide aussi (en tout cas, sur des morceaux de codes variés, elle atteint une vitesse de 25000 lignes par seconde)

Géré :
* Lignes de plus de 80 colonnes
* Espaces en fin de ligne
* Commentaires dans le code ou incorrects
* Déclarations de globales sans g_
* Déclarations de structures sans s_
* Déclarations de typedef sans t_
* Déclarations d'énumérations sans e_
* Déclarations d'unions sans u_
* Déclarations d'un prototype dans un .c
* Fonctions à plus de 4 paramètres
* Fonctions de plus de 25 lignes
* Fonctions contenant des fonctions
* Fichiers comportant plus de 5 fonctions
* Doubles sauts de ligne
* Macros non composées de A-Z 0-9
* Macros multilignes
* Utilisations de define dans un .c
* Fonctions de la lib C standard
* Mots-clefs interdits
* Absences d'espace après les mots-clefs
* Absences de parenthèses après un return non-void
* Ordre des includes
* Indentation des includes dans les .h
* Présence du header Epitech
* Absences d'espace après une virgule
* Lignes comportant plusieurs instructions (plusieurs points-virgules)
* ifndef de protection invalides ou manquants
* Présences d'opérateurs binaires (+, -, etc) en fin de ligne
* Déclarations de structures dans des structures
* typedefs de s_type, e_type et u_type en t_type obligatoirement

Pas (encore) géré :
* Absences d'espaces avant et après un opérateur binaire
* Déclarations/Affectations sur la même ligne
* Saut de ligne entre déclarations et reste du code
* Détection de l'indentation
* Saut de ligne après une structure de contrôle
* Symbole du pointeur (*) jamais sur le nom de type
* Gestion des paramètres de fonctions sur plusieurs lignes
* Norme des Makefiles
* Validité des Makefiles