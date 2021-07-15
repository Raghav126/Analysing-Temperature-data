# <div align="center"> Analysing Temperature data </div>
<p>This project analyse the temperature data of Gujarat and Mahabaleshwar(Maharastra) from year 2005 to 2014. And it visualize a record high and a record low temperatures by day of the year over the period 2005-2014 by plotting the data onto a line graph. It Overlays a scatter of the 2019 data for any points (highs and lows) for which the ten year record (2005-2014) record high or record low was broken in 2019.</p>

## Steps to follow
1. Clone the repository to specific folder in your computer.
1. Create Virtual environment in the project folder of the computer.

- #### Windows
  - Firstly, open command prompt window in your project folder.
  - Run `python -m venv example_env` in cmd window. (example_env is the name of the virtual environment. you can replace it with the name you want.)
  - To activate the virtual environment you created, run: `example_env\Scripts\activate.bat`.
  - Now, its time to install the libraries mentioned in the requirements.txt file that are used to build this project. Run `pip install -r requirements.txt`.

3. The data for this project comes from a subset of The National Centers for Environmental Information (NCEI) [Daily Global Historical Climatology Network (GHCN-Daily)](https://www.ncdc.noaa.gov/cdo-web/search?datasetid=GHCND). The GHCN-Daily is comprised of daily climate records from thousands of land surface stations across the globe.
4. I had specifically download the data for Gujarat's station, you can download the data of your area by surfing this [site](https://www.ncdc.noaa.gov/cdo-web/search?datasetid=GHCND) or you can use my dataset which is given in this repository.
5. Run the `ProjectDS.ipynb` file on your virtual environment.
6. I have given one JPG file which shows the output of map with red dots which shows the stations that we had used for our analysis.

**Note:** Install only those versions of libraries on your virtual environment, which I have mention in `requirements.txt` file (to install correct versions, please follow above steps). Otherwise output of the __map__ will not rendered on your screen and it gives error.







