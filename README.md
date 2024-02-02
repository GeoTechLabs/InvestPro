# Restaurant Investment Tool - R Shiny Application

## Overview

The Restaurant Investment Tool is an R Shiny web GIS project designed to assist in making informed decisions about suitable locations for restaurant investments. The tool employs a spatial regression model to predict the viability of different locations based on key parameters such as rent, footfall per day, food joint type, and competition distance.

## Features

- Predicts suitable locations for restaurant investments.
- Utilizes spatial regression modeling.
- Interactive web interface powered by R Shiny.
- Visualizes predictions on an interactive map.

## Project Structure

- **data**: Contains the datasets used for training the model.
- **WebProj.Rproj**: RSrudio Project.
- **app.R**: Contains the R Shiny application source code.
- **README.md**: Documentation for the project.

## Setup

1. Ensure you have R and R Shiny installed.
2. Ensure you install the leaflet package
## how to install
  install.packages("shiny")
  install.packages("leaflet")

4. Open the R Shiny application:

   ```R
   ## load libraries
   library(shiny)
   library(leaflet)
  
