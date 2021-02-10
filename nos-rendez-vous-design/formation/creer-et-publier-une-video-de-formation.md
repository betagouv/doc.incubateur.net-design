---
description: >-
  Cette page vise à donner des conseils pour publier des contenus vidéos
  accessibles en optimisant le processus de production au mieux.
---

# Créer et publier une vidéo de formation

### Préparer

* **Préparer un support de présentation** classique avec logiciel comme Keynote sur mac OS ou Power-point. Ces deux logiciels proposent une fonction d’enregistrement des présentations qui vont faciliter la suite.
* **Numéroter les slides** pour faire le lien entre le support et les commentaires écrit par ailleurs.
* **Écrire une trame pour chaque slide** de ce qui va être raconté à l’oral, par exemple dans les notes de présentateurs.
* Si vous devez montrer une autre source vidéo que la présentation, par exemple si la formation porte sur une application, utiliser un outil de montage vidéo comme [OBS Open Broadcaster Software](https://obsproject.com),  libre et open source. Ce logiciel permet de mixer en temps réel les sources suivant différentes configurations prévues et d'enregistrer ou de diffuser le fux sortant. Il peut être un peu long à prendre en main mais il permet beaucoup de choses comme, par exemple, intégrer ce qui se passe sur un écran de smartphone relié à l’ordinateur.

### Enregistrer

* **S'enregistrer** : une fois les préparatifs en place, l’enregistrement peut commencer. Il ne faut pas se faire d’illusion, vous allez vous y reprendre à plusieurs fois…
  * Keynote permet de revenir en arrière pour corriger les dernières minutes en conservant le début sans faire de montages vidéos.
  * La dernière version de Power-point permet la reconnaissance automatique de la voix pour permettre le sous-titrage. Je n’ai pas testé mais si ça marche correctement ça serait vraiment un plus !
* **Exporter la vidéo** : le fichier vidéo pouvant être un peu lourd, il peut être intéressant de l’alléger. En particulier si vous parlez avec slides statiques, il n’est pas nécessaire d’avoir 60 images par secondes, 10 suffiront largement. [Handbrake](https://handbrake.fr) permet de faire cela facilement notamment avec les pré-réglages ou en farfouillant dans les moult paramètres.

### Publier

* **Choisir une plateforme** où publier sa vidéo :
  * Youtube : 
    * Avantage majeur : fait le sous-titrage en partie automatiquement. 
    * Inconvénient : sa politique et son modèle économique.
  * Vimeo : 
    * Avantage : pas de publicité.
    * Inconvénient : moins de visibilité, limité à 500 mo de vidéo par semaine en version gratuite, 5 Go au total.
  * Peertube : 
    * Avantage : éthique et sans limite.
    * Inconvénient : il faut installer et maintenir son instance, ce n’est pas forcément à la portée de tout le monde.
  * Daily-motion :
    * Inconvénient : service en perte de vitesse, non maintenu.
* **Publier le transcript** rédigé à partir des notes de présentateurs préparées slides par slides \(d'où l'interet de numéroter les slides\).
* **Publier le support de présentation au format PDF** \(accessible\) pour qu'il soit consultable par tous.

### Sous-titrer

**À noter : rendre accessible les contenus est une obligation légale.**

Quelques liens utiles sur le sous-titrage :

* [Comment bien sous-titrer les vidéos ?](https://www.24joursdeweb.fr/2019/comment-bien-sous-titrer-les-videos/)
* [Sous-titre une vidéo, c’est nécessaire et c’est plus simple qu’il n’y parait !](https://access42.net/sous-titres-video-accessibilite-web)

Disons-le tout de suite, c’est une étape est fastidieuse mais nécessaire donc **commencez par générer des sous-titres automatiquement,** cela permet d'avoir une synchronisation avec la vidéo qui serait très chronophage à faire manuellement. Trois solutions pour cela  :

* Avec Youtube qui propose des sous-titres automatiques sur vos vidéos.
* Avec un service payant comme [authôt.com](https://authôt.com) ou [trint.com](https://trint.com) qui fait la transcription automatique.
* Avec Power-point qui intégre cette fonction.

Il est nécessaire de corriger les sous-titres générés automatiquement :

* En payant avec [authôt.com](https://authôt.com) \(à la minute\), [trint.com](https://trint.com) \(abonnement mensuel\). La qualité de sous-titrage est similaire sur les 2 services.
* À la main : cela va vous prendre deux à trois fois le temps de la vidéo.
* Sur YouTube, vous avez l'option de permettre à vos utilisateurs de corriger les sous-titres.
* En suite vous récupérer le fichier des sous-titres au format .srt et  vous pouvez affiner le résultat obtenu avec  [Aegisub](http://www.aegisub.org) qui permet d’ajuster les retours lignes et les enchainements des phrases \(et bien d'autres ajustements ou créations\).
* **N'oubliez pas de publier les sous-titres en uploadant le fichier .srt sur Vimeo ou Youtube.**

