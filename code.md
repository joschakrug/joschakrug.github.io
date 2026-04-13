---
layout: page
title: Code & data
permalink: /code/
---

I work with a wide range of technologies in my research. My particular expertise is in R, Julia and Stata, although I have some experience with Python as well and will write an optimised C/C++ routine for some computationally intensive bits when push comes to shove.

I am a great advocate of open source software and try to make the source code I produce in the context of my research openly available whenever I think it might be of use to others as well.

## R and Julia packages

- **[chunkwise](https://github.com/joschakrug/chunkwise):** An R package that contains an optimised C++ routine to read and process large text files in chunks. (This comes in useful when you have to deal with a huge `.csv` file of several GB on your mid-tier work notebook, for example.)
- **[GriddedFunctions.jl](https://github.com/joschakrug/GriddedFunctions.jl):** A Julia package that provides efficient and easy-to-use tools to work with functions that can only be represented as an approximation over a grid. (Crucial, for example, for value function iteration.)

## Data sets

- **[plz-ags-matching](https://github.com/joschakrug/plz-ags-matching):** A data set that contains a shape file of the boundaries of all PLZ-AGS (postal code--municipality) combinations in Germany and a correspondence between PLZ and AGS identifiers, based on openly available data.
