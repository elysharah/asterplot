This aster plot displays pie slices as lengths extending outward to the edge (0 at inner to 100 at outer). Widths of the pie slices represent the weight of each pie, which gets used to arrive at a weighted mean of the length scores in the center.

## Contributors

**Jim Regetz** [@regetz](https://github.com/regetz) developed the initial aster plot function in R (see [aster-plot](https://github.com/regetz/aster-plot) on github)

**Parker Abercrombie** [@parkerabercrombie](https://github.com/parkerabercrombie) developed the initial prototype varying all 3 of the 4 arc elements using Mike Bostock's [Donut Chart](http://bl.ocks.org/mbostock/3887193):

- outerRadius
- startAngle
- endAngle

For more details, see the [d3 Pie Layout](https://github.com/mbostock/d3/wiki/Pie-Layout#_pie) documentation.

**Ben Best** [@bbest](https://github.com/bbest) adapted this prototype to data from the Ocean Health Index. For more details on the data prep, see [ohi-aster](github.com/bbest/ohi-aster) on github.