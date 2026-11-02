<div align="center">

# Vienne Condrieu Agglomération

**Géomatique, données et outils open source au service d'un territoire de 30 communes**

[🌐 Site officiel](https://www.vienne-condrieu-agglomeration.fr) · [🗂️ Données sur data.gouv.fr](https://www.data.gouv.fr/organizations/vienne-condrieu-agglomeration-1/) · [📽️ Présentations](https://vienne-condrieu-agglomeration.github.io/slideshows/)

</div>

---

## 👋 Qui sommes-nous ?

Vienne Condrieu Agglomération est un EPCI créé le 1er janvier 2018, qui regroupe **30 communes** au sud de Lyon, sur les rives du Rhône.
Ce compte GitHub est animé par le **service SIG et Foncier** : nous y partageons des modules, des données ouvertes, des outils de déploiement et des supports de présentation autour de l'information géographique et de la donnée.

## 🧰 Projets actifs

### 🧩 Bibliothèque participative de modules GEO

Des modules d'extension pour la plateforme GEO, sous licence libre, que chacun peut installer, adapter et améliorer : [🌐 voir le site](https://vienne-condrieu-agglomeration.github.io/geo-modules-community/).
Projets communautaires indépendants, **non affiliés à Business Geografic**.

| Projet | Description | Langage |
|---|---|---|
| **[🌐 geo-modules-community](https://github.com/vienne-condrieu-agglomeration/geo-modules-community)** | Site de la bibliothèque : catalogue des modules, installation, retours d'expérience de développement et contribution | Python, Markdown |
| **🧩 Modules GEO** | Modules d'extension à importer dans le Générateur GEO | |
| &emsp;├ [📸 geo-module-panoramax](https://github.com/vienne-condrieu-agglomeration/geo-module-panoramax) | Vue immersive : affiche les photos à 360° [Panoramax](https://panoramax.fr) dans une application cartographique | JavaScript |
| &emsp;├ [🌳 geo-module-dfi](https://github.com/vienne-condrieu-agglomeration/geo-module-dfi) | Filiation des parcelles (DFI de la DGFiP) : graphe des parcelles mères, des lots et des parcelles filles | JavaScript |
| &emsp;└ [🪟 geo-module-compare-swipe](https://github.com/vienne-condrieu-agglomeration/geo-module-compare-swipe) | Comparateur de rasters (rideau et loupe) directement sur la carte | JavaScript |
| **🗄️ Données et intégrateurs** | Données ouvertes préparées pour les modules, lues par le navigateur (ni serveur ni base de données) | |
| &emsp;├ [⚙️ geo-community-integrator-dfi](https://github.com/vienne-condrieu-agglomeration/geo-community-integrator-dfi) | Intégrateur : télécharge les DFI, les contrôle et les convertit en un fichier JSON par commune | Python |
| &emsp;└ [🗂️ geo-community-data-dfi](https://github.com/vienne-condrieu-agglomeration/geo-community-data-dfi) | Données DFI publiées sur GitHub Pages, régénérées à chaque nouvelle situation de la DGFiP | JSON, GitHub Actions |

### 🛠️ Outils de déploiement et de cartographie

| Projet | Description | Langage |
|---|---|---|
| [🧩 business-geografic-geo-generateur](https://github.com/vienne-condrieu-agglomeration/business-geografic-geo-generateur) | Générateur de configuration pour la plateforme GEO (Business Geografic) | Jinja |
| [🐳 gdal-ecw-docker](https://github.com/vienne-condrieu-agglomeration/gdal-ecw-docker) | Image Docker de GDAL avec prise en charge du format raster ECW | Dockerfile |
| [🐳 geoserver-ecw-docker](https://github.com/vienne-condrieu-agglomeration/geoserver-ecw-docker) | Image Docker de GeoServer avec prise en charge du format raster ECW | Shell |

## 📚 Documentation et présentations

| Dépôt | Description |
|---|---|
| [📖 base-documentaire](https://github.com/vienne-condrieu-agglomeration/base-documentaire) | Information Géographique & Observatoire : documentation |
| [📽️ slideshows](https://github.com/vienne-condrieu-agglomeration/slideshows) | Présentations publiées via GitHub Pages |

### SIG Voisins #04 · 11 avril 2024

- [Diaporama en ligne](https://vienne-condrieu-agglomeration.github.io/slideshows/20240411-sigvoisins/#/)
- [Rencontre SIG Voisins (PDF)](https://github.com/vienne-condrieu-agglomeration/slideshows/blob/fab44787854c06d3fec0cfecb3f038f7bf69a163/20240411-sigvoisins/externe/00_VienneCondrieu-11104024-Rencontre%20SIG%20Voisins.pdf)
- [Présentation LiDAR (PDF)](https://github.com/vienne-condrieu-agglomeration/slideshows/blob/fab44787854c06d3fec0cfecb3f038f7bf69a163/20240411-sigvoisins/externe/01_20240411_Cercle_SIG_voisins_Presentation_LiDAR_v2.pdf)

## 🗄️ Historique

Ces dépôts ne sont plus maintenus et sont conservés pour mémoire.

- **Waze for Cities** : [waze-for-cities-integration](https://github.com/vienne-condrieu-agglomeration/waze-for-cities-integration), scripts d'intégration des données Waze for Cities (2022)
- **Géocodage et SIRENE** : [docker-addok](https://github.com/vienne-condrieu-agglomeration/docker-addok), [sirene](https://github.com/vienne-condrieu-agglomeration/sirene) (2018)
- **geOrchestra (ViennAgglo, 2014-2020)** : [georchestra-docker](https://github.com/vienne-condrieu-agglomeration/georchestra-docker), [georchestra-datadir](https://github.com/vienne-condrieu-agglomeration/georchestra-datadir), [georchestra-config](https://github.com/vienne-condrieu-agglomeration/georchestra-config), [georchestra-doc](https://github.com/vienne-condrieu-agglomeration/georchestra-doc)

## 🤝 Contribuer

Une question, une suggestion, un bug ? Ouvrez une *issue* sur le dépôt concerné.
Pour toute autre demande, rendez-vous sur le [site de l'agglomération](https://www.vienne-condrieu-agglomeration.fr).