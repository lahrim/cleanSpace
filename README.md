# cleanSpace - module pour Node.js
cleanSpace, permet de retirer les espaces avant ou après un mot ou une phrase


## installation
Placer le fichier cleanSpace.js dans le dossier modules


## utilisation
Dans le fichier, ajouter sur la première ligne
```
const { cleanSpace } = require('./cleanSpace')
```

Exemple d'utilisation
```
// retirer les espaces avant ou après le pseudo
cleanSpace(req.body.pseudo)
```
