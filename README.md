# Covid-19 Report Painel

![Intro Pic](images/main.png)

## Table of Contents
1. [Project Motivation](#Motivation)
2. [Getting Started](#getting_started)
	1. [Dependencies](#dependencies)
	2. [Installing](#installing)
	3. [Executing Program](#executing)
3. [Authors & Licensing](#authors)

<a name="motivation"></a>
## Motivation

This is a project for the Einstein Floripa selection process.

<a name="getting_started"></a>
## Getting Started

<a name="dependencies"></a>
### Dependencies
* Python 3.5+ (I used Python 3.7)
* Data Science libraries: NumPy, Pandas
* Web App and Data Visualization: Flask & Plotly
* Requests library for getting data from API's

<a name="installing"></a>
### Installing
Clone this GIT repository:
```
git clone https://github.com/gabrielboehme/Disaster-Response-Painel.git
```
<a name="executing"></a>
### Executing Program:
1. Run the following commands in the project's root directory to set up your database and model.

    - To run ETL pipeline that cleans data and stores in new .csv files
        `python ETL/transform_covid.py`

2. Run the following command in the app's directory to run your web app.
    `python app.py`

3. Go to http://localhost:5000/

<a name="Author"></a>
## Authors

* [Gabriel Boehme](https://github.com/gabrielboehme/)

<a name="acknowledgement "></a>
## Acknowledgements

* [Einstein Floripa](https://einsteinfloripa.com.br/) for providing the dataset.


<a name="screenshots"></a>
## Screenshots

1. Example of KPI's:

![KPI's](images/KPI.png)

2. Example of Deaths by State plot:

![Deaths](images/Mortes_estado.png)


3. Example of Cases by State plot:

![Cases](images/Casos_estado.png)


4. Example of correlation between features heatmap plot:

![Heatmap](images/Heatmap.png)
