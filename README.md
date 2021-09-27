# TP2 : Introduction Programmation

### Objectif
Manipuler les instructions de bases :

- Types primitifs & Wrapper
- Variables & opérateurs
- Instructions
- Boucles

### Prérequis
- Cloner le projet sur votre poste dans le repertoire de votre choix
- Ouvrir le projet TP2
  - Sur l'écran d'accueil d'IntelliJ, cliquer sur **New Project**
  - Selectionner **Java** dans la liste de gauche et **17** dans **Project SDK** puis Next
  - Ne rien cocher puis **Next**
  - Cliquer sur les **...** de **Project location** puis selectionner le dossier du projet tp2-xxxxx et cliquer sur **OK**
  - Cliquer sur **Finish**
  - Le projet s'ouvre

### RAPPEL Utilisation de GIT !!!!!
- Créer une nouvelle branche **prenomNom**  

```
$ git branch prenomNom
$ git checkout prenomNom
```

### Exercices

- Resoudre vos exercices directement dans chaque méthode *main()* de chaque Classe *ExerciceN*
- **Après chaque exercice**, faire un commit :

```
$ git add .  
$ git commit -m "Exercice x"
```

- A la fin du cours

```
$ git push origin prenomNom
```
-  Ouvrir **une seule** *pull request* sur github et **ne pas** la fermer/merger !!

- De chez vous, pour chaque exercice :

```
$ git add .
$ git commit -m "Exercice x"
```

- A la fin de tous les exercices

```
$ git push origin prenomNom
```

- Ne pas merger de pull request !!

### Exercice 1

Montrer que le theorème de pytagore est vrai avec un triangle rectangle de côté : 3, 4 et 5

### Exercice 2

Un jardinier amateur veut créer 4 carrés jardin de 1,25m x 1,25m. Il peut planter 9 plantes par carré. Ecrire un programme qui affiche la surface cultivée et le nombre plantes cultivables.

### Exercice 3

Les parachutistes sautent souvent à 4000 mètres (contante). Calculer et afficher la hauteur en "pieds" ?

### Exercice 4

Un radiateur de 500W chauffe 8m3, combien faut-il de radiateurs pour chauffer une pièce de 3,40 x 4,30 x 2,30

### Exercice 5

Sachant que ```ThreadLocalRandom.current().nextInt(0,2)``` retourne 1 ou 0, écrire un programme qui affiche *Vrai* si 1 ou *Faux* si 0 selon le résultat retourné.

### Exercice 6

Sachant que ```ThreadLocalRandom.current().nextInt(1,101)``` retourne un chiffre entre 1 et 100, écrire un programme qui affiche *Le nombre x est Pair* ou *Le nombre x est Impair* selon le résultat retourné.

### Exercice 7

Ecrire un programme qui détermine si l'année 1900 est bisextile. Une année est bissextile 
- si elle est divisible par 4 et non divisible par 100, ou
- si elle est divisible par 400.

### Exercice 8

Afficher une chaine contenant "3896,86 / 4,869 = " complétée par le résultat du calcul

### Exercice 9

Convertir la chaine **HELLO WORLD** en minuscule et **hello world** en majuscule et affichez les.
*Pensez à la richesse de l'API Java !*

### Exercice 10

Convertir **CNAM** en **Cnam** et afficher la. Pas de triche, ça doit fonctionner si on change CNAM en DGAC. 
*Là encore pensez à la richesse de l'API java, il doit exister une fonction pour récupérer la première lettre d'une chaine*

### Exercice 11

Calculer combien il y a de voyelles dans la phase "cette phrase contient 11 voyelles".   
*Pensez a faire des comparaisons entre chaque lettre de la phrase et des variables qui contiennent les voyelles*

### Exercice 12

Calculer le factoriel de x, x étant une constante que vous choisissez 
*(rappel : factoriel n!  = 1 x 2 x 3 x ... x n)*

### Exercice 13

Ecrire un programme qui répond *Vrai* si une phrase est un palindrome et *faux* dans le cas contraire. (exemple *Esope reste ici et se repose*)

### Exercice 14

A partir de https://fr.wikipedia.org/wiki/ROT13, écrire un programme qui 
- chiffre : "ceci est mon message secret"
- dechiffre : "tbbq tnzr"

Aidez vous de la table ASCII (le codage de **a** en char vaut **97**)

### Exercice 15

Ecrire un programme qui dessine un sapin de hauteur x (x est une constante).
```
    *
   ***
  *****
 *******
*********
```

### Exercice 16

Ecrire un programme qui dessine un sapin **vide** de hauteur x (x est une constante).
```
    *
   * *
  *   *
 *     *
*********
```
