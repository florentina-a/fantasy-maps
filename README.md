# fantasy-maps
AI-generated fantasy maps.

License: Creative Commons Attribution-NonCommercial 4.0 International Public License.

Kepler.gl exercise: Combine a fantasy map with a georeferenced dataset
1. Launch Kepler.gl (https://kepler.gl/).
2. Add the sample data (FantasyWorld.csv, generated using Jan and Llama 3.2 3B Instruct Q8) via Add Data To Map.
3. In Layers, click on Layer settings
  - In Fill Color, select the data field Event.
  - Increase the Radius to around 45.
  - Select the Field, LocationName as a label to be displayed on the map.
4. Click on the Base map (top-right option) to add the map style file (the map was generated using Chat-GPT4o)
  - From Map Style, select No Basemap.
  - Click on the button Add Map Style.
  - In the fields 1. Paste style url, copy-paste the link to the .json style file:
    https://raw.githubusercontent.com/florentina-a/fantasy-maps/refs/heads/main/mapstyle.json
  - Click Add Style.
