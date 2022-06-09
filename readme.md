# Geek Fighter Academy - Initiation Fox3 - Sierra Hotel
Classement des pilotes de la Geek Fighter Academy sur initiation au combat Fox3.

## Etablissement du classement
Classement établi sur une base de calcul ELO, proposée par CoubyStark.

Principe du classement ELO : [Wikipédia - Classement ELO](https://fr.wikipedia.org/wiki/Classement_Elo)

Eléments de calcul retenus :
- K = 60 jusqu’au 10ème match du joueur,
- K = 20 pour un classement Elo en dessous de 2 400 Elo,
- K = 10 pour un classement Elo au-dessus de 2 400
- Bonus 1/6ème de K si victoire de match sans mort (2 - 0)
- En cas de défaite pour tout ELO inférieur à 1100, pas de pénalisation, ELO incrémenté de 1 par match

## Données brutes
Elles se trouvent dans le fichier **data\gfa_1v1_raw_data.csv**.

En cas d'erreur, ne pas hésiter à ouvrir un ticket.
