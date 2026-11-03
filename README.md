# Grasshopper Workshop

Mini-Grasshopper interactif pour apprendre les principes de la programmation visuelle de Rhino/Grasshopper, en 7 leçons.

**Site :** https://olivierpranal.github.io/grasshopper-workshop/

## Utilisation

Tout tient dans `index.html` : aucun serveur, aucune installation. Ouvrez le fichier dans un navigateur, ou utilisez la version en ligne.

## Faire évoluer l'outil

Tout se trouve dans le `<script>` de `index.html` :

- **`DEFS`** : les composants. Chaque entrée décrit un nom, des entrées (`ins`, avec valeur par défaut `def` facultative), des sorties (`outs`) et une fonction de calcul (`fn` pour un résultat par élément, `list` pour produire une liste).
- **`LESSONS`** : les leçons. Chaque leçon a un titre, un texte, des exercices (`tries`) et un graphe d'exemple (`graph` : nœuds et fils).
- **`solve()`** : le moteur. Il évalue le graphe et applique la règle de la liste la plus longue.
- **`drawPreview()`** : la vue de dessus façon Rhino.

## Pistes

- Arbres de données simplifiés (Graft, Flatten)
- Divide Curve, Distance, attracteurs
- Export et import d'un graphe en JSON
- Vue 3D
