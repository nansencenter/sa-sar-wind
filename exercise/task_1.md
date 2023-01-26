## 1. Task description

The goal is to get a basic understanding of Synthetic Aperture Radar (SAR) principles and its way to observe ocean surfaces with application to wind retrievals. In addition, you should get the first experience applying python for exploring and visualizing SAR data. Programming skills to learn:

* Installation of python and relevant packages (using anaconda and/or pip)
* Creating a python work environment (install packages, run notebooks)
* Writing a code in jupyter notebooks
* Python data types (e.g., int, string, float, etc.) and structures (list, dict, tuple, etc.)
* What is a function/class in python and how they work
* Common scientific python packages: NumPy, matplotlib, cartopy, pandas 
* Plotting data in python/jupyter using matplotlib and cartopy

---
## 2. Reading
Get a basic overview of SAR principles with a focus on application to ocean surface and phenomena related to the Atmospheric Boundary Layer (ABL):
1. Read [Chapter 1](http://sarusersmanual.com/ManualPDF/NOAASARManual_CH01_pg001-024.pdf) and [Chapter 2](http://sarusersmanual.com/ManualPDF/NOAASARManual_CH02_pg025-080.pdf) of [SAR Marine User Manual](http://sarusersmanual.com/) to gain overview and basic understanding of SAR
2. Read [Part III](http://sarusersmanual.com) to get more detailed information and examples on using SAR for observing ABL

The manual contains basic information but also an abundance of references to papers and books you can use to explore the topic in more detail.

---
## 3. Programming

Complete an introductory course on Python programming from any available online platform (e.g, Coursera, edX, etc.) or UCT. Use any available online resources or books which can help you to get a better understanding. The more practice the better.

**NOTE:** I would suggest starting playing with Jupyter notebooks as soon as you start learning python.

**Excercise:**

1. Download a Sentinel-1 Interferometric Wide Level 2 OCN product from the [Alaska SAR Facility (ASF) website](https://asf.alaska.edu/). You can use [data search](https://search.asf.alaska.edu) to browse, select a scene, and download the data. You will have to go through a very simple registration step to access the data. 
2. Read and explore data and metadata using python and [Nansat](https://github.com/nansencenter/nansat) (python library to read and manipulate geospatial datasets) in a Jupyter notebook. You can find more information about how to read and manipulate data in Nansat in [Nansat lectures](https://github.com/nansencenter/nansat-lectures)
3. Plot a Seigma0 VV and Sigma0 VH from the downloaded scene on a map with identification of the coast line and geographic coordinates. Do not hesitate to add any additional information you might need to explore and describe the map you produce (e.g, indicate date and time, sensor name, etc.). You will have to use python [matplotlib](https://matplotlib.org/) and [cartopy](https://scitools.org.uk/cartopy/docs/latest/) packages to complete this step.
4. Push a notebook with code and figures to the project GitHub repository

---
## 4. Writing

1. Write a page (maximum) summary about using SAR for retrieving wind speed and direction based on the reading material and any other information you can find.
2. Write an extended caption (a description) of the maps you produced during the programming exercise. The description should take not more than half a page and should reflect on the features you observe and generic information about the map. You can find some examples in [SAR Marine User Manual](http://sarusersmanual.com/)
