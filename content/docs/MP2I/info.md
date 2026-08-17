---
title: "Info"
weight: 5
# bookFlatSection: false
# bookToc: true
# bookHidden: false
# bookCollapseSection: false
# bookComments: false
# bookSearchExclude: false
# bookHref: ''
# bookIcon: ''
---
# **Informatique**
Site de M. Karpman : [site](https://membres-ljk.imag.fr/Pierre.Karpman/CPGE/2025/)

## **Setup pour l'informatique**
Il est **vivement recommendé** d'avoir une machine avec **Linux**, MacOS est aussi acceptable et Windows avec WSL est... utilisable.

Pour le C, il vous faudra un compilateur, vous avez le choix entre [clang](https://clang.llvm.org/) et [gcc](https://gcc.gnu.org/).

Pour Ocaml, l'installation d'[opam](https://opam.ocaml.org/) est vivement recommendée, `opam` vous permettra de gérer les packages et versions ocaml.

Il est conseillé d'installer `utop` via `opam` :
```sh
$ opam install utop
```

## **Fonctionnement**
Le rythme est assez soutenu, on fait un poly par semaine et selons les chapitres on passe jusqu'à 3 semaines sur un chapitre.

Au niveau du travail en classe :
  - un TP de deux heures par semaine sur le chapitre en cours
  - un TD une semaine sur deux au S1 et toutes les semaines au S2
  - un DS environ toutes les 6 semaines

Il est conseillé de finir les TP à la maison, même si cela ne doit pas empiéter sur le reste, faites le si vous avez du temps et si ça vous donne envie.

Les DS mixent questions de programmation et théorie, les premiers DS sont assez introductifs.

## **Tips**
### **Pour le C**
Si vous chercher de la docu, le site [geekforgeeks](https://www.geeksforgeeks.org/) propose des articles sympa, vous avez aussi le [poly](https://membres-ljk.imag.fr/Pierre.Karpman/CPGE/2025/introc.pdf) rédigé par M. Karpman qui est très bien.

Quelques recommendations de flags de compilation :
  - `-Wall` et `-Wextra`, un must, active tous les warnings du compilateur pour vous prévenir des potentiels problèmes avec votre code
  - `-fsanitize=undefined`, un must aussi, permet d'afficher à l'éxécution les `undefined behavior` (choses qu'il est souvent préférable d'éviter)
  - `-fsanitize=address`, utile quand vous manipulez la heap, permet de prévenir à l'éxécution d'éventuels problèmes liés à la gestion mémoire

### **Pour Ocaml**
La [docu officielle](https://ocaml.org/manual/) est suffisante pour rechercher des méthodes.

