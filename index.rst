.. PIGAL documentation master file, created by
   sphinx-quickstart on Mon Nov 25 11:24:13 2013.
   You can adapt this file completely to your liking, but it should at least
   contain the root `toctree` directive.

PIGAL Python Interactive Graph Analysis Library 
=================================

Description technique version 1.1
-----------------
PIGAL est une application web pour l’analyse par la théorie des graphes des interactions anatomiques et fonctionnelles dans le cerveau humain

Laboratoires
~~~~~~~~~~~~~~~~~~~~~~
Laboratoire d'imagerie Fonctionnelle
UMR_S 678 Inserm/UPMC
CHU Pitié-Salpêtrière
91 boulevard de l’Hôpital, 75013 Paris

|LIF|_

|Inserm|_ |UPMC|_


.. |Inserm|  image:: http://www.inserm.fr/var/inserm/storage/images/inserm/219-19-fre-FR/inserm.fr.gif
.. _Inserm: http://www.inserm.fr/

.. |UPMC|  image:: http://www.upmc.fr/skins/UPMC/templates/index/resources/img/upmc-logotype.gif
.. _UPMC: http://www.upmc.fr/

.. |LIF|  image:: http://www.google.fr/url?source=imglanding&ct=img&q=http://linem.imed.jussieu.fr/img/LogoLIF.gif&sa=X&ei=0g-4UrjTCKmq0QWZj4HQDQ&ved=0CAkQ8wc&usg=AFQjCNGi0BR8XtvqX1Sc6j6iOB7_ELz5Tw
.. _LIF: http://www.imed.jussieu.fr/


Auteurs
~~~~~~~~~~~~~~~~~~~~~~
KETZINGER Jean-Christophe, Ingénieur de Recherches (IR) - UPMC

MESSE Arnaud, Ingénieur de Recherches (IR) - IHU-A-ICM

PELEGRINI-ISSAC Mélanie, Ingénieur de recherches (IR) - Inserm

BENALI Habib,Directeur de recherche (DR) - Inserm

Brève description
-----------------

Le cerveau humain est un réseau complexe dont les connexions fonctionnelles et anatomiques peuvent être étudiées à partir de données de neuroimagerie (en particulier d'IRM fonctionnelle et de diffusion). Ce réseau peut être représenté sous forme de graphe, ce qui fait de la théorie des graphes une approche de choix pour l'analyse de la connectivité anatomo-fonctionnelle. J'ai développé la plateforme logicielle Web ''Python Interactive Graph Analysis Library'' (PIGAL), qui permet de calculer de nombreuses mesures sur les graphes, de les comparer entre sujets, et de les visualiser de façon interactive. Le logiciel a été validé sur des données de connectivité anatomique de sujets sains et sur des données de connectivité fonctionnelle de patients atteints du syndrome de Gilles de la Tourette, ce qui a permis d'obtenir des résultats conformes à ceux de la littérature. 

Contents:

.. toctree::
   :maxdepth: 2
   
   tutoriel

Introduction
-----------------
Notre cerveau est un réseau présentant une organisation à deux niveaux. D'une part, il existe
une représentation fonctionnelle selon laquelle des régions de la substance grise du cerveau, qui
peuvent être distantes les unes des autres, échangent de l'information pour gérer nos fonctions
cognitives et comportementales.

D'autre part, cette information circulant sous forme électrique le long des axones de la substance
blanche, il existe une représentation anatomique des liens structurels entre les différentes
régions du cerveau, liens que l'on peut cartographier. Ces deux représentations impliquent qu'il
existe une connectivité fonctionnelle et une connectivité anatomique dans le cerveau humain.

Depuis la dernière décennie, les techniques d'imagerie cérébrale, qu'elles soient anatomiques
ou fonctionnelles, connaissent une évolution sans précédent, en particulier l'imagerie par résonance
magnétique (IRM) fonctionelle (IRMf) et de diffusion (IRMd). Les méthodes d'analyses
des données acquises suivent une évolution similaire. L'utilisation de la théorie des graphes a
récemment été proposée pour étudier l'organisation générale du cerveau humain. Elle a pour but
d'établir un plan complet de la connectivité anatomo-fonctionnelle cérébrale et de révéler des
biomarqueurs efficaces permettant par exemple de caractériser des pathologies et leur évolution
au cours du temps.

Ce travail s'inscrit dans l'optique de faciliter l'analyse par la théorie des graphes des interactions
anatomo-fonctionnelles cérébrales. **Il a eu pour objectif le développement de la
boîte à outils PIGAL (Python Interactive Graph Analysis Library), qui propose de
mettre à disposition une interface simple d'utilisation regroupant de nombreuses
fonctionnalités liées à la théorie des graphes, favorisant des comparaisons de cohortes
par le biais de méthodes statistiques conventionnelles et proposant des outils
de visualisation interactive. Ce logiciel ayant pour objectif d'être accessible, modulable
et facile à améliorer.**

De nombreux outils sont disponibles sur le Web pour appliquer la théorie des graphes. Il
existe des bibliothèques de fonctions et des scripts nécessitant de réaliser les calculs en ligne
de commande (e.g. Brain Connectivity Toolbox ou NetworkX), il existe aussi des logiciels à
installer en local proposant une interface graphique (e.g. Graph Analysis Toolbox, Brain Net
Viewer, Multimodal Brain NETwork, igraph) ou encore des applications Web (e.g. The Virtual
Brain, UCLA Multimodal Connectivity Database) dont les codes sources ne sont pas toujours
accessibles. Les caractéristiques techniques de ces outils sont comparées dans la section 1. Cependant,
il n'existe pas, à ce jour, d'outil permettant à la fois la comparaison de groupes, la
visualisation interactive et le calcul de mesures de la théorie des graphes. N'ayant pu rencontrer
l'évolutivité et la clarté d'utilisation souhaitée, Arnaud Messé a donc proposé à Jean-Christophe
KETZINGER de contribuer à combler ce manque et de développer le projet PIGAL.


Indices and tables
==================

* :ref:`genindex`
* :ref:`modindex`
* :ref:`search`

