# Objectif : Creation d'une structure de données à partir d'éléments chainés

## Schéma
![alt text](schema.jpg)

## Output main

    initialisation
    Affichage :
    obj[0]=(NUM)case[0]
    obj[1]=(STR)case[1]
    obj[2]=(PTR)00750D10
    obj[2][0]=(NUM)case[2][0]
    obj[2][1]=(STR)case[2][1]
    obj[2][2]=(PTR)00750D58
    obj[2][2][0]=(NUM)case[2][2][0]
    obj[2][2][1]=(STR)case[2][2][1]
    obj[3]=(STR)case[3]
    ======================================================
    [0] OBJ
     ├→[0] : (NUM) case[0]
     ├→[1] : (STR) case[1]
     ├→[2] : (OBJ) 00750D28
     │  ├→[0] : (NUM) case[2][0]
     │  ├→[1] : (STR) case[2][1]
     │  ├→[2] : (OBJ) 00750D70
     │  │  ├→[0] : (NUM) case[2][2][0]
     │  │  └→[1] : (STR) case[2][2][1]
     │  └→[3] : (STR) case[2][3]
     └→[3] : (STR) case[3]
    ======================================================
    FREE
    [0] : (null)
    [1] : (null)
    [2] : (OBJET)00750D28
    [0] : (null)
    [1] : (null)
    [2] : (OBJET)00750D70
    [0] : (null)
    [1] : (null)
    [3] : (null)
    [3] : (null)

    Donnees inexistantes
