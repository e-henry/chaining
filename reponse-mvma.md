# Reponse [mvma]

## Commande passée

    $ grep -i "star wars" sets.csv | sed -e 's/"\(.*\),\(.*\),\(.*\),\(.*\)"/\1\2\3\4/' -e 's/"\(.*\),\(.*\),\(.*\)"/\1\2\3/' -e 's/"\(.*\),\(.*\)"/\1\2/'|cut -d ',' -f 2,3 | sed -e 's/\(.*\),\(.*\)/| \2 |  | \1 |/'|sort |uniq >> reponse-mvma.md


## Résultat

|Année|Nom de la boite|
