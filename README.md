
# WebDesign-Weather_Pages_with_Bootstrap
These webpages act as a dashboard for the visualizations I created with the WeatherPy file (see **API-Weather_Analysis_and_Mock_Vacation_Planning_with_OpenWeatherMapAPI**) repository.  Specifically, we'll be plotting [weather data](Resources/cities.csv).
This dashboard has an individual page for each plot and a means by which the user can navigate between them. These pages contain the visualizations and fake text representing the graphs explanation. There is also a landing page, where a comparison of all of the plots can be seen, and another page where we can view the data used to build them.

The website consists of 7 pages total, including:
* A [Landing page](Landing_Page.html) containing:
	* An explanation of the project.
	* Links to each visualizations page. 
* Four visualization pages ([Cloudiness](Cloudiness_Page.html), [Humidity](Humidity_Page.html), [Max Temperature](Max_Temp_Page.html), and [Wind Speed](Wind_Speed_Page.html)) each with:
	* A descriptive title and heading tag.
	* The plot/visualization itself for the selected comparison.
	* A paragraph describing the plot and its significance.
* A [Comparisons page](Comparisons_Page.html) that:
	* Contains all of the visualizations on the same page so we can easily visually compare them.
	* Uses a Bootstrap grid for the visualizations.
	* The grid must be two visualizations across on screens medium and larger, and 1 across on extra-small and small screens.
* A [Data page](cities_table.html) that:
	* Displays a responsive table containing the data used in the visualizations.

### Tech Stack
* HTML
* Bootstrap
* CSS
* Jupyter Notebook
* Python

### User Instructions
* Clone the repository: git clone https://github.com/DarrylB32/WebDesign-Weather_Pages_with_Bootstrap.git
* Using your internet browser, open the [Landing_Page](Landing_Page.html) file (from here you should be able to navigate through each webpage)

### Additional Notes
 - The paragraph of text accompanying each weather visualization page has been copy and pasted and is the same for each visualization