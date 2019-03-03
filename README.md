# EMS-Dispatches-Pittsburgh
This repository contains jupyter notebooks which explore [Allegheny County 911 EMS Dispatches data](https://data.wprdc.org/dataset/allegheny-county-911-dispatches-ems-and-fire) using  [Plotly](https://plot.ly/), [seaborn](https://seaborn.pydata.org/) and [Mapbox](https://www.mapbox.com/).

There are four jupyter notebooks:

<ol>
<li> data_preprocessing.ipynb  <a href="https://colab.research.google.com/github/thoo/EMS-Dispatches-Pittsburgh/blob/master/data_preprocessing.ipynb">
  <img src="https://colab.research.google.com/assets/colab-badge.svg" alt="Open In Colab" height="12px"/>
</a> </li>

<li> data_preprocessing-EMS-population.ipynb  <a href="https://colab.research.google.com/github/thoo/EMS-Dispatches-Pittsburgh/blob/master/data_preprocessing-EMS-population.ipynb">
  <img src="https://colab.research.google.com/assets/colab-badge.svg" alt="Open In Colab" height="12px"/>
</a></li>

<li> data-visualization-seaborn.ipynb  <a href="https://colab.research.google.com/github/thoo/EMS-Dispatches-Pittsburgh/blob/master/data-visualization-seaborn.ipynb">
  <img src="https://colab.research.google.com/assets/colab-badge.svg" alt="Open In Colab" height="12px"/>
</a></li>

<li> data-visualization-plotly.ipynb  <a href="https://colab.research.google.com/github/thoo/EMS-Dispatches-Pittsburgh/blob/master/data-visualization-plotly.ipynb">
  <img src="https://colab.research.google.com/assets/colab-badge.svg" alt="Open In Colab" height="12px"/>
</a></li>

<li> plotly_map_plot.ipynb  <a href="https://colab.research.google.com/github/thoo/EMS-Dispatches-Pittsburgh/blob/master/plotly_map_plot.ipynb">
  <img src="https://colab.research.google.com/assets/colab-badge.svg" alt="Open In Colab" height="12px"/>
</a></li>
</ol>

All of these notebooks can be opened and run at Google Colaboratory  <img src="https://colab.research.google.com/assets/colab-badge.svg" alt="Open In Colab" height="18px"/>.

---
## data_preprocessing.ipynb
Clean up the data and fill missing values.

---
## data_preprocessing-EMS-population.ipynb
EMS-dispatches data only contains such as city name and GEOID but does not include the population. Therefore, the population for each sub-counties of Allegheny is extracted from [US Census]('https://www2.census.gov/programs-surveys/popest/datasets/2010-2017/cities/totals/sub-est2017_42.csv').

---

## data-visualization-seaborn.ipynb
This notebook is a walk-through tutorial on an exploratory analysis of EMS dispatches data using Pandas and visualizing with seaborn.

---

## data-visualization-plotly.ipynb
This notebook takes advantages of [Plotly](https://plot.ly/) for its interacitve and publication-quality graphs to visualize EMS dispatches data.

<img src="images/bar.gif" width="80%" height="80%">

<img src="images/pie.gif" width="65%" height="65%">

---

## plotly_map_plot.ipynb
A tutorial on how to use [Plotly](https://plot.ly/) to plot an interactive choropleth map by layering with [Mapbox](https://www.mapbox.com/). To use Mapbox, a free regestration is required to obtain a token.

<img src="images/map.gif" width="618" height="546" />
