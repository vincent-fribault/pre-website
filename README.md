Pre-website
===========

Ce script permet d'installer les dépendances pour gérer un site statique sous
[middleman](https://middlemanapp.com/).

Il est fortement inspirer du script de
[Thoughtbot](https://github.com/thoughtbot/laptop) pour
une machine prêt pour [Ruby On Rails](http://rubyonrails.org/).

Pré-requis
----------

Les "command-line tools" sont nécessaire pour la compilation de ruby et autres
outils via homebrew.
Sous Yosemite and Maverick, il suffit de lancer la commande suivante :

```sh
xcode-select --install
```

Installation
------------

Executez le script suivant :

```sh
curl --remote-name
less mac
sh mac 2>&1 | tee ~/pre-website_debug.log
```
