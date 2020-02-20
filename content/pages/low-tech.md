Title: Teushirt : low-tech
Date: 2010-12-03 10:20
Modified: 2010-12-05 19:30
Category: pages
Tags: pelican, publishing
Slug: low-tech
Authors: robrob
Summary: la page qui explique pourquoi la démarche est low-tech
Status: hidden
Size: 150kb


###Un site low-tech, ça existe ?

_Low-tech_, ce n'est pas juste le dernier buzzword des bobos écolos. C'est une philosophie qui s'est mise en place face aux enjeux posés par les high-techs. Pollutions, émissions de CO2, technologies propriétaires, épuisement des minerais, travail dans des conditions inhumaines, créations de dépendances géopolitiques et même de dépendances dans nos vies quotidiennes... <br>La liste est longue et pourrait nous donner envie de tout débrancher ! Mais pas si vite. Internet et les télécommunications ont permis de grandes choses, et ce serait dommage de s'en priver. 

###Alors, les low-techs, c'est quoi ?

Les low-techs, ce sont des technologies que l'on développe selon 3 grands principes :<br><br>
![Low-techs]({static}/images/dithers/lowtech.png#right)
**#** _Elles doivent être **durables**_ : fabriquées avec des ressources renouvelables, elles consomment le moins possible et l'énergie consommée doit être écologique. Leur cycle de vie doit être réfléchi en amont de bout en bout : l'obsolescence programmée est bien entendu hors sujet, et le réemploi ou la revalorisation est de mise.<br>
**#** _Elles doivent être **accessibles**_ : elles sont autoconstructibles et réparables par les autres. Cela implique que l'on puisse jeter un coup d'oeil sous le capot sans compromettre leur utilisation, et qu'en un temps relativement court, chacun d'entre nous puisse être capable d'acquérir les compétences pour les mettre sur pied. Leur éventuel prix doit toujours refléter leur valeur intrinsèque.<br>
**#** _Elles doivent être **adaptées**_ : elles répondent toujours à un besoin réel, et de manière efficace. Elles ne doivent pas être aliénantes dans leur utilisation et respectent l'intégrité de chacun.

###Du coup, internet, c'est vraiment pas low-tech...
![Tim]({static}/images/dithers/timbernerslee.png#left)
Au moment de son invention, Internet portait en lui beaucoup d'attributs low-tech. Il s'agissait de construire un réseau d'échange d'informations que tous les humains de la planète allait pouvoir utiliser, sans réstriction. Internet a permis grâce à l'intelligence collective et au travail collaboratif de repousser les limites de notre connaissance et de rendre chacun plus autonome. Certes, les notions d'écologie n'étaient pas du tout présentes à la naissance du web, mais si c'était à refaire aujourd'hui, sûr que Tim Berners Lee y mettrait davantage du sien. <br>Bref, tout espoir n'est pas perdu, et aujourd'hui des solutions existent pour rendre internet **plus durable, plus accessible et plus adapté**.

###Pourquoi _teushirt.org_ est différent ?

Sur le modèle décrit par [Low-tech Magazine](https://solar.lowtechmagazine.com/2018/09/how-to-build-a-lowtech-website.html), des sites web plus low-tech sont en train d'émerger. En pratique, comment on fait ?

**#** **un amour de serveur** : le premier problème avec internet, c'est l'hébergement. On a tous en tête cette image des méga data-centers bourré de données consommant autant d'énergie qu'un pays de l'hémisphère sud... On en est pas loin. Le truc, c'est que plus la vitesse de connexion augmente, plus les données que l'on consomme sont lourdes.La 3G a vu l'avènement des vidéos 1080p, la 4G la 4K et la 5G ? La 8K. Plus de données, ça veut dire plus de serveurs, et plus de transit sur le réseau. Tout ça consomme énormément d'énergie, au point qu'aujourd'hui une entreprise comme Netflix émet autant de CO2 que l'Espagne. Donc faire un site web low-tech, ça veut dire déjà, avoir un serveur qui consomme peu, et surtout le plus renouvelable possible.<br>
_teushirt.org_ est hébergé en Belgique sur des serveurs mutualisés mis à disposition par [all2all](http://www.all2all.org/fr/), une association à but non lucratif. Une [charte stricte](http://www.all2all.org/fr/informations/about-all2all/charte/) est suivie tant sur le point de vue éthique qu'écologique. Entre autres, leurs serveurs sont alimentés par de l'électricité renouvelable, ils tournent sur une distribution de Linux open-source et la protection des données est primordiale.<br>

**#** **un site poids plume** : faire un site web low-tech, ça veut bien sûr dire faire léger. Aujourd'hui, une page web pèse en moyenne 2Mo, et les chiffres sont à la hausse. Les grandes vitesses de connexions dont nous profitons ont abolit toute limite de taille.  _teushirt.org_ est developpé de manière minimaliste afin de peser le moins lourd possible. Adieu animations, vidéos en arrière-plan et typographies propriétaires. Notre site est statique, n'utilise aucune police spéciale ni aucune animation, ce qui le rend très léger. En plus d'être écologique, cela le rend accessible depuis des appareils anciens plus du tout capable d'ouvrir des sites web récents.<br>

**#** **images allégées** : ce qui pèse le plus lourd, sur internet, c'est bien sûr les vidéos, puis les photos. Pas question de vidéo sur _teushirt.org_ (finalement, le gif de la page d'accueil est une sorte de vidéo low-tech?), mais on trouvait dommage de se passer complètement d'image. Alors on a décidé de suivre la méthode de dithering décrite par Kris de Decker pour Low-tech Magazine. On réduit les images à 6 niveaux de gris ou de couleurs. Ainsi, on garde la majorité de l'information tout en divisant par 5 voire par 10 la taille des images. La page [Je veux voir !]({static}/category/articles.html) donne donc un aperçu allégé de nos teushirts. Si l'envie vous prend d'en voir un de plus près, en cliquant dessus, vous accédez à la version complète de l'image, plus lourde. Elle n'est donc pas chargée par défaut, mais sur demande.<br>

**#** **Design & thème à clic** : faire un site allégé, cela voulait nécessairement dire renoncer aux thèmes tout prêts tout migons de WordPress, souvent lourds et gourmands en ressource. Alors il a fallu repenser le design de zéro. Heureusement, une fois de plus, Low-tech Magazine était là pour aider. Des textes clairs et qui jouent sur la taille, des couleurs simples, et des images parcimonieuses. Evidemment, on a aussi pensé à la version mobile.

**#** **Open-source** : le site a été généré avec Pelican, un gestionnaire de contenu très léger et simple à utiliser. Tout le thème conçu pour _teushirt.org_ est disponible sur [github](https://github.com/MartinBaron/pelican_theme_teushirt), pour que vous puissiez le réutiliser et l'adapter à vos besoins.<br><br>
![Taille des pages web depuis 2011]({static}/images/pagezise_original.png#center)



