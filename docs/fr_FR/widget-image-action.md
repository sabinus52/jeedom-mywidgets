# Widget "Image_Action"

Widget pour Jeedom permettant d’afficher image de type **action**.

![](../images/widget-image-action.png)


## Paramétrage

### Paramétrage du widget

Paramètres à ajouter dans ***Paramètres optionnels widget***

![](../images/param-widget.png)


#### Possiblité de choisir l'image suivant :

Nom du paramètre | Valeur par défaut    | Valeurs possibles                                | Description
---------------- | -------------------- | ------------------------------------------------ | -----------
**logo**         | defaut               | Choix du nom de l'image dans le dossier `action` | Nom du logo


#### Possiblité de configurer l'affichage du widget avec les paramètres optionnels suivants :

Nom du paramètre     | Valeur par défaut | Valeurs possibles | Dashboard | Mobile | Description
-------------------- | ----------------- | ----------------- | --------- | ------ | -----------
**size**             | 80                | [0-9]+            | Oui       | Oui    | Dimension de l'image en pixels.
**size_dashboard**   | *size*            | [0-9]+            | Oui       | Nom    | Dimension de l'image en pixels en version dashboard
**size_mobile**      | *size*            | [0-9]+            | Non       | Oui    | Dimension de l'image en pixels en version mobile
**style**            |                   | code css          | Oui       | Oui    | Style CSS du widget.
**style_dashboard**  | *style*           | code css          | Oui       | Non    | Style CSS du widget en version dashboard
**style_mobile**     | *style*           | code css          | Non       | Oui    | Style CSS du widget en version mobile
