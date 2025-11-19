# Polimi - Auriga Beamer Template
## Brief Description 
The base theme is [Auriga](https://markdownlivepreview.com/). The changes applied allow for an out of the box polimi look.
### Logos
There are in total 4 logos included by default in the presentation:
- `titlelogoA`: this goes only in the title page 
- `titlelogoB`: //
- `logoA`: this goes in the regular slides
- `logoB`:  // 
<br>
By default, the title logos are aligned at center of the bottom of the title slide. If only `logoA` is provided, the logo in the regular slides will be aligned at the bottom right. If both `logoA` and `logoB` are provided, then they will be aligned at the bottom-center of the slides.

### Colors
Usually, official Polimi templates use a very debatable light blue, which can be employed setting `\selectcolor{polimiBlue}`. Otherwise, a deeper, much more pleasant blue is available by using `\selectcolor{deepPolimiBlue}`.

## Dependencies
Being based on [Auriga](https://markdownlivepreview.com/), the theme needs:
- A TeX installation that includes LuaTeX
- LaTeX package dependencies including beamer (these usually come with your TeX installation, but if not, you can get them from CTAN)
- Raleway, Lato, and Hack, which are all available under Open Font License
