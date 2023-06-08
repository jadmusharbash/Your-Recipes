![readme](https://github.com/jadmusharbash/Your-Recipes/assets/123292194/5f00087b-3177-4628-8fdc-e6ea9e4b1e80)
The primary function in charge of turning on and off the visibility of recipe components is toggleRecipe. It accepts a parameter called recipeId that enables dynamic control of various recipe components. Using various DOM modification techniques, the recipe, img, and desc variables are used to store references to the text, image, and recipe elements, respectively. The function checks the current display state by gaining access to the style property of the picture and text elements, and then uses conditional expressions to apply modifications as necessary. This makes it possible for the image and text to behave like an accordion, revealing or hiding them depending on their current visibility.
