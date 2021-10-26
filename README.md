# Transformez une maquette en site web

[![Codacy Badge](https://api.codacy.com/project/badge/Grade/1296c230d59347649e304c3bc11ce18e)](https://app.codacy.com/gh/raficraft/OCR_reservia?utm_source=github.com&utm_medium=referral&utm_content=raficraft/OCR_reservia&utm_campaign=Badge_Grade_Settings)
[![Codacy Badge](https://app.codacy.com/project/badge/Grade/6c59cd6fae134d43a0a5e0cb98e8b872)](https://www.codacy.com/gh/raficraft/OCR_reservia/dashboard?utm_source=github.com&amp;utm_medium=referral&amp;utm_content=raficraft/OCR_reservia&amp;utm_campaign=Badge_Grade)

Intégration maquette HTML/CSS 

Deuxième projet du parcours développeur web d'OpenClassRooms.

## Objectif

Intgration d'une maquette founrie au format *.PNG d'un site de réservations de vacances.

![Lien](https://user.oc-static.com/upload/2020/08/24/1598262857804_Maquette%20reservia-min.png "Reservia").

## Éléments fourni par OpenClassRooms

-   Maquette aux format Desktop et Smartphone (Iphone8).
-   Images aux formats small, medium, large
-   Les couleurs de bases sont : bleu #0065FC - bleu clair #DEEBFF - gris #F2F2F2
-   Police de caractère ["Raleway"](https://fonts.google.com/specimen/Raleway "Police raleway")
-   Les icônes proviennent du site ["Font Awesome"](https://fontawesome.com/ "Font awesome")

## Instructions

-   L'intégration doit ce faire sans framework
-   Séparation des finhirs HTML et CSS
-   Utilisation de balises sémantiques
-   Les filtres, bien que non fonctionnels, doivent changer de style au survol.
-   Chaque carte d’hébergement ou d’activité devra être cliquable dans son intégralité. Pour l’instant les liens seront vides.
-   Dans le menu, les liens “Hébergements” et “Activités” sont des ancres qui doivent mener aux sections de la page.
-   le site ne doit contenir aucune erreur au validateur [W3C](https://validator.w3.org/#validate_by_upload) (html et css)
-   Même si aucune maquette n'est fournie pour les tablettes, l'intégration doit le prendre en charge
-   Le code doit être versionné avec git et doit avoir un repo distant sur Github ou Gitlab
-   le site doit êtres hébérger sur GitPages.
-   Le site devra être compatible avec les dernières versions de Chrome et Firefox.

## Notes sur le projet

-   Le site à été réalisé en utilisant VS code.
-   Les styles on été "découpé" en morceau afin de faciliter le travail sur les différentes parties du site, puis recompilé. Voir le répertoire css/découpage.
-   Des repères, comme ceux présent dans photshop m'on permis d'aligner correctement les éléments comme sur la maquette (Voir de le CSS body::after et body::before). Je pense d'ailleurs améliorer le concept avec JS afin d'obtenir un véritable outil développement pour les dévelopeurs front-end.
-   Il fut très difficile de reproduire avec exactitude la maquette en ayant pour matériaux de base une image PNG et non un fichier PSD.

## liens d'ébergements

-   Projet Reservia réalisé par Raphaël Parodi et hébergé sur [GitPages]( https://raficraft.github.io/reservia/)