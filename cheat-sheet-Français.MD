Assembleur base :

    - mov = copie d'un contenu
    ex : mov AX, 5 
    AX va prendre la valeur de 5

    - cmp = comparer 
    cmp AH, BH
    AH et BH seront comparé

    - call = appel de procédure (fonction)
    call sub_132
    appel de la fonction sub_132

    - jmp = saut d'une instruction vers une autre (sans conditions)
    jmp loc_123
    saute vers loc_123

    - je = jump if equal, saute vers une instruction si la comparaison est égal
    - jne = jump if not equal, saute vers une instruction si la comparaison est pas égal

    - add = ajout d'une valeur
    add AX, 5 (5 et ajouté à AX)

    - sub = soustraction d'une valeur
    sub AX, 5 (5 va être soustrait a AX)

    - inc = ajoute 1 au registre
    - dec = retire 1 au registre

    - ret = appel la dernière instruction d'une procédure

    - nop = ne fait rien, utile pour remplacer certaine conditions qui nous dérangent

    - retn = return (fin de fonction)
    - Sleep = pause du programme
    - SUB_ = Sous programme

    - Empiler un regsitre au sommet (variable) : push
    - Retirer un registre du sommet (variable) : pop

    - thread = 2ème processus executé en parrallèle

Tips pour du reverse engineering:
- Ne pas tout comprendre mais regarder les fonctions appellé avec call.
- Regarder le nom des fonctions + recherche sur internet
- En assembleur, "21h" => 21 en hexa (ne pas prendre le h lors de la conversion)

Important : 
- Avant d'executer une fonction, tout les paramètres de la fonction son stocké dans la pile d'execution.