# Cargo-tracing-system
You have to add "allCars.csv" to project folder. This file is required for gps data. You can get file from "https://www.kaggle.com/datasets/henrikengdahl/taximovementconcatenated"  </br>  </br>

Project is about real time gps tracing but we couldn't do this real things(we don't have gps device) so we have a file. This file contain location data for Swedish taxi cars during October and November 2018. We are using this data from our project. Think like simulate. I used message broker(zeromq) too for communicate between data(allCars.cvs) and interface or database. 

