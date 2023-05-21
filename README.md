
<!-- Improved compatibility of back to top link: See: https://github.com/othneildrew/Best-README-Template/pull/73 -->
<a name="readme-top"></a>



![Python](https://img.shields.io/static/v1?style=for-the-
badge&message=Python&color=3776AB&logo=Python&logoColor=FFFFFF&label=)
![Jupyter](https://img.shields.io/static/v1?style=for-the-
badge&message=Jupyter&color=F37626&logo=Jupyter&logoColor=FFFFFF&label=)
![Tableau](https://img.shields.io/static/v1?style=for-the- badge&message=Tableau&color=E97627&logo=Tableau&logoColor=FFFFFF&label=) 
[![MIT License][license-shield]][license-url]
[![LinkedIn][linkedin-shield]][linkedin-url]

[license-shield]: https://img.shields.io/github/license/othneildrew/Best-README-Template.svg?style=for-the-badge
[license-url]: https://github.com/JoshuaOlubori/UK-Road-Accident-Casualties/blob/f47c7d604613183d31617d101d14ef5c96503f1d/LICENSE.txt
[linkedin-shield]: https://img.shields.io/badge/-LinkedIn-black.svg?style=for-the-badge&logo=linkedin&colorB=555
[linkedin-url]: https://linkedin.com/in/joshua-edun


<!-- PROJECT LOGO -->
<br />
<div align="center">

  <h3 align="center">Tracking a Pandemic with Data</h3>

  <p align="center">
    Featuring Python and Tableau
     <br />



<!-- TABLE OF CONTENTS -->
<details>
  <summary>Table of Contents</summary>
  <ul>
    <li><a href="#overview">Overview</a></li>
        <li><a href="#task">Task</a></li>
        <li> <a href="#application">Application</a></li>
        <li><a href="#screenshots">Screenshots </a></li>
    <li><a href="#contact">Contact</a></li>
  </ul>
</details>


<div align="left">
<!-- ABOUT THE PROJECT -->
  
## About The Project 🍪 

![code](https://github.com/JoshuaOlubori/UK-Road-Accident-Casualties/blob/ddb49a64610e84d36ded41d2096050e7a2f3c183/report.png)

Code segment
<a name="requirement"/>

### Overview

he year 2020 will go down in history as one drastically shaped by a virus that, as of late October, had infected more than 40 million
people worldwide. Apt assessments have compared what’s happening now to the devastations of the 1918 flu pandemic. But what’s different today is how technology has allowed us to see, almost in real time, where the virus is spreading, how it’s mutating, and what effect it’s having on economies across the world.
This detailed view of COVID-19 is made possible thanks, in part, to a new generation of huge datasets—hundreds of genomes, millions of tweets—along with advances in computing power and the analytical methods to study them. (Credits Katherine Unger Baillie et al., 2020)
The Nigeria Centre for Disease Control (NCDC) through the National Emergency Operations Centre (EOC) has continued to lead the national public health response in Nigeria with oversight of the Presidential Task Force on COVID-19 (PTF-COVID-19). The NCDC is also working closely with all states of the Federation to support their response activities to the pandemic.(NCDC coronavirus COVID-19 advisory, 2022)
In light of this, data collection and analysis is necessary to inform the appropriate response, planning and allocation of resources.
This is an interactive dashboard on the COVID-19 pandemic in Nigeria, reflecting information emerging on the disease and its impact on the Nigerian population.


<!-- -->
  <a name="task"/>
  
## Task 📌

To design a Tableau dashboard to clearly visualize the COVID-19 pandemic in Nigeria since the start of the pandemic in 2020. Key metrics to show include total number of cases, infection rate, fatality rate e.t.c.
My audience is the general public and therefore the viz is to be hosted on Tableau Public.
  
<a name="prepare"/>
  
### Prepare 🧹
Where was the data located and organized?

The data was sourced from the NCDC (Nigerian Centre for Disease Control) and accessed via [link](https://data.humdata.org/m/dataset/nigeria_covid19_subnational) on the 15th of May, 2022.
The dataset was contained in a CSV file, arranged in 14 columns with the headers written in French. That had to be taken care of in the data cleaning process.

#Are there issues with bias or credibility in this data?
There are concerns that the data from Nigeria may not completely reflective of the true situation on ground due to low testing rates compared to Western countries.
#Are there any problems with the data?
Problems of note include the columns headers being in French and a few redundant columns.

  <a name="screenshots"/>
  
### Process ⚙️

#What tools are you choosing and why?
For data cleaning, exploratory data analysis (EDA) and visualization, I choose Python's pandas with Jupyter Notebooks. I like pandas versatility with handling data and together with Jupyter Notebook's flexible running of code in cells, it makes for an efficient workflow.
#What steps have you taken to ensure that your data is clean?
I opened a folder for the project on my PC and named the file with an appropriate naming convention.
Then I imported the dataset using pandas and inspected the first few rows, the last few rows, the columns, th.e shape and some summary statistics of the data to confirm that it was imported correctly and to have a feel of the data.
Using a mapping function, I renamed the column headers appropriately. Where null values where present, I filled in with zero. The Jupyter Notebook file delineates the whole data preparation process

On preliminary exploration on Excel, I discovered that date values on some of the tables were inconsistently formatted. Therefore all date fields have to be homogenized going forward

I did all data cleaning and wrangling with Python's pandas on Jupyter Notebooks.
The codes can be accessed via [link](https://github.com/JoshuaOlubori/Data-Science-Analytics-Portfolio- Projects/blob/main/Covid_19_in_Nigeria/nga_covid19.ipynb)


  <a name="insights"/>
  
### Insights 🕵🏽‍♂️
1.The states of Lagos, Federal Capital Territory (Abuja), and Rivers have the highest confirmed cases most likely due to their being port cities and Lagos' high population density.
2.There are 246,889 confirmed cases, 223,634 recoveries and 3079 deaths.
3.December 22nd, 2021 saw the highest number of confirmed cases at 4,006 while August 29th, 2021 was the peak of total deaths at 93.
The visual can be viewed amd interacted with [link](https://public.tableau.com/views/Covid- 19InNigeria/Dashboard?:language=en- GB&publish=yes&:display_count=n&:origin=viz_share_link)

<!-- CONTACT  ☎️ -->

  <a name="contact"/>
  
## Contact

Edun Joshua Olubori - [connect on linkedin](https://www.linkedin.com/in/joshua-edun) - joshuaolubori@gmail.com

<p align="right">(<a href="#readme-top">back to top</a>)</p>

footnotee
[a] Katherine Unger Baillie, Credits, Baillie, K. U., Berger, M. W., Brockmeier, E. K., Writers, Date October 28, Date, 28, O., Subtopics Data Science, Subtopics, Science, D., Schools School of Engineering & Applied Science, Schools, School of Engineering & Applied Science, Share Twitter Facebook, Share, & Twitter Facebook. (1970, May 26). The role of data in a world reshaped by covid-19. Penn Today. Retrieved May 30, 2022, from https://penntoday.upenn.edu/news/role-data-world-reshaped-covid-19
[b]NCDC coronavirus COVID-19 microsite. Retrieved May 30, 2022, from https://covid19.ncdc.gov.ng/advisory/



