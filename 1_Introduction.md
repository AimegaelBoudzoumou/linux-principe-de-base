# Chapitre 1 : Introduction

### Contenu

1. Historique de Unix
2. GNU : FSF, CopyLeft, GPL
3. Linux : caractéristiques, distributions
4. Quelles distributions choisir : grand public, mobiles, professionnelles, spécialisées
5. Exercices

----------------------------------------------------------------------------------------------------------------------

## 1. Historique de Unix

1969 : Ken Thompson, développeur au sein du laboratoire Bell (qui font partie de AT&T) inventa le système Unix.

K. Thompson avait d'abord travaillé sur le système Multics. 

Quand Bell Labs se retira du projet Multics, il se mit à développer son propre système, sur une machine DEP PDP-7.

Si ce système reprenait certaines idées de Multics, K. Thompson y ajouta des nouveauté : Unix était né.

## 2. GNU

1984 : lancement d'un mouvement pour le développement de logiciels libres de droits, par Richard M. Stallman. 

Ceci, pour s'opposer à la commercialisation des logiciels et plus particulièrement à l'indisponibilité du code source. 

### 2.1. FSF

1985 : Richard Stallman a créé la FSF (Free Software Foundation) dans le but de collecter des fonds destinés à financer le logiciel libre.

Il ne s'oppose pas au fait de vendre des logiciels, du moment que le code source reste disponible et que tout programmeur est autorisé à modifier et redistribuer le logiciel.  

### 2.2. CopyLeft et GPL

Pour mener à bien son projet et permettre la diffusion des logiciels libres, Richaard Stallman a mis en place une licence spécifique. celle-ci évite l'appropriation du code source et le dépôt d'un copyright par toute personne s'étant contenté de modifier quelques lignes d'un logiciel libre.
Les fondements de logiciels libres sont regroupés sous quatre libertés:
- La liberté d'éxécuter le programme pour tout usage.
- La liberté d'étuder le fonctionnement du programme.
- La liberté de redistribuer des copies, gratuitement ou non.
- La liberté d'améliorer le programme et de publier vos améliorations, pour en faire profiter toutes la communauté.

A cela, s'ajoute la GPL (General Public License) créée par Richard Stallman ajoute une obligation de rester sous licence libre; cette notion est appelée "copyleft" (gauche d'auteur), par opposition à "copyright" (droit d'auteur), et induit que tout logiciel utilisant une partie de code régi par la GPL est automatiquement placé sous les termes de la GPL.

## 3. Linux
Utilisant le système d'exploitation Minix, développé par Andrew S. Tanenbaum dand le but de montrer à ses étudiants le fonctionnement d'un système de type Unix, lors d'un projet d'étude sur le mode protégé des processeurs Intel 386, Linux Torvalds se mit à développer son propre noyau Unix pour y ajouter de nouvelles fonctionnalités.

Linux ("Linus' Unix") est donc né en 1991 grâce à un étudiant de l'université d'Helsinki. La réussite du nouveau système devra son salut à l'idée de son créateur, L. Torvalds, d'inscrire son projet sous les termes de la licence GPL et de programmer à tous les programmeurs et autres hackers d'internet de l'aider.

*__Remarque__: Le terme de "Hacker" ne doit pas être confondu  avec celui de "cracker" qui désigne un individu cherchant à s'introduire de façon illégale dans un système informatique pour en utiliser les ressources ou en altérer les données. Le mot hacker représente ici les premiers programmeurs sur les systèmes Unix devenus certainement de véritables gourous dans leur domaine et non le pirate informatique mal intentionné.*

### 3.1. Caractéristiques
Les principales caractéristiques de Linux sont les suivantes:
- Multitâche
- Multiutilisateur
- Multiplateforme
- Système de fichiers
- Gestion de la mémoire
- Réseau
- Conformité avec de nombreux standards comme POSIX
  
### 3.2. Distributions
A proprement parlé, Linux n'est pas un système d'exploitation mais seulement son noyau (kernel). Il ne constitue pas à lui seul la totalité du système d'exploitation; pour cela, il doit être accompagné des outils des outils de base communs à tous les Unix.

Ces outils standards étant en grande majorités des logiciels libres, on les retrouve aussi sous Linux, généralement dans un version GNU comprenant nombre d'améliorations par rapport aux originaux. Parmi ces programmes, on distingue le compilateur GNU C/C++, un des meilleurs compilateurs disponibles aujourd'hui.

Il faut aussi évoquer l'ensemble des commandes accessibles directement à partir d'un shell, telles que **grep**, **find**, **awk** ou encore des éditeurs de texte comme **vi**. Pour être précis, le terme GNU/Linux doit être alors utilisé pour désigner ce système et non "Linux" comme trop souvent.

A l'aide d'autres développeurs, Linus Torvalds a ajouté de plus en plus d'outils et d'applications. Au fil du temps, des universités, des compagnies et de simples individus ont commencé à distribuer Linux avec leur propre de paquetage pour accompagner le noyaux Linux. Le concept de distribution Linux est né.

Une distribution GNU/Linux est donc composé du noyau Linux, d'outils de base GNU, d'une suite logicielle praticulière avec une configuration préétablei, et d'outils d'administration propres à la distribution comme l'installateur ou le gestionnaire de paquetage logiciels.

Aujourd'hui, créer et vendre une distribution Linux peut représenter un chiffre d'affaires de plusieurs millions de dollars et il est possible d'acheter les versions "boîte" de grandes compagnies telles que Red Hat ou Suse. Néanmoins, on peut toujours télécharger librement la plupart de ces distributions commerciales ainsi que celles réalisées par des groupes d'individus passionnés.

## 4. Quelles distributions choisir
### 4.1. Les distributions "grand public"
### 4.2. Les distributions "mobiles"
### 4.3. Les distributions "professionnelles"
### 4.4. Les distributions "professionnelles"

## 5. Exercices

###  Test
```shell
$ command -o -p -t
```

```bash
$ command -o -p -t
```
