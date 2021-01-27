# Spatial-interaction-of-tumor-immune-cells.
Uses Bivariate analysis inside ArcGis to explore how tumor and immune cells interact.

<h4> Problem Statement</h4>
◦ Ongoing research to identify spatial relationship between immune and tumor cells. Uncovers interaction using Local Bivariate algorithm across independent Gaussian Kernel density functions.

<h4> Methodology </h4>
1. Execute Script kernel density function to generate estimation for kernel functions for each tumor and immune cells. <br /> 
2. Perform local bivariate analysis to infer relationship between tumor density function and immune density at each point in the grid. <br />
3. Aggregate results using summarizer which then informs what regions of the current image exhibit positive relation, what regions have negaitve relation and so on.  <br />


