# fantasy-maps
License: Creative Commons Attribution-NonCommercial 4.0 International Public License.

Kepler.gl exercise: Combine a fantasy map with a georeferenced dataset
1. Launch Kepler.gl (https://kepler.gl/).
2. Add the sample data (FantasyWorld.csv) via Add Data To Map (the CSV file was generated using Jan and Llama 3.2 3B Instruct Q8).
3. In Layers, click on Layer settings
  - In Fill Color, select the data field Event.
  - Increase the Radius (e.g., around 45).
  - Select the Field LocationName as a label to be displayed on the map.
4. Click on the Base map (top-right option) to add the map style file (the map was generated using Chat-GPT4o)
  - From Map Style, select No Basemap.
  - Click on the button Add Map Style.
  - In the field 1. Paste style url, copy-paste the link:
    https://raw.githubusercontent.com/florentina-a/fantasy-maps/refs/heads/main/mapstyle.json
  - Click Add Style.
5. From the right side panel, select Show legend.
6. To share/export the map, click on Share from the top-left panel. 
