# Master's Thesis. Artificial Intelligence in the press: a comparative analysis of ideologically diverse newspapers

### Author: Isabel Molero López
### Master in Computational Social Science

## Description

This Master's thesis repository contains the code needed to do the analysis of articles on artificial intelligence published from 2014 to 2023 by two digital media. It is explained how the process of extracting the content by means of and the date of each article in the two media has been carried out, how the data has been cleaned, visualizations have been made and text analysis has been carried out. All this was done using the RStudio tool. First of all, web scraping techniques were used to obtain the information. For this purpose, it was necessary to use the RSelenium R package, which allows remote interaction with the websites. For the visualizations the package ggplot2 has been used and, finally, several text analysis tools have been used in R. That is why this repository is composed of three main documents: three rmd files in which all the code necessary to replicate the work is found. In these files the commented code is presented in such a way that anyone who needs it can make the modifications they wish.

To use the code in this project you will need to have installed R and RStudio.  



![imagen](https://github.com/isabelml/tfm_r_project/assets/113594617/6c78e0df-26df-4a2d-95cf-c4b768ec24cc)

## Installation instructions: the Docker

Before starting the webscraping process a docker must be installed.
It is a container where we can run applications (in this case RStudio) and allows us to make more easy our work with a website (the Selenium browser is created into the docker container).
It can be installed from here: [Docker installation](https://www.docker.com/products/docker-desktop/)

Once the Docker is downloaded and installed in our computer, we have to open the control panel of our computer and execute the following lines: 
1. To pull the image: docker pull selenium/standalone-firefox
2. To start the Docker container: docker run -d -p 4445:4444 selenium/standalone-firefox

Before executing the code in the rmd file you need to ensure that the status of your Docker container is "running":

![imagen](https://user-images.githubusercontent.com/113594617/224956341-7695b0ba-40b5-4da4-a023-7474f6d84536.png)


## Usage instructions

In this project you will find three RMD files with all the code needed to perform the web scraping process, data cleaning, data visualization and text analysis.

### Project structure

#### 1. Web scraping
#### 2. Data cleaning
#### 3. Data visualization
#### 4. Text analysis

### Files you will find in this project

- **web_scraping_ai**. This rmd file generates the csv files with the articles news. 
- **data_cleaning_ai**. This rmd file generates two csv files with the data ready to perform visualizations and text analysis. 
- **visualizations_ai**. This file contains the code needed to make a line graph with the frequency of articles published each year on AI in the two digital newspapers and to perform the text analysis.
- **Images**. Folder with images used to illustrate part of the process.

### Contact information
- Isabel Molero - github.com/isabelml. **Master in Computational Social Science.**


