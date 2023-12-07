# Reponse [bok]

## Commande passée

    $ grep -i "star wars" sets.csv | sed -e 's/"\(.*\),\(.*\),\(.*\),\(.*\)"/\1\2\3\4/' -e 's/"\(.*\),\(.*\),\(.*\)"/\1\2\3/' -e 's/"\(.*\),\(.*\)"/\1\2/' -e 's/"\([0-9]\{4\}\)","\(.*\)"/\1, \2/' | sort -u

## Résultat

| Année | Nom de la boite |
| ----- | --------------- |
