# normoulinette
(Encore) une moulinette de norme Epitech, mais codée en Python et dégoulinante de swag

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
* Fichiers comportant plus de 5 fonctions
* Doubles sauts de ligne
* Macros non composées de A-Z 0-9
* Utilisations de define dans un .c
* Fonctions de la lib C standard
* Mots-clefs interdits
* Absences d'espace après les mots-clefs
* Absences de parenthèses après un return non-void
* Ordre des includes
* Présence du header Epitech
* Absences d'espace après une virgule
* Lignes comportant plusieurs instructions
* ifndef de protection invalides ou manquants

Pas (encore) géré :
* Déclarations/Affectations sur la même ligne
* Saut de ligne entre déclarations et reste du code
* typedefs de s_struct en t_struct obligatoirement
* Détection de l'indentation
* Saut de ligne après une structure de contrôle
* Symbole du pointeur (*) jamais sur le nom de type
* Gestion des paramètres de fonctions sur plusieurs lignes
* Norme des Makefiles
* Validité des Makefiles