![GMIT Logo](https://github.com/Munster2020/HDIP_CSDA_COMP08050_PROJECT/blob/main/GMIT_Logo.jpg)
# Higher Diploma in Science in Computing (Data Analytics)
## Programming for Data Analysis (COMP08050) - Project 2020
The aim of this module is to develop programming skills towards the effective use of data analysis libraries and software.
Students learn how to select efficient data structures for numerical programming, and to use these data structures to transform
data into useful and actionable information.

### 1. Repository Structure
1. Readme:
[README.md](https://github.com/Munster2020/HDIP_CSDA_COMP08050_PROJECT/blob/main/README.md)

2. Jupyter Notebook:
[project2020.ipynb](https://github.com/Munster2020/HDIP_CSDA_COMP08050_PROJECT/blob/main/project2020.ipynb)

3. Excel version of simulated data:
[simulated_data.xlsx](https://github.com/Munster2020/HDIP_CSDA_COMP08050_PROJECT/blob/main/simulated_data.xlsx)

4. Images Folder
[images](https://github.com/Munster2020//HDIP_CSDA_COMP08050_PROJECT/tree/main/images)

If you have any issues viewing tasks2020.ipynb in github you can use Jupyter NBViewer which is a web application behind The Jupyter Notebook Viewer at https://nbviewer.jupyter.org/

### 2. Software used

![logo](https://github.com/Munster2020/HDIP_CSDA_COMP08050_PROJECT/blob/main/images/JupyterN.png "Jupyter")
![Jupyter](https://jupyter.org/) Jupyter is a free, open-source, interactive web tool known as a computational notebook, which researchers can use to combine software code, computational output, explanatory text and multimedia resources in a single document. (Source:downloads.com)

![logo](https://github.com/Munster2020/HDIP_CSDA_COMP08050_PROJECT/blob/main/images/cmdr.png "Cmder")
![Cmdr](https://cmder.net/) provides you with an alternative to the Windows default command prompt utility through a more capable console emulator that also comes packing a good-looking graphical user interface. (Source:downloads.com)

---
### 3. Project

__Problem statement__: For this project you must create a data set by simulating a real-world phenomenon ofyour choosing.  You may pick any phenomenon you wish – you might pick one that isof interest to you in your personal or professional life.  Then, rather than collect datarelated to the phenomenon, you should model and synthesise such data using Python.We suggest you use thenumpy.randompackage for this purpose.Specifically, in this project you should:

- Choose a real-world phenomenon that can be measured and for which you could collect at least one-hundred data points across at least four different variables.

- Investigate  the  types  of  variables  involved,  their  likely  distributions,  and  their relationships with each other.

- Synthesise/simulate a data set as closely matching their properties as possible.

- Detail your research and implement the simulation in a Jupyter notebook – the data set itself can simply be displayed in an output cell within the notebook.


Note that this project is about simulation – you must synthesise a data set.  Some students may already have some real-world data sets in their own files.  It is okay to base your synthesised data set on these should you wish (please reference it if you do),but the main task in this project is to create a synthesised data set.

The project is divided into nine sections outlined below.

__1.0__ Introduction

__2.0__ Libraries

__3.0__ Dataset

__4.0__ Overview

__5.0__ Detailed Analysis

__6.0__ Flight Status

__7.0__ Simulation

__8.0__ Simulation Analysis

__9.0__ Comparison

---

__1.0 Introduction__: In this section I provide an overview of the real-world phenomenon I decided to generate my simulated data on. It also includes a brief introduction to simulation and synthetic data and an outline of where I sourced the dataset from. The real-world phenomenon I chose to look at related to aviation, more specifically information on flight delays at US airports and the type of delays experienced. I wanted to understand the relationship between flight delays and flight volume. I need to point out now that if I had had a chance to choose a dataset again, I would not have chosen this one. I will explain this in more detail later but suffice it to say the data had been cleansed already, was aggregated and had little categorical variables. In retrospect I should have chosen one that was a date series or time series for flights at an individual airport or more but which hadn’t been aggregated to a monthly view. I would also have liked if there had been more categorical variables with perhaps a status for individual flights.

__Learnings__: When researching an interesting dataset to analyse take your time. I also learned to download and add additional functionality in Jupyter Notebooks, including using the add-ons "Autopep8", "spellchecker" and "Table of Contents(2)". Autopep8 is excellent for formatting your code correctly, while spellchecker comes in handy in correcting those pesky spelling mistakes.

__Topics__: research, simulation, synthetic data.

---

__2.0 Libraries__: This section covers importing the libraries used for this project. I used Pandas for importing and manipulating the dataset. NumPy for generating the synthetic dataset and Matplotlib and Seaborn for data visualisation. I also used SciPy for the identification of the distributions of the dataset variables.

__Learnings__: I learned two things in this section. I got an understanding of the SciPy stats module and a way of making plots clearer by using the magic command %config InlineBackend.figure_format = ‘retina’.

__Topics__: libraries, Pandas, NumPy, SciPy, retina display magic command.

---

__3.0 Dataset__: 

