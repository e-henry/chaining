# Reponse [mfa]

## Commande passée

    $ echo "" >> reponse-mfa.md && grep -i "star wars" sets.csv | sed -e 's/"\(.*\),\(.*\),\(.*\),\(.*\)"/\1\2\3\4/' -e 's/"\(.*\),\(.*\),\(.*\)"/\1\2\3/' -e 's/"\(.*\),\(.*\)"/\1\2/' | awk -F ',' '{print "| "$3" | ", $2" |";}' |  sort -k3  >> reponse-mfa.md

## Résultat

| Année | Nom de la boite |
| ----- | --------------- |