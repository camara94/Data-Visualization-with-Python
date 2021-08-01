# Data Visualization with Python

## Learning Objectives
In this course you will learn about:
* Data visualization and some of the best practices when creating plots and visuals.
* The history and architecture of Matplotlib, and how to do basic plotting with Matplotlib.
* Generating different visualization tools using Matplotlib such as line plots, area plots, histograms, bar charts, box plots, and pie charts.
* Seaborn, another data visualization library in Python, and how to use it to create attractive statistical graphics.
* Folium, and how to use to create maps and visualize geospatial data.
## Syllabus 
### Module 1 - Introduction to Visualization Tools
* Introduction to Data Visualization
* Introduction to Matplotlib
* Basic Plotting with Matplotlib
* Dataset on Immigration to Canada
* Line Plots
### Module 2 - Basic Visualization Tools
* Area Plots
* Histograms
* Bar Charts
### Module 3 - Specialized Visualization Tools
* Pie Charts
* Box Plots
* Scatter Plots
* Bubble Plots
### Module 4 - Extra Visualization Tools
* Waffle Charts
* Word Clouds
* Seaborn and Regression Plots
### Module 5 - Creating Maps and Visualizing Geospatial Data
* Introduction to Folium and Map Styles
* Maps with Markers 
* Choropleth Maps
## Module 1 - Introduction to Visualization Tools
### Learning Objectives
In this lesson you will learn about:
* Data visualization and some of the best practices to keep in mind when creating plots and visuals.
* The history and the architecture of Matplotlib.
* Basic plotting with Matplotlib.
* The dataset on immigration to Canada, which will be used extensively throughout the course.
* Generating line plots using Matplotlib.
### Introduction to Data Visualization
#### Why Build Visuals ?
![whybuild](images/whybuild.png)
### Best Practices
![bestpractice](images/bestpractices.png)
### Example
![example](images/example.png)
### Example - Remove Background
![example remove bg](images/exampleremovebg.png)
### Example - Remove Border
![example remove bg](images/exampleremoveborder.png)
### Example - Remove Redundant Legend
![example remove bg](images/exampleremoveredundantlegend.png)
### Example - Remove 3D
![example remove bg](images/exampleremove3d.png)
### Example - Remove Text Bolding
![example remove bg](images/exampleremovetextbold.png)
### Example - Reduce Color
![reduce colr](images/reducecolr.png)
### Example - Remove Wedges
![remove wedges](images/removewidget.png)
### Example - Thicken Lines
![thicken lines](images/tickenline.png)
### Example - Emphasize Bacon
![emphasizebacon](images/emphasizebacon.png)
### Comparaison
![comparaison](images/comparaison.png)
### More Examples
![more example](images/moreexamples.png)
[https://www.darkhorseanalytics.com/](https://www.darkhorseanalytics.com/)
### Introduction to Matplotlib
#### Matplotlib - History
![mat](images/matplotlibhist.png)
#### Matplotlib - Archictecture
![mat](images/matplotlibarch.png)
### Backend Layer
![backend layer](images/backendlayer.png)
### Artist Layer
![artist layer](images/artistlayer.png)
### Putting the Artist Layer to Use
![putting artist](images/puttingartistlayertouse.png)
![figure](images/figartist.png)
### Scripting Layer
![scriptinglayer](images/scrptinglayer.png)
### Further Reading
![further](images/furtherreading.png)
[https://aosabook.org/en/matplotlib.html](https://aosabook.org/en/matplotlib.htm)
### Basic Plotting with Matplotlib
### Matplotlib - Jupyter Notebook
Jupyter notebook is open source web application that allows you to create and share documents that contain live code visualizations and some explonatory text as well. Jupyter has some specialized support for Matplotlib
![import matplotlib](images/importmatplotlib.png)
### Matplotlib - Plot Function
In this cours, you can already create visuals tools such as:
* histograms
* bar charts
* box plots
* and any more using one function **Plot**
### Matplotlib - Backends - inline
magic function **%matplotlib inline**, the limitation of this backend is we can not modify figure when it is rendered.
![plot function](images/plot.png)
### Matplotlib - Backends - Notebook
With a notebook backend in place, if a plt function is called, it checks if an active figure exists, and any functions you call will be applied to this active figure. If figure does not exist, it renders a news figure.
![notebook backend](images/notebookbackend.png)
### Matplotlib - Pandas
Pandas is also a built-in implementation of it. there, plotting in pandas is as simple as calling the plot function on a given pandas series or dataframe.
#### Matplotlib - Pandas - Line
![pandas built-in](images/pandasplot.png)
#### Matplotlib - Pandas - Histogram
![pandas built-in](images/pandashist.png)
### Dataset on Immigration to Canada
#### Dataset
![dataset](images/dataset.png)
#### Immigration Data to Canada
![immigration data to canada](images/immigrationdatatocanada.png)
#### Read Data into Pandas DataFrame
![read data](images/readdataintopandas.png)
#### Display DataFrame
![display dataset](images/displaydata.png)
### Line Plots
![lineplot](images/lineplot.png)
### Dataset - Recap
![data recap](images/datasetrecap.png)
### Dataset - Precessed
![processed](images/processed.png)
### Creating Line Plot
![creating line plot](images/creatinglineplot.png)
## Module 2 - Basic Visualization Tools
### Learning Objectives
In this lesson you will learn about:
* Area plots, and how to create them with Matplotlib.
* Histograms, and how to create them with Matplotlib.
* Bar charts, and how to create them with Matplotlib.
### Area Plots 
![areaplot](images/areaplot.png)
### Dataset - Recap
![datasetrecap](images/datasetrecap.png)
### Dataset - Processed
![datasetprocessed](images/dataprocessed.png)
### Generating Area Plots
![generatingareaplot](images/generatingareaplot.png)
![generatingareaplot](images/areaplot2.png)
### Area Plots
![generatingareaplot](images/areaplotfig.png)
### Histograms
![hist](images/histogramm.png)
### Dataset Recap
![data](images/datasetrecap.png)
### Dataset - Processed
![processed](images/processed.png)
### Histograms
![hist](images/histograms.png)
### Numpy - Histograms
![nphist](images/nphistogram.png)
### Bar Charts
![barchart](images/barchart.png)
### Dataset - Recap
![data](images/datasetrecap.png)
### Dataset - Processed
![dataset](images/dataprocessed.png)
### Bar Chart
![bar chart](images/barchart2.png)
## Module 3 - Specialized Visualization Tools
### Learning Objectives
In this lesson you will learn about:
* Pie charts, and how to create them with Matplotlib.
* Box plots, and how to create them with Matplotlib.  
* Scatter plots and bubble plots, and how to create them with Matplotlib.
### Pie Charts
![piechart](images/piechart.png)
### Dataset - Recap
![data](images/datasetrecap.png)
### Dataset - Processed
![dataset](images/dataprocessed.png)
### Pie Chart 
![df_continent](images/dfcontinents.png)
![piechar](images/piechart2.png)
### Outcomes
![outcomes](images/outcome.png)
### Pie Charts Flows
![piechartflows](images/piechartflows.png)
[https://www.surveygizmo.com/survey-blog/pie-chart-or-bar-graph](https://www.surveygizmo.com/survey-blog/pie-chart-or-bar-graph/)
### Box Plots
![boxplot](images/boxplot.png)
### Dataset - Recap
![data](images/datasetrecap.png)
### Dataset - Processed
![dataset](images/dataprocessed.png)
### Box Plots
![boxplot](images/boxplot2.png)