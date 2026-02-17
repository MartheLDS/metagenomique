le fichier binaire bacteria_of_interest contient la liste (python) des bactéries susceptibles d'être trouvées dans le milieu urinaire.

La liste peut être importée dans un script python comme suit:

```
import marshal
list = marshal.load(open("/home/marthe/Documents/DS/projet/local/labeled_data/sources/bacteria_of_interest", 'rb'))
```
