---
title: Fichier 02
sort: 2
---

# Mon titre n'est pas *Fichier 02*, et pourtant ...

> Ce fichier est un exemple

Le présent fichier permet de démontrer le résultat lors de l'utilisation de la directive **title** dans le *YAML front matter*. Ainsi, plutôt que d'obtenir pour titre et en-tête dans la naviguation le **Header1**:

- Mon titre n'est pas *Fichier 02*, et pourtant ...

Nous obtenons pour titre:

- Fichier 02

Afin d'imposer le titre que nous désirons, plutôt que celui du **Header1**, nous pouvons simplement inscrire la directive suivante:

```
# Exemple de YAML Front Matter
---
title: Fichier 02
sort: 2
---

TITRE # --> Sera remplacé par la directive title ci-haut

TEXTE

[...]
```

