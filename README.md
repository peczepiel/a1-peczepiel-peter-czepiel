A1 - Peter Czepiel
===

Overall Description
---

For my version of A1, I chose to make a picture of a little triangle person (slightly resembling Bill Cipher from Gravity Falls) holding a blue sign that reads *"Hello World!"* as the assignment is named. I did this by incorporating the following D3 append tags in my SVG:
- "rect": rectangle housing the text, along with both feet
- "text": text reading *"Hello World!"*
- "circle": circles for the eyeball and iris
- "line": lines for the border of the triangle
- "polygon": two trapezoids adjacent to the textbox
- "path": both arms and legs, along with the triangles with cutouts to fit the eye

Along with these functional features, I made sure to use a variety of colors, these being:
- "gold": main triangles and arms
- "lightblue": textbox rectangle
- "navy": textbox trapezoids
- "black": legs, feet, and iris
- "white": eyeball
- "lightgrey": page background


Technical Achievements:
---

To go beyond what the assignment was asking, I did a few things on the technical side to ease viewing. For example, when first creating my drawing the shapes were much too larger causing the user to have to scroll or zoom out. I fixed this by using SVG transformations to scale all parts of the SVG down by 55% (scale()) and moved the entire drawing to the center of the page (translate()). I also experimented with ways to make text more readable. I did this by adding attribute tags like "font-size", "font-weight", and "text-anchor" to my textbox.


Design Achievements:
---

On the design side of things, I chose to make a more cohesive drawing rather than just pasting shapes randomly on the screen. I also added a "<style>" tag to the top of my html file so that I could improve the viewer experience. This allowed me to make the page unscrollable, remove the scrollbars entirely, and set the background color to a neutral light grey. I also made my main SVG conform to the size of the users whole page so that nothing is fixed. I did this by using the window.innerWidth and window.innerHeight variables. Lastly, I experiments with making paths that bend and curve in interesting directions rather than straight paths. This can be seen in the legs of the triangle person.


Links and Screenshot
---

Here is a working link to my gh-pages site:
[https://peczepiel.github.io/a1-ghd3-peczepiel/](https://peczepiel.github.io/a1-ghd3-peczepiel/)

Some links I used to help me with the design process are:
- [https://www.w3schools.com/graphics/svg_transformations.asp](https://www.w3schools.com/graphics/svg_transformations.asp) (information about SVG Transformations)
- [https://d3-graph-gallery.com/graph/shape.html#mytext](https://d3-graph-gallery.com/graph/shape.html#mytext) (basic information about how to make SVG shapes using D3)
- [https://jonathansoma.com/lede/storytelling/d3/text-elements/](https://jonathansoma.com/lede/storytelling/d3/text-elements/) (information about text styling in D3)

Here is a screenshot of the final product:
![Final Screenshot](image.png)
