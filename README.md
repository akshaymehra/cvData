# cvData
Using JSON to populate a CV and website
See http://akshaymehra.com/posts/CVFromJSON/ for a writeup.

This repository only has three files:

1. `cv.json`: the JSON file that contains data from my CV
2. `cv/single.html`: a Hugo file that parses the data in cv.json for display at https://akshaymehra.com/cv
3. `mehra_cv.tex`: a LuaTeX file that produces a .pdf version of the data in cv.json. Note that you will need to compile using `luatex`!
