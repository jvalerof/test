# Markdown Generalities
Web page with many examples of how to create a good Markdown:
https://pandao.github.io/editor.md/en.html


## Including an video
First to include the image url and next the video url:

<script src="https://gist.github.com/jvalerof/a81ef45737b915d9e681d00bfdc22763.js"></script>
[![Watch the video](https://img.youtube.com/vi/T-D1KVIuvjA/maxresdefault.jpg)](https://youtu.be/T-D1KVIuvjA)


# Justify Text
<div class=text-justify>
Aqui se escribe el texto que sera justificado. Los siguientes caracteres son de ejemplo. kkkkkkkkkkkkkkkkkkkkkkkkkkkkkkkkkkkkkkkkkkkkkkkkkkkkkkkkkkkkkkkkkkkkkkkkkkkkkkkkkkkkkkkkkkkkkkkkkkkkkkkkkkkkkkkkkkkkkkkkkkkkkkkkkkkkkkkkkkkkkkkkkkkkkkkkkkkkkkkkkkkkkkkkkkkkkkkkkkkkkkkkkkkkkkkkkkkk. 
 </div> 

# Including tables

Tables should have the next style:

| First Header  | Second Header |
| ------------- | ------------- |
| Content Cell  | Content Cell  |
| Content Cell  | Content Cell  |

To create this style automatically, it is recomended to use:
1. Vistit the web page: https://ozh.github.io/ascii-tables/
2. In input space paste the csv content.
3. The web page setings should be:
- Header Location: First Row.
- Auto-Format: ok.
- Output Style: Github Markdown.
- Custom Separator: ,
- Comment Style: "" (No comment style applied)

4. The output will be paste like next:



| District | CVPM |                   AGENCYNAME                    |
|----------|------|-------------------------------------------------|
| D02      | 21A  | Kern Delta Water District                       |
| D03      | 21C  | Wheeler Ridge - Maricopa Water Storage District |
| D04      | 19A  | West Kern Water District                        |
| D01      | 19A  | Belridge Water Storage District                 |
| D05      | 19A  | Berrenda Mesa Water District                    |
| D06      | 19B  | Semitropic Water Service District               |
| D07      | 21A  | Rosedale - Rio Bravo Water Storage District     |
| D08      | 19B  | Buena Vista Water Storage District              |
| D09      | 20   | Cawelo Water District                           |
| D10      | 21A  | Henry Miller Water District                     |
| D11      | 19A  | Lost Hills Water District                       |
| fk13     | 18   | Tulare Irrigation District                      |
| fk08     | 18   | Saucelito Irrigation District                   |
| fk01     | 18   | Delano - Earlimart Irrigation District          |
| fk06     | 18   | Lower Tule River Irrigation District            |
| fk03     | 20   | Kern - Tulare Water District                    |
| fk05     | 18   | Lindsay - Strathmore Irrigation District        |
| fk02     | 18   | Exeter Irrigation District                      |
| fk04     | 18   | Lindmore Irrigation District                    |
| fk07     | 18   | Porterville Irrigation District                 |
| fk11     | 18   | Tea Pot Dome Water District                     |
| fk14     | 18   | Vandalia Irrigation District                    |
| fk12     | 18   | Terra Bella Irrigation District                 |
| fk10     | 20   | Southern San Joaquin Municipal Utility District |
| fk09     | 20   | Shafter - Wasco Irrigation District             |
| ot2      | 20   | North Kern Water Storage District               |
| ot3      | 20   | Olcese Water District                           |
| ot1      | 15B  | Dudley Ridge Water District                     |


