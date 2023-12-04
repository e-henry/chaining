# Reponse [mvma]

## Commande passée

    $ grep -i "star wars" sets.csv | sed -e 's/"\(.*\),\(.*\),\(.*\),\(.*\)"/\1\2\3\4/' -e 's/"\(.*\),\(.*\),\(.*\)"/\1\2\3/' -e 's/"\(.*\),\(.*\)"/\1\2/'|cut -d ',' -f 2,3 | sed -e 's/\(.*\),\(.*\)/| \2 |  | \1 |/'|sort |uniq >> reponse-mvma.md


## Résultat

| Année | Nom de la boite |
| 2000 |  | Star Wars #1 - Sith Minifig Pack |
| 2000 |  | Star Wars #2 - Luke/Han/Boba Minifig Pack |
| 2000 |  | Star Wars #3 - Troopers/Chewie Minifig Pack |


