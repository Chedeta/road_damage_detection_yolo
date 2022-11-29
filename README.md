# Road Damage Detection - Challenge avec Yolov5

🎬 <a href='https://share.vidyard.com/watch/ghGTNqG6qGF15jbiDgqw2M?'>Cliquer ici pour la vidéo de présentation du projet</a>

## 1. Présentation du sujet

L'entretien et la gestion des routes est un sujet majeur, celui ci ayant un impact important sur la vie des gens.

Actuellement, la plupart des méthodes qui permettent d'analyser et qualifier l'état des routes se contentent de ressources humaines souvent coûteuse à la fois en temps et en argent. Ce qui limite le nombre de contrôles qui pourraient être effectués.

De ce constat a vu le jour un projet ambitieux, le Global Road Detection Challenge en 2018, ayant pour objectif la mise en place et l'entrainement d'une IA adaptable à l'ensemble des routes du monde à l'aide d'un jeu de données de défauts routiers labélisé.

Le dataset utilisé dans cette étude est un jeu de données de 2020 portant sur 3 pays :

<ul>
  <li>Inde : 7 706</li>
  <li>Japon : 10 506</li>
  <li>Tchéquie : 2 829</li>
</ul>

A chacune des photos est associé un fichier <code>.xml</code> contenant une liste des défauts présents sur l'image avec leur catégorie et leurs boundig box.

<img src="https://iili.io/DubqG4.md.png">

## 2. Aperçu des défauts

Le dataset est fourni avec une description des défauts présents sur la route :

<img src="https://iili.io/DA3bb2.md.png">


## 3. Aperçu des résulats

L'ensemble du projet a été développé à l'aide de Google Collab, l'outil étant mieux adapté pour l'utilisation de Yolov5 et des dépendances.

![image](https://user-images.githubusercontent.com/96300465/202906951-1b7ebe74-5daa-4a97-aeb2-c123c45f8f63.png)

Plusieurs trainings avec plusieurs épochs et finetuning différents ont permis de déterminer le meilleur run parmi ceux effetués, qui a ensuite été intégré à l'outil de visualisation de modèles Gradio.

![image](https://user-images.githubusercontent.com/96300465/202907054-88f0086a-aa29-4f93-bc70-6437ea781da3.png)

## 4. Crédits

Auteur : Jean Ivars, avec la participation de <a href='https://github.com/Bebock'>Hélène</a>, <a href='https://github.com/HenriPuntous/'>Henri</a> et <a href='https://github.com/NBridelance'>Nicolas</a>.
