Template de Game Design Document
================================

Ceci est un portage du template de *Game Design Document* écrit originèlement par des membres de l'association `Futurn <http://240plan.ovh.net/~pepitela/futurn/index.php?op=edito>`_.

Ce document vous montre la marche à suivre pour rédiger correctement un `GameDesign Document <http://en.wikipedia.org/wiki/Game_design_document>`_ dans le but de créer vos propres jeux vidéo.

Ce portage a été réalisé à l'aide de `Sphinx <http://sphinx-doc.org>`_ un puissant générateur de documentation. Celui-ci permet de produire à partir de fichiers `ReStructuredText <http://fr.wikipedia.org/wiki/ReStructuredText>`_ des documents HTML, Latex, PDF ou encore Epub.


Installation
------------

Avant toute chose il vous faut récupérer les sources de ce dépôt::

    $ git clone git://github.com/skitoo/game-design-document.git


Puis lancer l'installation nécéssaire au projet::

    $ cd game-design-document
    $ pip install -r requirements.txt



Utilisation
-----------

Maintenant que tout est bien installé, il vous suffit d'éditer le fichier **conf.py** présent le dossier **source**. Modifiez notamment les variables **author**, **title** et **project**::
    
    project = u'game-design-document'
    title = u'My Game'
    author = u'My Name'


Vous pouvez maintenant éditer l'ensemble de votre *GameDesign Document* à l'aide de ReStructuredText.


Génération du document
----------------------

Maintenant que votre document est édité vous pouvez le générer. Pour cela allez à la racine de votre projet puis lancez la commande make::

    $ # pour l'HTML
    $ make html

    $ # pour Latex
    $ make latex

    $ # pour le PDF
    $ make latexpdf

    $ # pour l'Epub
    $ make epub


Votre document est alors généré dans le dossier *build*.


Auteurs
-------

Co-rédacteurs :

* Victor SMEU 
* Jean Etienne GOUBARD 
* Benoît ROBIN

Inspirations :

* `Gamasutra <http://gamasutra.com>`_

Porteur du document sous Sphinx :

* `Alexis Couronne <http://skitoo.net>`_

