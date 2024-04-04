# README #

### RUNNING THE CONTAINER ###
* Navigate to this directory on your computer in Terminal (mac) or Powershell (Win) 
* Start: docker-compose -f docker-jupyterlab.yml up

## DEFAULT DIRECTORY ##
* Jupyter Default directory is set up as a local volume in `labs/`
* There should be 2 notebooks (.ipynb files) there that can be edited in Jupyter

## MYSQL - GETTING STARTED ##
* Connect to the container with your MySql IDE
	* SERVER HOST - localhost
	* SERVER PORT - 13306
	* LOGIN - root
	* PASSWORD - password
	* Import the csv data from `app/csv/2024 Prospect Age Database.csv` into a new table called `2024_nfl_prospects`

## JUPYTER ##
* Navigate to `http://localhost:8889`
* You can open one of the existing notebooks are create a new one.
* If you choose to use an existing you'll need to `Run All` from the menu
* If you cho0se to make a new one start importing and have fun!