## Matplotlib_1:

* defining x & y axis
* Line graph:
    * label & legend()
    * xlabel, ylabel, title
    * colors
    * marker, marker size, marker edge color, marker face color
    * linestyle, linewidth
* Bar graph:
    * overlapping
    * bar-width
    * horizontal bar
* multiple graphs in the same figure
* multiple graphs for same values
* Histogram:
    * bins
    * cumulative

## Matplotlib_2:

* Scatter plot
* Stackplot:
    * x-axis is 1 value
    * y-axis is more than 1 values
* Subplot:
    * position:  total rows, total columns, position of the cell.
    * tight_layout()
* Subplot2grid:
    * matrix size (3,4), starting point (0,0), rowspan = 1, colspan = 3.
* 3-D: scatter
    * 3-values (x,y,z)
    * in case of subplot----position(111)
    * figsize(width,height)
    * dpi: pixels
* 3-D: bar
    * 6-values (3 for axis, 3 for thickness)
    * 1 plane must be zero, for the graph to be grounded
    * multiple bars in the same figure

## seaborn_1

- Scatterplot
- Countplot
- Hue (color)
    - without order, with order
    - changing colors
- Relational plots & subplots:
    - relplot()
    - column-wise, row-wise, both
    - wraping columns
    - point size
    - point transparency

## seaborn_2

- Line plot:
    - using relplot()
- multiple observations per x-value:
    - using relplot()
    - kind = "scatter", "line"
    - confidence interval (ci):
        - shaded region : indicates uncertainity
- Categorical plot:
    - catplot()
    - kind = "count", "bar" 
    - horizontal bar: by interchanging x & y values
    - Box plot:
        - to see median, spread, skewness, outliers
        - used in time_series data
    - Point plot:
        - import median
- changing color palette:
    - sequential palette
    - custom palette
    - changing the size
