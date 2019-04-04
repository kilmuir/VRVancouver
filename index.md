## GEOB 472 Mapping with WebVR Assignment:
## Vertical Growth: Vancouver's Changing Cityscape

Author: Alec Francis

For this assignment, I was interested in showing changes to the urban landscape and built environment through the medium of virtual reality. originally, I created a 3D map of the entire downtown peninsula and the changes in buildings from 1999-2009. This was done in QGIS and ultimately the file size of the exported glb file was so large as to be unwieldy. I thus settled for a focus on the Yaletown area of North False Creek. Yaletown is located on what used to be industrial land but since Expo 86 has seen rapid and extensive development (which is ongoing). Since Vancouver is known for its high rise developments, one of the goals of my visualisation was to see how the heights of the building developments built since 1999 compared to those built before. In the final map, orange buildings are those built after 1999 while blue represents those built before.

The project began with several datasets: 1 meter orthophotos of the Downtown peninsula, a 30m digital elevation model (DEM), and building footprint files of the city's buildings in 1999 and 2009 (which included heights and other data). I then processed these layers in QGIS by clipping and selecting data in order to reduce their extent. Using Qgis2threejs, I set the layers relative to the DEM, and then extruded the two building layers proportional to their maximum height. I exported the output as a glb file, which allowed my to host it in A-Frame.

The idea of 'shifting baselines', popularised by UBC fisheries researcher Daniel Pauly relates to the loss of knowledge between generations, or over time. For example, a person might not notice a gradual decline in bird population over their lifetime, and their children may start at a radically different 'baseline' of fish population than they did - and the lower population just seems normal. This phenomenon can lead to significant problems for those studying populations, or other environmental issues. While the concept is most often used with reference to the natural sciences, I think it could be extended to provide us with some insight on a rapidly changing cityscape. Real estate development has become a primary driver of Vancouver's economy since the city opened itself up to global capital following Expo 86. While people may feel strongly one way or the other about a specific development at the time of construction, it is hard to conceptualise how much or how fast the city has changed. This is especially the case if you are, like me, born since Expo, and thus have no recollection of Vancouver before then.

The idea behind this map was to look critically at the development of False Creek's north bank and to attempt to mitigate the 'intergenerational forgetting' of changes in Vancouver's urban landscape. Since buildings are very three-dimensional structures which are not effectively visualized as footprints on maps, I think that VR is a suitable medium to convey their physical presence. Given the significant constraint of my lack of experience with VR, I concede that the project in its current iteration has a long way to go before it succeeds in becoming a compelling VR experience. I think the basic idea is sound, but a more successful VR experience could be achieved by drafting buildings and other urban features in sketchup to create a more realistic urban environment. New and old buildings at the same location could be superimposed with varying opacity so that both would be visible.

Ulitmately hosting on GitHub proved a bit glitchy - so I've linked a to a version on _Glitch_ instead.
<a href = 'https://stump-shirt.glitch.me/' title = "Vertical Growth"
  target = "_blank"> See here for the final map</a>
  
## Screenshot

<img src = 'https://github.com/kilmuir/VRVancouver/screenshotvr.png'>

