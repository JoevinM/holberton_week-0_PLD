# Introduction au Markdown

Objectif de Markdown
Markdown permet de :

Structurer un texte (titres, paragraphes)

Mettre en forme du texte (gras, italique, listes, etc.)

Integrer des elements comme des images, des liens, du code

 Principales syntaxe Markdown

Titres

markdown

Copier

Modifier

# Titre de niveau 1
## Titre de niveau 2
### Titre de niveau 3
Texte en gras, italique, barrer

Copier
Modifier
**gras** ou __gras__
*italique* ou _italique_
~~barrer~~
Listes
Liste |  puces

markdown
Copier
Modifier
- ~Element 1
- ~Element 2
  - Sous-element

Liste numerotee

markdown
Copier
Modifier
1. Premier
2. Deuxieme

Liens et images
markdown
Copier
Modifier
[Texte du lien](https://exemple.com)

![Texte alternatif](https://url-image.com/image.jpg)
Citations
markdown
Copier
Modifier
> Ceci est une citation.
Code
Dans une phrase :

markdown
Copier
Modifier
Voici du `code` en ligne.
Bloc de code :



``markdown
Copier
Modifier
def bonjour():
print("Salut !")``



Copier
Modifier
Separateur
markdown
Copier
Modifier
---
Format des fichiers Markdown
Les fichiers Markdown ont generalement des extension :
.md (ex. README.md)

Pourquoi utiliser Markdown ?
Simple |  apprendre

Lisible meªme sans conversion

Parfait pour la documentation, blogs statiques, etc.

Compatible avec de nombreux outils (GitHub, Notion, Obsidian, etc.)

# Diffrences entre systemes d'exploitations

Unix

Unix est un ancien systeme d exploitation nee dans les annees 1970.

Il a servi de base |  beaucoup d autres systemes.

C est un systeme souvent proprietaire (non gratuit).

Utiliser  surtout dans les serveurs ousysteme industriels.

Exemples de systemes Unix : AIX, Solaris, HP-UX.

Linux

Linux est un noyau de systeme d exploitation, cree en 1991 par Linus Torvalds.

Il est libre et open-source.

Il est baser sur les idees de Unix, mais n est pas Unix.

De nombreux systemes appeller "distributions" utilisent Linux (comme Ubuntu, Debian, Fee
dora).

 Ubuntu
Ubuntu est une distribution Linux.

C est un systeme d exploitation complet, base sur Linux.

Developper par Canonical, il es concu pour etre simple | utilisable pour les debutants.

Il inclut : le noyau Linux + une interface graphique + des logiciels pret  a l emploi.

Windows

Windows est un systeme d exploitation cree par Microsoft.

Il est proprietaire, et est tres rependu sur les ordinateurs personnels.

Contrairement |  Unix/Linux, sa base technique est differente.

Il est tres orienter interface graphiqu (Bureau, fenetres, clics).


## Questions

### **PLD Questions - Week 0**

1. **C'est quoi Emacs et Vim ?**

Des Ãditeurs de textes.

2. **C'est quoi Git ?**

C'est une commande et une version controle systeme

3. **C'est quoi GitHub ?**

Cela permet de stocker ses repo en ligne.

4. **Quelle est la diffence entre Git et GitHub ?**

L'un est en Commande Bash et l'autre en interface graphique.

5. **Est-ce que les commandes `git add...` et `git commit ...` suffisent pour monter notre code sur GitHub ?**

Non il faut Ã©galement la commande Git Push.

6. **Parmi ceux-ci, quels sont les meilleurs messages de commits :**

   - a) aaaaaa
   - b) Add the README.md file with the project description and a summary of the used commands.
   - c) please work
   - d) add files
   - e) Update the command argument on the file to output the correct format.

La reponse b) et e)

7. **Pour se renseigner sur une nouvelle commande Linux, quelle est la premiere chose que je dois faire :**

   - a) Lire le man page de la commande sur le terminal.
   - b) Demander une explication de la commande |  mes collegues.

La reponse a) et si l'on ne comprend pas ou ne trouve pas La reponse b).

8. **Est-ce que je peux faire un `git push` sans avoir fait un nouveau commit ?**

Non il faut commit d'abord.

9. **RTFM signifie quoi ?**

Read the fu****** manual.

10. **Qu'est-ce qu'elle fait la commande `cd -` ?**

Cette commande permet de switcher au dernier repertoire prcedent.

11. **Qu'est-ce qui se passe si on tape `cd` tout court ?**

On retourne compltement a la racin.

12. **C'est quoi la caracteristique special des fichiers caches sous Linux ?**

Il commence par un "." .

13. **Qu'est-ce que la commande `man` ?**

Cela permet d'afficher le manuel d'utilisation d'une application dans le Shell.

14. **Comment chercher un mot cle sur une page man d'une commande Linux ?**

Ctrl+F .

15. **Comment copier plusieurs fichiers en meme temps avec la commande `cp` ?**

cp *

16. **Qu'est-ce que le dossier `/tmp` sous le systeme Linux ?**

C'est le dossier temporaire de la machine.

17. **Quelle est la difference entre un chemin absolu (absolute path) et un chemin relatif (relative path) sous Linux ?**

le chemin absolu est le chemin complet depuis le root et le chemin relatif est baser sur le repertoire courant.

18. **Comment peut-on facilement identifier un chemin absolu ?**

Il commence par un "/"
