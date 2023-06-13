# RStudio Theme: "Inspired" by Atom's One Dark

![Image of theme as applied to source code for R's lm() function](atom-inspired.png)


You can try out this theme by running the following in R:

```{r}
url <- "https://github.com/dyavorsky/atom-inspired/blob/main/atom_inspired.rstheme"
rstudioapi::addTheme(url, apply = TRUE, force = TRUE)
```

This will appear in *Tools \> Global Options \> Appearance \> Editor Theme* as **One Dark {Inspired}**

If you have issues applying the theme programatically, try this instead:

 - Download the *atom_inspired.rstheme* file from this github repo
 - Go to RStudio's Tools > Global Options > Appearance
 - Under Editor Theme, click "Add"
 - Select the *atom_inspired.rstheme* file from it's location on your machine
 - Click "Apply"

To remove this theme, go to RStudio's Tools > Global Options > Appearance and click "Remove" or simply run

```{r}
rstudioapi::removeTheme("One Dark {Inspired}")
```

More information on custom RStudio themes can be found here:

-   Posit's article "Using Themes in the RStudio IDE" [[link](https://support.posit.co/hc/en-us/articles/115011846747-Using-Themes-in-the-RStudio-IDE)]
-   RStudio Extensions website for "Creating Custom Themes for RStudio" [[link](https://rstudio.github.io/rstudio-extensions/rstudio-theme-creation.html)]
-   tkrable's GitHub repo for One Dark [[link](https://github.com/tkrabel/rstudio_atom_theme)]


If you like the dark RStudio theme (not the editor theme), check out [darkstudio](https://github.com/rileytwo/darkstudio)
