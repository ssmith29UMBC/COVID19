# COVID19


\chapter{Description of Code}

This appendix provides a brief description of the code and the location of the notebooks used during the experimental portion of the research. Copies of the Jupyter Notebooks and associated data are stored in the following github repository: https://github.com/ssmith29UMBC/COVID19. 

\section{Visualizations}

MAP.ipynb provides the code for building the visualization in Figure 3.1 and visuals.ipynb contains the code for building the visualizations in Figures 3.2-3.6. 

\section{Forecasting Models}

I used four separate notebooks to build the forecasting models. Iterative.ipynb notebook contains the code that build the case and death forecast models trained with population density and tested on the consecutive fourteen days. It also includes the visualizations and comparisons of the results. Iterative No Density.ipynb notebook contains the code that build the case and death forecast models trained without population density and tested on the consecutive fourteen days. It also includes the visualizations and comparisons of the results. Testing January.ipynb tested the models trained with population density against the data from 29 Dec 2020 - 11 Jan 2021. It also includes the metrics and visualizations for these models. Testing January No Density.ipynb tested the models trained without population density against the data from 29 Dec 2020 - 11 Jan 2021. It also includes the metrics and visualizations for these models. 

\section{Datasets}
These notebooks rely on the following datasets: popden.csv, US\_counties.csv time\_series\_covid19\_confirmed\_US.csv, and time\_series\_covid19\_deaths\_US.csv. These data files include aggregated data from Johns Hopkins University\footnote{https://github.com/CSSEGISandData/COVID-19/tree/master/csse\_covid\_19\_data/csse\_covid\_19\_time\_series}, Kaggle\footnote{https://www.kaggle.com/johnjdavisiv/us-counties-covid19-weather-sociohealth-data}, and US Census Bureau\footnote{https://www.census.gov/data/datasets/time-series/demo/popest/2010s-counties-total.html}. 
