## EX 1

FONCTION CmpterJusqua(n)
  nombre n
POUR i de 1 à n FAIRE
     AFFICHER i
  FIN POUR
FIN FONCTION  

## EXO 2
POUR i de 1 à n FAIRE
 SI i === n ALORS 
   AFFICHE i
    FIN SI
FIN POUR

## Exo 3
VARIABLE
n:ENTIER
i:ENTIER
DEBUT
POUR i de 1 à n
 AFFICHER i 
 SI i %2 == ALORS
   AFFICHER i
   FIN SI
   FIN POUR
FIN FOCTION


## EXO 4
FONCTION produit(n)
    total ← 1
    POUR i DE 1 À n AFFICHER
        total ← total * i
    FIN POUR
    RETOURNER total
FIN FONCTION

     
 ## EXO 5
  FONCTION compterPairs(n)
    INITIALISER compteur à 0
    POUR i de 1 à n FAIRE
        SI i est pair ALORS
            AJOUTER 1 à compteur
        FIN SI
    FIN POUR
    RETOURNER compteur
FIN FONCTION


# EXO 6
FONCTION table(n)
    POUR i de 1 à n FAIRE
        AJOUTER n × i à resultat
    FIN POUR
    RETOURNER resultat
FIN FONCTION


# EXO 7
FONCTION multiplesJusqua(n, limite)
    TANT QUE multiple est inférieur ou égal à limite FAIRE
        AJOUTER multiple à resultat
        AJOUTER n à multiple
    FIN TANT QUE
    RETOURNER resultat
FIN FONCTION


