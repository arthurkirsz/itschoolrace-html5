# HTML5 itschoolrace challenge
#### Equipe Intech we Trust
---
#####Introduction

Pour la réalisation de cette application, l'effort principal a été effectué sur la qualité du code HTML. 


Nous pensons que le HTML doit être utilisé pour la sémantique de l'information et que seul le CSS et le Javascript devraient être responsables du rendu visuel de la page. 
De plus, en l'absence d'utilisation de tailles fixes en pixels, le HTML est à l'origine quasiment responsive. Le parti pris était donc de ne pas utilisé Bootstrap qui ajoute de nombreuses classes et d'éléments non-significatifs dans le DOM dans le but de rendre le site responsive. 
Libéré des contraintes de ce framework, notre HTML est simple, lisible et explicite.


Un effort important a également été réalisé pour que le rendu du site soit optimal sur une vaste majorité des terminaux actuels : media queries, gestion des icones/favicons pour iOS et Android, des tiles sur Windows Phone, gestion des images pour les appareils à haute densité de pixels (hdpi).

#####Librairies et inspiration
Un certain nombre d'éléments ont été intégrés a l'application (Javascript, CSS, icônes). Ils ont été modifiés et améliorés ou adaptés pour construire le projet, et il convient d'en créditer les auteurs :

  - HTML5 Boilerplate v4.3.0 | MIT License
  - normalize.css v1.1.3 | MIT License
  - classie - class helper functions from bonzo
  - fullscreenForm.js v1.0.0 | MIT License
  - Modernizr 2.8.3 | MIT & BSD License
  - Icon by Freepik | Creative Commons BY 3.0 License

#####Equipe

Arthur Kirsz, Vincent Marquet, Guillaume Noël


#####Difficultés rencontrés
Malgré nos compétences en HTML5, certains problèmes sont survenus lors du développement. Un exemple de difficulté est la validation des champs par le Javascript. 

Afin de fournir une expérience utilisateur optimale, il est important de contrôler le remplissage des champs d'un formulaire.

Or, en HTML5, il est possible de renseigner du texte dans un input de type number. Nous nous sommes aperçus que lorsque un visiteur renseigne une chaine de caractère plutot qu'un nombre, la valeur de l'input est une chaine de caractère vide comme si rien n'avait été renseigné. 
Il n'est donc pas possible de différencier un champ non rempli d'un champ mal rempli...   le message d'erreur doit par conséquent être exprimé pour répondre aux deux cas possibles : champ non saisi ou saisie incorrecte.


#####Remerciements
Pierre, notre interlocuteur chez Hackateam, pour sa disponibilité et les réponses qu'il a pu nous apporter sur le brief du projet.

Fabien Lebret pour ses conseils avisés.

Tympanus pour ses nombreux exemples d'UI bien foutues.

