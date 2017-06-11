

These are scenes, .yaml files used to create maps in [Mapzen's Tangram](https://mapzen.com/products/tangram/). 

I'm using these files to learn Tangram and GLSL.  

I've structured the code in most (but not all of the) files so that they should work (and display a map) if you
copy and paste the code into https://mapzen.com/tangram/play 

Most of the code in here is not written from scratch by me rather I've just adapted code written by Patricio González Vivo of Mapzen, who deserves credit. 

Some of these scenes also include workable examples of shader code that you can insert into a scene with less fuss (hopefully). 

Below are descriptions and direct links to them in Tangram Play as well so you can view and edit them. 

Descriptions:

skim-city: a reimagination in the sim city 2000 aesthetic. designed to be viewed mostly at z15+ zoom level (since that's you'd usually play SC2000 at anyways). Really early stages; [viewable example](https://mapzen.com/tangram/play/?scene=https%3A%2F%2Fraw.githubusercontent.com%2Fskorasaurus%2Fsc3n3%2Fmaster%2Fskim_city.yaml#15.0000/41.5021/-81.6890)


line-dash-example: [viewable example](https://mapzen.com/tangram/play/?scene=https%3A%2F%2Fraw.githubusercontent.com%2Fskorasaurus%2Fsc3n3%2Fmaster%2Fsimpler-line-dash-example.yaml#11.7500/41.4622/-81.7251)
Use dashes for your lines. 
The [block reference](http://tangrams.github.io/blocks/#lines-dash)

lines-chevron-example: example of chevron Lines, [viewable example](https://mapzen.com/tangram/play/?scene=https%3A%2F%2Fmapzen.com%2Fapi%2Fscenes%2F722%2F600%2Fresources%2Flines-chevron-example.yaml#19.00000/38.93663/-79.91654)

lines-outline: [viewable example](https://mapzen.com/tangram/play/?scene=https://raw.githubusercontent.com/skorasaurus/sc3n3/master/lines-outline.yaml#17.50000/41.47735/-81.67940) - 

(need to finish describing the rest of the files)

PS - global.yaml is filed referenced in several of my scenes, used to properly layer features. available at 
https://tangrams.github.io/blocks/global.yaml