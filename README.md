# cvData
Using JSON to populate a CV and website
See http://akshaymehra.com/posts/CVFromJSON/ for a writeup.

This repository only has three files:

`cv.json`: the JSON file that contains data from my CV
`cv/single.html`: a Hugo file that parses the data in cv.json for display at https://akshaymehra.com/cv
`mehra_cv.tex`: a LuaTeX file that produces a .pdf version of the data in cv.json. Note that you will need to compile using `luatex`!
