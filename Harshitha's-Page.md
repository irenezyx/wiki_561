
# Koch snowflake

Koch Snowflake is a special [Fractal](https://en.wikipedia.org/wiki/Fractal).

[Niels Fabian Helge von Koch](https://en.wikipedia.org/wiki/Helge_von_Koch), a swedish noble gave his name to one of the early fractal curves to be described - [Koch snowflake](https://en.wikipedia.org/wiki/Koch_snowflake)
It is based on a paper titled "On a continuous curve without tangents, constructible from elementary geometry".

> Koch snowflake can be constructed as shown in the diagram below - Only 3 steps are shown
* Start with an equilateral triangle
* Divide each side into 3 parts
* construct equilateral triangles in the middle parts
* Repeat the above step recursively

This can result in a curve that looks continuous in a zoomed out view but can be broken into discrete fractals when zoomed in



![Fractal Image](Harshitha-koch_iteration.svg)


# Dimension 
h<sub>&theta;</sub>(x) = &theta;<sub>o</sub> x + &theta;<sub>1</sub>x

With every iteration, the number of sides of the Koch snowflake increases by a factor of 4, therefore the number of sides after k iterations is given by:

N<sub>k</sub> = 3 x 4<sup>n</sup>


If the original equilateral triangle has sides of length s, the length of each side of the snowflake after n iterations is:

S<sub>k</sub> = s/3<sup>n</sup>


[Animated illustration](https://en.wikipedia.org/wiki/Koch_snowflake#/media/File:Kochsim.gif)

## Reference: 

1. [Wikipedia](https://en.wikipedia.org/wiki/Koch_snowflake)
2. [Equation Markdown](https://stackoverflow.com/questions/11256433/how-to-show-math-equations-in-general-githubs-markdownnot-githubs-blog)

