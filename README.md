# beehives-notes

> A Vue.js project

## Build Setup

``` bash
# install dependencies
npm install

# serve with hot reload at localhost:8080
npm run dev

# build for production with minification
npm run build
```

For detailed explanation on how things work, consult the [docs for vue-loader](http://vuejs.github.io/vue-loader).

## Présentation du projet
### Composants

  * Rucher (ensemble de ruches)
  * Ruche (une colonie d'abeilles associée à un rucher)
  * Note (note dans une NoteList)
  * NoteList (associée soit à une ruche soit à un rucher)

### Etapes

  1. Liste de base de ruchers et de ruches avec les notes associées
    * Création des composants de base
    * Ajout de la base de données

  2. Connection avec personnalisation
    * login via CouchDB
    * droits associés aux données
    * partage de vue et d'édition
