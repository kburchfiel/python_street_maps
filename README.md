# Charlottesville Street Map Creator

By Kenneth Burchfiel

*(More documentation to come!)*

This Python script shows how to use the Plotly and fpdf libraries to (1) create a series of Charlottesville maps, then (2) save these maps to a PDF file. You are welcome to adapt the script to create maps of other cities.

The script generates these maps using a for loop that shifts central map coordinates east and south over a specified distance. This approach creates 64 separate maps that, together, encompass much of Charlottesville.

This code also utilizes the Pillow library to create 'overview' maps that combine 16 to 64 of these maps into single images, thus making it easier to locate a map of interest. (The map codes displayed within these overview maps correspond to codes on the bottom left of each individual map in the PDF.)

Although the Python *code* is released under the MIT license, the maps themselves contain OpenStreetMap data and are thus available under the Open Database License. See openstreetmap.org/copyright for more details.

## Sample maps


