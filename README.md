# CovidTracker
A web application to track Covid-19 cases in India

## Description
CovidTracker is a web application that showcases a dashboard containing chart visualizations attributing to the available Covid-19 data in India. This application is a purely front-end based, thus at the moment it doesn't provide backend funcitonalities like database linking or the capacity to store user information to further personalize the application experience.

## Get Started
In order to use the web application, you will need to download the project folder. Github allows you to download the project folder in .zip format. Unzip the file. You will see a folder named covidTracker-master. Inside you will see the following list of files

![dir_project](https://user-images.githubusercontent.com/29114760/80819130-075b6c80-8bf2-11ea-9949-b4527cde626f.JPG)

You can directly click the html documents to view them.
The register and login pages can be seen by clicking their corresponding html documents. 

### index.html
The actual web application can be viewed by clicking the index.html document which will prompt open a webpage that visualizes the Covid-19 data of India. On the side navigation bar, you can click the **State Wise Database** to open up a page that shows state wise status around Covid-19 virus. The data used in visualization is being queried from a json file: [Covid-19 India](https://api.covid19india.org/data.json)

The**State Wise Database** can directly be viewed by clicking the tables.html in the main directory. 

### vendor folder
This folder is a special folder that contains libraries that are used to add more functionalities to the dashboard web app
* **chart.js** is a special library that allows the creation of interactive charts in an html document in accordance with the data fed into the its parameters. This library is used to make charts like the bar and pie chart. 
* **fontawesome-free** contains svg icons and different fonts used in the html document.
* **jquery** is a library used to extract elements from the web document and further add interactivity to it.

The js folder contains the javascript files that are used to provide dynamic behavior to the web documents and the css folder contains css files that are used to style the web pages.




