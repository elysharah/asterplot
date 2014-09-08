This aster plot displays pie slices as lengths extending outward to the edge (0 at inner to 100 at outer). Widths of the pie slices represent the weight of each pie, which gets used to arrive at a weighted mean of the length scores in the center.

## Contributors

**Jim Regetz** [@regetz](https://github.com/regetz) developed the initial aster plot function in R (see [aster-plot](https://github.com/regetz/aster-plot) on github)

**Parker Abercrombie** [@parkerabercrombie](https://github.com/parkerabercrombie) developed the initial D3 prototype varying  3 of the 4 arc elements starting with Mike Bostock's [Donut Chart](http://bl.ocks.org/mbostock/3887193):

- outerRadius
- startAngle
- endAngle

This is the only example pie chart I've encountered on the web (after much searching) which varied individual arc segments by all 3 (usually just startAngle and endAngle with fixed innerRadius and outerRadius, even if done with multiple rows as with the very cool [Zoomable Sunburst](http://bl.ocks.org/mbostock/4348373)). The outline of the pie chart is generated in addition to the outerRadius-varying segments. For more details, see the [d3 Pie Layout](https://github.com/mbostock/d3/wiki/Pie-Layout#_pie) documentation.

Tooltips on hover are rendered via the [d3-tip library](https://github.com/caged/d3-tip).

This effort was made possible through the [NCEAS Open Science CodeFest](http://nceas.github.io/open-science-codefest/) Sep 2-4, 2014 in Santa Barbara, CA.

**Ben Best** [@bbest](https://github.com/bbest) adapted Parker's prototype to CSV data from the [Ocean Health Index](http://ohi-science.org). For more details on the data prep, see [ohi-aster](github.com/bbest/ohi-aster) on github.