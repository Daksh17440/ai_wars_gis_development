PROMPT given:

I am making a linkedin post on comparison of Gemini pro and Chatgpt go and claude in gis development. 
This same prompt is given to all 3. We have to create a python notebook for collab that follows the stated path: 
1) take input of a city/stat/nation and use geopy(nominatim) to verify it, and store the string. 
2) using osmnx download and save 2 vector files as geodataframes, 1st the boundary of location and 2nd the sports infrastructure (found at "boundary":"administrative" and "sport":True) 
3) be sure to convert and download all files in mercator epsg32643 
4) rasterize the sports infra vector 
5) build a heatmap of the location for sports infra raster, decide the spread extent and conventions urself 
6) use geemap to import GHSL population data for the location ("JRC/GHSL/P2023A/GHS_POP") 
7) style a new raster zoning the location into 5 zones depending on sports infra/population ratio 
8) directly download the boundary, sports infra(vectors), and GHSL population and resultant map(raster) 
The whole code is to be made in 1 go and comparison will be made on basis of the efforts made in debugging.
