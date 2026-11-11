VARIABLES
n:ENTIER

DEBUT
SI n >= 0 ALORS
AFFICHER 'true'
SINON
AFFICHER 'false'
FIN SI
FIN


## EXO 2
VARIABLES
n:ENTIER

DEBUT
SI n modulo 2 = 0
RETOURNE vrai
SINON 
RETOURNE faux
FIN SI
FIN


## EXO 3
DÉBUT
    LIRE a, b, c

    max ← a

    SI b > max ALORS
        max ← b
    FIN SI

    SI c > max ALORS
        max ← c
    FIN SI

    AFFICHER max
FIN


## exo 4

FONCTION mention(note)
    SI note >= 16 ALORS
        RETOURNER "Très bien"
    SINON SI note >= 14 ALORS
        RETOURNER "Bien"
    SINON SI note >= 12 ALORS
        RETOURNER "Assez bien"
    SINON SI note >= 10 ALORS
        RETOURNER "Passable"
    SINON
        RETOURNER "Insuffisant"
    FIN SI
FIN FONCTION


## EXO 5
FONCTION fizzbuzz(n)
    SI n est divisible par 15 ALORS
        RETOURNER "FizzBuzz"
    SINON SI n est divisible par 3 ALORS
        RETOURNER "Fizz"
    SINON SI n est divisible par 5 ALORS
        RETOURNER "Buzz"
    SINON
        RETOURNER n converti en texte
    FIN SI
FIN FONCTION






