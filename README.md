# DS_project_1

## Obtaining Data

We started with obtaining the top 200 movies for 2015, 2016, 2017 and 2018, as well as the top 600 for 2019 from Box office mojo by copying data to csv files. 

The names of the movies were then extracted and formatted correctly so that the rest of the required information could be obtained using the OMBD API. This was done in the Notebook Obtaining Data using OMDB API.ipynb.

## Data Cleaning

The data obtained was separate for each year so they were all merged together into one main csv file.
This was done in two separate Notebooks Merging Multiple Year Data.ipynb and Merging Process Final.ipynb.


Empty and unnecessary columns from the data were dropped. The contents were processed and converted to the correct datatypes. The actors and genres were all created into separate columns containing boolean values. 

Movies entries without any financial information were also dropped.

## Plotting

The data was then plotted using the Plotly library, by creating sub dataframes for each plot as the main dataframe was too large to handle easily (1245, 3772). 

Some of the cleaning was done along with the merge process and the rest was done during plotting. 

All the plots along with some of the later cleanup is contained in the Cleaning and Plotting.ipynb Notebook.

## Presentation

Canva was used to prepare slides using the plots generated using Plotly.