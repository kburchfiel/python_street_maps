# Python Street Map Creator

By Kenneth Burchfiel

*(More documentation to come!)*

This Python script shows how to use the Plotly and fpdf libraries to (1) create a series of maps of Charlottesville, Virginia, then (2) save these maps to [a PDF file](https://github.com/kburchfiel/python_street_maps/blob/main/cville_map_book.pdf). You are welcome to adapt the script to create maps of other cities.

The script generates these maps using a for loop that shifts central map coordinates east and south over a specified distance. This approach creates 64 separate maps that, together, encompass much of Charlottesville.

This code also utilizes the Pillow library to create 'overview' maps that combine 16 to 64 of these maps into single images, thus making it easier to locate a map of interest. (The map codes displayed within these overview maps correspond to codes on the bottom left of each individual map in the PDF.)

Although the Python *code* is released under the MIT license, the maps themselves contain OpenStreetMap data and are thus available under the Open Database License. See openstreetmap.org/copyright for more details.

## Sample maps

### Overview map that shows all 64 tiled maps

(This image serves as a visual table of contents for the PDF-based mapbook.)

<img src='https://raw.githubusercontent.com/kburchfiel/python_street_maps/refs/heads/main/maps/combined_map_smaller.png' width="500"/>

### Maps that show quadrants of this overview map

Top-right quadrant:

<img src='https://raw.githubusercontent.com/kburchfiel/python_street_maps/refs/heads/main/maps/combined_map_subset_1_smaller.png' width="500"/>

Bottom-right quadrant:

<img src='https://raw.githubusercontent.com/kburchfiel/python_street_maps/refs/heads/main/maps/combined_map_subset_3_smaller.png' width="500"/>


### Individual tiled maps

The map numbers and codes found within the overview maps above are located near the bottom left of these maps.

<img src='https://raw.githubusercontent.com/kburchfiel/python_street_maps/refs/heads/main/maps/tiled/cville_tiled_map_03_03.png' width = "500"/>

<img src='https://raw.githubusercontent.com/kburchfiel/python_street_maps/refs/heads/main/maps/tiled/cville_tiled_map_04_03.png' width = "500"/>

<img src='https://raw.githubusercontent.com/kburchfiel/python_street_maps/refs/heads/main/maps/tiled/cville_tiled_map_04_04.png' width = "500"/>

<img src='https://raw.githubusercontent.com/kburchfiel/python_street_maps/refs/heads/main/maps/tiled/cville_tiled_map_05_04.png' width = "500"/>





