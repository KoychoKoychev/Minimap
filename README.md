# Minimap
Simple application that allows the user to create a minimap from selected set of tiles
## Overview
The map has height and widht that are set from two separete input fields. When the size is changed the map increases/reduces its size on the right and the bottom. The tiles are separated on two groups : Lands and Items. An item tile can only be placed on a field with land tile. Lands and items can be changed once they are placed on the map.
## File system
Once a map is created, it can be saved to a JSON file, that will be downloaded in the default Download directory of your browsed.
The JSON files can be loaded into the application and it will generate the previously created map.
