# Puy De Dôme [2020]
![image](https://raw.githubusercontent.com/Lombard-Web-Services/cartographie/master/cartographie/puy_de_dome/images/map.png)

Cartographie du département 63 - Puy De Dôme

## Fonctionnalités et contenu
* Carte avec délimitation uniquement, au format GEOJSON compatible Mapbox-Gl-JS
* Ressources format OSM, SVG, GEOJSON
* SVG interactif avec choropleth (TLMAPS)
* Délimitation des SVG avec PETR+CA+CC ou CA+CC

### SVG interactif
Naviguez dans le fichier [js/sampledata.js] pour ajouter le dataset dans l'objet JSON.
```sh
var example_data = { data ....}
```

## Demo délimitations avec Mapbox GL
* Délimitation GEOJSON API maps lombard-web-services [demo-mapbox-gl-js]
* Carte interactive SVG communautés de communes et communautés d'agglomérations [demo-svg-cacc]
* Carte interactive SVG PETR et CA - CC [demo-svg-cacc-petr]

# SVG interactif Choropleth
![image](https://raw.githubusercontent.com/Lombard-Web-Services/cartographie/master/cartographie/puy_de_dome/images/svg_CACCPETR.png)
![image](https://raw.githubusercontent.com/Lombard-Web-Services/cartographie/master/cartographie/puy_de_dome/images/svg_CACC.png)
* Avec affichage par communauté de communes et d'agglomération [demo-svg-cacc]
* Avec affichage par communauté de communes et d'agglomération ainsi que PETR [demo-svg-cacc-petr]

## CACC et PETR
* 2099673 - Clermont Auvergne Métropole
* 6846152 - CA Riom Limagne et Volcans
* 6846149 - CA Agglo Pays d'Issoire
* 6846150 - CC Mond'Arverne Communauté
* 6846153 - CC Thiers Dore et Montagne
* 6846154 - CC Ambert Livradois Forez
* 6846147 - CC Billom Communauté
* 6846155 - CC Plaine Limagne
* 3413115 - CC entre Dore et Allier
* 6846156 - CC Combrailles Sioule et Morge
* 6846157 - CC du Pays de Saint-Éloy
* 6846151 - CC Chavanon Combrailles et Volcans
* 6846148 - CC Dômes Sancy Artense
* 2169016 - CC du Massif du Sancy
* PETR Grand Clermont : 6846147 2099673 6846152 6846150

## Licenses
[GNU-GPL] License
Copyleft - Thibaut LOMBARD


[comment]: #
   [demo-mapbox-gl-js]: <https://lombard-web-services.github.io/cartographie/cartographie/puy_de_dome/maps_petr.html>
   [demo-svg-cacc]: <https://lombard-web-services.github.io/cartographie/cartographie/puy_de_dome/demo_CACC.html>
   [demo-svg-cacc-petr]: <https://lombard-web-services.github.io/cartographie/cartographie/puy_de_dome/demo_CACC_PETR.html>
   [GNU-GPL]: <https://www.gnu.org/licenses/licenses.fr.html>
