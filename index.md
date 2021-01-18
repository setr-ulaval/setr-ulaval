[doc]: https://setr-ulaval.github.io/img/icon-doc.png
[slides]: https://setr-ulaval.github.io/img/icon-slides.png
[video]: https://setr-ulaval.github.io/img/icon-video.png

# Systèmes embarqués temps réel - GIF-3004 #

*Synopsis* : Ce cours porte sur l'analyse et la conception de systèmes embarqués avec systèmes d'exploitation standards et temps réel. Il présente le rôle des systèmes d'exploitation dans les systèmes embarqués pour la gestion de l'exécution des programmes, l'encapsulation du matériel, et l'offre de primitives et de services logiciels. Le cours porte également sur les notions conceptuelles et pratiques de systèmes temps réel. Les notions conceptuelles sont mises en pratiques, par le développement d'applications logicielles pour systèmes embarqués avec systèmes d'exploitation. Les travaux sont réalisés en langage de programmation C sur une plateforme matérielle ARM et des systèmes d'exploitation ouverts. 

## Chronologie et présentations ##

| Sem. | Dates              | Cours mardi 13h30-15h20 (PLT-2765)    | Ateliers vendredi 9h30-11h30 (PLT-0105)  | Laboratoires  |
| :--: | :---------         | :------------------------------       | :----------------------                  | :----------- |
| 1    | 13-17 janvier	    | [Présentation du cours](https://sitescours.monportail.ulaval.ca/contenu/sitescours/036/03606/202001/site113810/modules725524/module934565/page2599044/bloccontenu2449993/setr-sem01-presentation.pdf) ![][slides]<br/> [Introduction aux systèmes embarquées temps réel](https://sitescours.monportail.ulaval.ca/contenu/sitescours/036/03606/202001/site113810/modules725524/module934566/page2598987/bloccontenu2450013/setr-sem01-introduction.pdf) ![][slides] | [Développement sur RPi](https://sitescours.monportail.ulaval.ca/contenu/sitescours/036/03606/202001/site113810/modules725524/module934584/page2599046/bloccontenu2449994/setr-sem01-atelier-rpi.pdf) ![][slides] | [Énoncé labo 1](labo1.html) |
| 2    | 20-24 janvier      | [Systèmes d'exploitation et programmation concourante](https://sitescours.monportail.ulaval.ca/contenu/sitescours/036/03606/202001/site113810/modules725524/module934567/page2599042/bloccontenu2450012/setr-sem02-sysexp.pdf) ![][slides] | [UNIX et ligne de commande](https://sitescours.monportail.ulaval.ca/contenu/sitescours/036/03606/202001/site113810/modules725524/module934584/page2599046/bloccontenu2449994/setr-sem02-atelier-terminal.pdf) ![][slides]<br/> Évaluation labo 1 | |
| 3    | 27-31 janvier      | Systèmes d'exploitation et programmation concourante | [Labo 2 : système de fichiers](https://sitescours.monportail.ulaval.ca/contenu/sitescours/036/03606/202001/site113810/modules725524/module934585/page2598989/bloccontenu2450014/setr-sem03-atelier-labo2.pdf) ![][slides]<br/> Évaluation labo 1 | [Énoncé labo 2](labo2.html) |
| 4    | 3-7 février        | [Programmes temps réel](https://sitescours.monportail.ulaval.ca/contenu/sitescours/036/03606/202001/site113810/modules725524/module934568/page2599040/bloccontenu2450011/setr-sem04-tempsreel.pdf) ![][slides] | [Programmation système en C](https://sitescours.monportail.ulaval.ca/contenu/sitescours/036/03606/202001/site113810/modules725524/module934585/page2598989/bloccontenu2450014/setr-sem04-atelier-progsys.pdf) ![][slides] | |
| 5    | 10-14 février      | Programmes temps réel | | |
| 6    | 17-21 février      | [Entrées/sorties et gestion de la mémoire avec temps réel](https://sitescours.monportail.ulaval.ca/contenu/sitescours/036/03606/202001/site113810/modules725524/module934569/page2598985/bloccontenu2450010/setr-sem06-esmemoire.pdf) ![][slides] | [Labo 3 : multiplexeur de vidéos temps réel](https://sitescours.monportail.ulaval.ca/contenu/sitescours/036/03606/202001/site113810/modules725524/module934586/page2598991/bloccontenu2450015/setr-sem06-atelier-labo3.pdf) ![][slides]<br/> Évaluation labo 2 | [Énoncé labo 3](labo3.html) |
| 7    | 24-28 février      | **Examen partiel** au local **PLT-3775** | [Labo 3 : implémentation et détails techniques](https://sitescours.monportail.ulaval.ca/contenu/sitescours/036/03606/202001/site113810/modules725524/module934586/page2598991/bloccontenu2450015/setr-sem07-atelier-implementation.pdf) ![][slides] | |
| 8    | 2-6 mars           | **Semaine de lecture** | | |
| 9    | 9-13 mars          | [Noyau Linux](https://sitescours.monportail.ulaval.ca/contenu/sitescours/036/03606/202001/site113810/modules725524/module934570/page2598983/bloccontenu2450009/setr-sem09-linux.pdf) ![][slides] | | |
| 10   | 16-20 mars         | [Développement de pilotes dans Linux](https://sitescours.monportail.ulaval.ca/ena/site/module?idSite=113810&idModule=934571&idPage=2598963) ![][slides] ![][video] | [Labo 4 : pilote de périphérique](https://sitescours.monportail.ulaval.ca/ena/site/module?idSite=113810&idModule=934587&idPage=2599048) ![][slides] ![][video] | [Énoncé labo 4](labo4.html) |
| 11   | 23-27 mars         | [Communication et synchronisation](https://sitescours.monportail.ulaval.ca/ena/site/module?idSite=113810&idModule=934572&idPage=2598926) ![][slides] ![][video] | | [Énoncé labo 5](labo5-projet.html) |
| 12   | 30 mars - 3 avril  | [Systèmes parallèles](https://sitescours.monportail.ulaval.ca/ena/site/module?idSite=113810&idModule=934573&idPage=2607532) ![][slides] ![][video] | Évaluation labo 3 | |
| 13   | 6-10 avril         | [Théorie des files d'attente](https://sitescours.monportail.ulaval.ca/ena/site/module?idSite=113810&idModule=934574&idPage=2607549) ![][slides] ![][video] | Congé (Vendredi saint) | Proposition labo 5 |
| 14   | 13-17 avril        | [Fiabilité et tolérance aux fautes](https://sitescours.monportail.ulaval.ca/ena/site/module?idSite=113810&idModule=934575&idPage=2609676) ![][slides] ![][video] | | |
| 15   | 20-24 avril        | **Examen final** dans monPortail| Évaluation labo 4 | |
| 16   | 27 avril - 1er mai | | Évaluation labo 5 | |


---

## Laboratoires ##

Le cours comporte cinq laboratoires. La plateforme utilisée est [Raspberry Pi Zero W](https://www.raspberrypi.org/products/raspberry-pi-zero-w/) avec système d’exploitation Linux, programmé en C. L'ensemble Raspberry Pi Zero W du cours est en vente au magasin du service technique du département de génie électrique et de génie informatique (PLT-3112) au coût de 57 $.

| Laboratoire                                                         | Remise code source  |
| :----------------                                                   | :-----------------  |
| [Labo 1 : environnement de développement](labo1.html) &nbsp;&nbsp;  | Pas de remise |
| [Labo 2 : système de fichiers](labo2.html)                          | Vendredi, 21 février, 9h30 |
| [Labo 3 : multiplexeur de vidéos temps réel](labo3.html)            | Lundi 30 mars, midi |
| [Labo 4 : pilote de périphérique](labo4.html)                       | Vendredi, 24 avril, midi |
| [Labo 5 : projet](labo5-projet.html)                                | Vendredi, 1er mai, midi |

