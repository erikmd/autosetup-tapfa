# autosetup-tapfa

## Remarque

Ce script permet de configurer automatiquement les modes Emacs liés à
OCaml/Coq pour l'UE TAPFA.

**Ce script est conçu exclusivement pour être utilisé sur les machines
de TP de l'UPS** sur lesquelles sont déjà installés Emacs 26, OPAM,
Merlin et learn-ocaml-client.

Mais si vous utilisez votre propre ordinateur portable, consulter
https://github.com/erikmd/tapfa-init.el

## Installation

* Ouvrir un terminal et exécuter :

```
curl -OL https://github.com/erikmd/autosetup-tapfa/raw/master/autosetup-tapfa
bash ./autosetup-tapfa
```

Suivre les instructions, en particulier :

* Choisir l'option `Recommandée-UPS`

* Relancer le terminal et ré-exécuter une seconde fois :

```
bash ./autosetup-tapfa
```

* Choisir l'option `Recommandée-UPS`

* Emacs devrait alors se lancer et se configurer automatiquement

* Vous pouvez maintenant créer ou ouvrir un fichier OCaml en tapant
  <kbd>C-x C-f tp1.ml RET</kbd> (c'est-à-dire <kbd>Ctrl+X Ctrl+F</kbd>
  `tp1.ml` <kbd>Entrée</kbd>)

* Si nécessaire, vous pouvez aussi activer le mode
  [learn-ocaml](https://github.com/pfitaxel/learn-ocaml.el#usage)
  en tapant <kbd>M-x learn-ocaml-mode RET</kbd> (c'est-à-dire
  <kbd>Alt+X</kbd> `learn-ocaml-mode` <kbd>Entrée</kbd>)
