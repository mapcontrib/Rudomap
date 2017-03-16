# Comment décrire les équipements liés aux déchets dans OSM
## Les équipements publics
### Poubelle publique -> [Wiki OSM](http://wiki.openstreetmap.org/wiki/FR:Tag:amenity%3Dwaste_basket)

*La poubelle classique que l'on trouve fréquemment dans l'espace public, aux arrêts de bus, ...*

![Poubelle publique](http://wiki.openstreetmap.org/w/images/thumb/2/22/M%C3%BClleimer_%C3%96PNV.JPG/200px-M%C3%BClleimer_%C3%96PNV.JPG)

#### Tags
- > amenity=waste_basket

### Containers déchets ménagers -> [Wiki OSM](http://wiki.openstreetmap.org/wiki/FR:Tag:amenity%3Dwaste_disposal)

*Principalement en milieu rural, ces containers regroupent un hameau, plusieurs maisons.*

![Container collectif d'apport de poubelles ménagères](http://wiki.openstreetmap.org/w/images/thumb/6/6b/Waste_container.jpg/200px-Waste_container.jpg)

#### Tags
- > amenity=waste_disposal
- > waste=trash
    
### Container à verre -> [Wiki OSM](http://wiki.openstreetmap.org/wiki/FR:Tag:amenity%3Drecycling)

*Tous les verres ayant eu un usage alimentaire peuvent être mis dans ces containers.*

![Container à verre](https://upload.wikimedia.org/wikipedia/commons/thumb/2/22/Glass_salvage_container_in_Paris%2C_April_2011.jpg/640px-Glass_salvage_container_in_Paris%2C_April_2011.jpg)

#### Tags
- > amenity=recycling
- > recycling_type=container
- > recycling:glass_bottles=yes
- > operator=

### Container à vêtements -> [Wiki OSM](http://wiki.openstreetmap.org/wiki/FR:Tag:amenity%3Drecycling)

*Gérés par de nombreux opérateurs différents, dépendants du territoire (associations, syndicats mixtes, ...).*

![container à vêtements](https://upload.wikimedia.org/wikipedia/commons/thumb/4/46/Cabine_Oxfam.JPG/360px-Cabine_Oxfam.JPG)

#### Tags
- > amenity=recycling
- > recycling_type=container
- > recycling_clothes=yes
- > operator=

### Compostage collectif -> [Wiki OSM](http://wiki.openstreetmap.org/wiki/FR:Tag:amenity%3Drecycling)

*Au pied d'immeuble collectif, dans des espaces publics, dans des parcs et jardins, ces composteurs collectifs permettent de transformer les déchets organiques en compost.*
![container à déchets organiques](https://upload.wikimedia.org/wikipedia/commons/thumb/f/f6/Pavillon_compostage_Montreuil_2011.jpg/320px-Pavillon_compostage_Montreuil_2011.jpg?uselang=fr)

#### Tags
- > amenity=recycling
- > recycling_type=container
- > recycling:organic=yes
- > operator=

### Piles et batteries -> [Wiki OSM](http://wiki.openstreetmap.org/wiki/FR:Tag:amenity%3Drecycling)

*Ce type de container se trouve dans les déchèteries mais également de plus en plus souvent dans des centres commerciaux et grandes surfaces, ...*

![container à piles et batteries]()

#### Tags
- > amenity=recycling
- > recycling_type=container
- > recycling:batteries=yes
- > operator=

### Container pour le plastique -> [Wiki OSM](http://wiki.openstreetmap.org/wiki/FR:Tag:amenity%3Drecycling)

*Récupération des plastiques (emballages, bouteilles, ...) à des fins de recyclages.*

![container à plastique]()

#### Tags
- > amenity=recycling
- > recycling_type=container
- > recycling:plastic=yes
- > recycling:plastic_bottles=yes
- > recycling:plastic_bags=yes
- > recycling:plastic_packaging=yes
- > operator=

### Container pour le métal -> [Wiki OSM](http://wiki.openstreetmap.org/wiki/FR:Tag:amenity%3Drecycling)

*Récupération des métaux (canettes, ...) à des fins de recyclages.*

![container à métaux]()

#### Tags
- > amenity=recycling
- > recycling_type=container
- > recycling:cans=yes
- > operator=

### Container pour les bouchons plastiques -> [Wiki OSM](http://wiki.openstreetmap.org/wiki/FR:Tag:amenity%3Drecycling)
*Ces containers sont souvent associés à des structures, permettant à ces dernières de récupérer des financements en contrepartie de ces collectes.*

![container pour les bouchons plastiques]()

#### Tags
- > amenity=recycling
- > recycling_type=container
- > recyclin:plastic_caps=yes
- > operator=

### Déchèteries -> [Wiki OSM](http://wiki.openstreetmap.org/wiki/FR:Tag:amenity%3Drecycling)

*En charge de la récupération des déchets recyclables (cartons, papiers, métaux, bois, déchets verts, ...) et des déchets plus spécifiques (gravats, piles, solvants, D2E, ...).*

![Déchèteries](http://wiki.openstreetmap.org/w/images/c/c2/WertstoffhofWeitnau.jpg)

#### Tags
- > amenity=recycling
- > recycling_type=centre
- > Types de matériaux recyclés -> [Wiki OSM](http://wiki.openstreetmap.org/wiki/FR:Tag:amenity%3Drecycling#Mat.C3.A9riaux)
- > operator=
- > opening_hours=*
- > description = réservé aux professionnels (dans certains cas)

### station pour camping car ->[Wiki OSM](http://wiki.openstreetmap.org/wiki/FR:Tag:amenity%3Dwaste_disposal)
*En particulier dans les zones touristiques, ces stations pour camping-car permettent à ces derniers de se débarrasser des divers déchets accumulés (eaux grises, wc chimiques, ordures ménagères, ...).*

![Station pour camping car](http://wiki.openstreetmap.org/w/images/b/b0/Fr-CE24-Station_vidange_caravanes.gif)

#### Tags
- > amenity=waste_disposal
- > waste_disposal:grey_water=Yes/No (eaux grises : vaisselle, douche)
- >> waste_disposal:chemical_toilet = Yes / No
- > waste_disposal:trash=Yes/No
- > fee=Yes/no/x€ (payant ou non, prix) 

## le traitement des déchets

### Centre de tri ->[Wiki OSM](http://wiki.openstreetmap.org/wiki/Tag:amenity%3Dwaste_transfer_station)
*Les différents types de déchets sont triés puis transférés vers les filières adéquates (en passant potentiellement par un centre de transfert).*
#### Tags
- > amenity=recycling
- > recycling_type=centre
- > access=private
- > operator=*

### Centre de transfert
*Des camions amènent des déchets pour les regrouper et les amener par "poids lourds" aux filières appropriées.*
#### Tags
- > amenity=waste_transfer_station
- > access=private
- > operator=*

### Décharge, centre d'enfouissement, ... ->[Wiki OSM](http://wiki.openstreetmap.org/wiki/Tag:landuse%3Dlandfill)
*L'enfouissement pour les déchets dits "ultimes".*

![Décharge](https://upload.wikimedia.org/wikipedia/commons/a/ac/Landfill_Hawaii.jpg)

#### Tags
- > landuse=landfill
- > operator=*

### Incinérateur de déchets ->[Wiki OSM](http://wiki.openstreetmap.org/wiki/FR:Key:generator:source)
*Brûler les déchets permet de réduire la quantité et va permettre de chauffer.*
#### Tags
- > power=generator
- > generator:source=waste


### Centre de compostage
*En charge d'assurer le compostage des déchets verts, ces centres de compostage revendent ou redistribuent également souvent des terres paysagères et/ou des composts.*

![Plate-forme de compostage](https://upload.wikimedia.org/wikipedia/commons/thumb/6/67/Tas_de_compost%2C_sur_une_plateforme_de_compostage..JPG/320px-Tas_de_compost%2C_sur_une_plateforme_de_compostage..JPG?uselang=fr)

#### Tags
- > amenity=recycling
- > recycling_type=centre
- > recycling:organic=yes
- > recycling:green_waste=yes
- > recycling:garden_waste=yes
- > operator=*

## Ressourceries, recycleries
dont les ateliers vélos, les spécialistes bois et meubles, ...

#### Tags
- > amenity=recycling
- > amenity_type= centre
- > shop=second_hand

atelier de réparation vélo : recycling:bicycles=yes


## Quelques tags supplémentaires
- > containers enfouis : location=underground

