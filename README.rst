
OSM-FR integration into KDE marble
=====================================

The french community did a very good job at providing an `OpenStreetMap rendering <http://tile.openstreetmap.fr/>`_ well adapted for french people.

The virtual globe `Marble <https://marble.kde.org/>` from KDE is also a good software to navigate through the world.

This project provides a Marble map that uses OSM-FR rendering. It also provides HillShading as an option.

To browse the maps osmfr into marble, just do :

..
  cd .local/share/marble/maps/earth
  git clone https://github.com/adrien-github/osmfr.git

This software contacts the following servers:
- \*.tile.openstreetmap.fr for the map tiles
- \*.tiles.wmflabs.org for the hillshading

Any improvement is welcome!

:Author: Adrien Grellier <perso@adrieng.fr>
:Date: 2017-05-05
:License: BSD 3-clause

.. vim:set filetype=rst:
