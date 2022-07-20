# MetDataDashboard

A shiny dashboard that shows available meterological sites in the uk and allows you to download the met data in a CSV or ADMS Met format. 

The application is built with the Shiny framework for the R programming language. The application layout is produced with the flexdashboard package, and the charts and maps use visdat and Leaflet.js, all accessed through their corresponding R packages.

Meteorological data is retrieved from NOAA Integrated Surface Database using the worldmet R package.

I welcome feedback and suggestions in issues.

To Do:

merge more met data into sites from other sources
